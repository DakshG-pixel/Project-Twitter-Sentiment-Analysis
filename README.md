# Project-Twitter-Sentiment-Analysis
<b>Sentiment Analysis</b>: It is the interpretation and classification of emotions (positive, negative) within text data using text analysis techniques. Sentiment analysis allows organizations to identify public sentiment towards certain words or topics
This project performs sentiment analysis on Twitter data to classify tweets as positive or negative. It utilizes machine learning techniques to train a model that can predict the sentiment of a given tweet.

# Project Structure
* Importing dependencies
* Importing dataset
* Preprocessing Text
  * used regular expressions to remove urls,usernames,non alphanumeric text, emojis, consecutive letters etc
  * stopwords removal and used a predefined emojis dictionary to replace a given emoji with it's sentiment intended
  * used nltk's WordNetLemmatizer to lemmatize words(convert them in their base form)
* Analysing data(wordcloud)
* Splitting data
* TF-IDF Vectoriser(to form matrix of tfidf features)
* Transforming Dataset
* Creating and Evaluating Models
  * LinearSVC Model
  * Logistic Regression Model(best accuracy)
  * Multinomial Naive Bayes model(fastest)
* Using the Model on example text samples

# libraries used
numpy, pandas , re , matplotlib, wordcloud, time, NLTK(natural language toolkit), sklearn(sci-kit learn)

Contributions to this project are welcome! If you have any suggestions, bug reports, or feature requests, please submit an issue or a pull request.
