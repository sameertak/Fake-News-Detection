# Fake-News-Detection
-------------------------------------------
Libraries used:-
-------------------------------------------
-numpy

-pandas

-regex

-nltk

-sklearn

What's done in the code?
--------------------------------------------
1) I combined the train and test csv files. And filled the NaN values with empty strings.
2) Made a new column (named "content") which contains 'Author Name' + 'Title' of the news.
3) Used PortStemmer (from nltk library) to make the words to its root word (Example:- (actor, actress, acting --> act))
4) Seprated the Content with the Labels.
5) Converted Textual data to Numerical data with the help of TfifVectorizer.
6) Then applied train test split.
7) Achieved 97% accuracy with Logistic Model.
8) Used the same model for the test dataset.


Dataset
-----------------------------------------
The dataset is collected from Kaggle.
Link:- https://www.kaggle.com/c/fake-news/data?select=train.csv
