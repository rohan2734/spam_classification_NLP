# spam_classification_NLP

- This project is about the spam classification of the SMS messages extracted from Grumbletext website 
- you can find more about the dataset ![here](https://archive.ics.uci.edu/ml/datasets/SMS+Spam+Collection)

## steps followed in the project

### labelling
- I had identified that there are two labels, "ham","spam"
### Data cleaning and text preprocessing
- I had done the text preprocessing which includes removing stop words, removing punctuation marks, and lowering the words
- I used the nltk corpus for stopwords
- I used PorterStemmer for stemming the dataset.

### Vectorization
- I created Bag of words using TF-IDF 
- I used the Tf-Idf count vectorizers fit transform
- I limited the max features to be 2500 , this is a important parameter to build vocabulary

### Classification
- After vectorization , I used RandomForestClassifier to classify the messages into spam and ham

### Metrics
- I used confusion matrix, accuracy score for evaluating the performance model,and its accuracy is 98.4%


- Thanks for reading till the end, if you have any opportunities in AI , ML , DL ,NLP, feel free to reach me out on ![Linkedin](https://www.linkedin.com/in/rohandevaki/) or ![Email Id](mailto:jagandevaki1@gmail.com) , 
