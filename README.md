# IMDb-Movies-Sentiment-Analysis 🍿👀📽
In this project I develop several sentiment classifiers for the dataset 
[imdb-reviews.csv](https://drive.google.com/file/d/16TrTTwS0KTnqPFHC6TQm0ZGCHn5biA7E/view?usp=share_link). Each row in the dataset contains a URL for an IMDb movie (https://www.imdb.com/), a score between 0.0 and 10.0 and a review text. The classifier deals with 2 classes: negative sentiment (score between 0.0 and 4.0) and positive sentiment (score between 7.0 and 10.0). There are no reviews with intermediate scores in the dataset. The models I used are:

* **Logistic Regression** experimenting with **TF-IDF** and **Bag Of Words** as input.\
 Related filename: *logistic_regression.ipynb*\
 Link to Google Colaboratory:
 [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/192mvLxVo1RFCTUASoQ_IDjgY5w7EHVor?usp=share_link)

* **Feed Forward Neural Networks** using **GloVe word embeddings** ([GloVe](https://nlp.stanford.edu/projects/glove/)) as input.\
 Related filename: *FNN.ipynb*\
 Link to Google Colaboratory:
 [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1qMsEBs7_Blkys8rzSmlTOHWr0J3eNDa5?authuser=2#scrollTo=fMGmxNGYMZ8G)

* **Bidirectional stacked RNNs with LSTM/GRU cells** using **GloVe word embeddings** ([GloVe](https://nlp.stanford.edu/projects/glove/)) as input.\
 Related filename: *BiRNN.ipynb*\
 Link to Google Colaboratory:
 [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1QXNT4XbYM0DVylO2AmNzVcpRFHaNv9ay?authuser=2)

* **Pretrained BERT-base model**.\
 Related filename: *Bert.ipynb*\
 Link to Google Colaboratory:
 [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1WhSohvmgR0CoWbZAKlSjgG0euogEd8nf?authuser=2)
