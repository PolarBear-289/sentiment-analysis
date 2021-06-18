# sentiment-analysis
Sentiment Analysis is the process of ‘computationally’ determining whether a piece of writing is positive, negative or neutral. 
It’s also known as opinion mining, deriving the opinion or attitude of a speaker.

![sentiment-analysis](https://user-images.githubusercontent.com/60652108/121798954-f7acb500-cc46-11eb-9994-5a6205405f7c.jpg)

Steps to be followed:-
•	Read the datasets using pandas library
•	Clean the data using re library to remove all the external information, to reduce the suffix and prefix I have used nltk.snowball.steamer.
•	Used word tokenizer and stopwords(English) to filter the data more.
•	Split the dataset into test and train test
•	Used count vectorizer and TFIDF to convert the data into vectors and fit them into the sets.
•	Used Multinomial Naïve byes theorem to create the model.
•	Dumped the model using pipeline
•	Create an app using streamlite 
Conclusion:
Created an app the app successfully that analyze the given statement and provide the output based on that.

Note-Few features may not work now as I am currently working on updgrading the model and pre-processing part using tweepy api.




