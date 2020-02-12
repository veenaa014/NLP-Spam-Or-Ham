# NLP-Spam-Or-Ham
SPAM Classifier:

Classifies text message or email as spam or ham (not spam). I used the dataset from UCI Machine learning repository - sms spam collection data.

I created a pandas dataframe from the UIC dataset, then performed cleaning and pre-processing.

Data Preprocessing is done using re, nltk.

For stemming purposes, I have used PorterStemmer. Stemming is a technique that helps find the root of the word.

With use of Regular expression I have removed punctuation marks and numbers since they are not necessary.

'Corpus' contains all the root words of the message(stopwords are also removed at this stage).

I have converted this corpus data into bag of words and trained the model using Naive Bayes classification. With this model, I'm able to get an accuracy of 0.9
