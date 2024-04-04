# Spam_Mail_Detection

Dependicies:
  python
  Numpy 
  pandas 
  scikit-learn

Use of 
  LabelEncoder : to encode spam or ham into 0,1.
  TfidfVectorizer: to convert the mail message into matrix of count.
    TF-IDF stands for "Term Frequency-Inverse Document Frequency".
    TF-IDF(w, d, D) = TF(w, d) * IDF(w, D).
    where:
      TF(w, d) represents the Term Frequency of word w in document d.
      IDF(w, D) represents the Inverse Document Frequency of word w in the entire document d.

Model:
  Logistic Regression

Accuracy: 96%
