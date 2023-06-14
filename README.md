![image](https://github.com/dsaadeh21/Geolocation-Prediction-from-Tweets-Yachay.ai/assets/110855552/6ee0077d-ee91-4838-939d-66f954cdca1f)

Welcome to the repository for the Geolocation Prediction from Tweets project, developed during an externship at Yachay.ai. This project aims to predict the geolocation of tweets by leveraging deep learning techniques. Below is an overview of the project:

# Project Overview
- Preprocessed and performed Exploratory Data Analysis (EDA) on a dataset containing over 600,000 tweets.
- Developed and trained a Keras functional API regression model that incorporates a deep learning approach using BERT for geolocation prediction.
- Dataset and User Data
- The dataset consists of tweet information, with each row containing the following user data:

- 'text': The content of the tweet.
- 'id': The unique ID of the tweet.
- 'user_id': The ID of the user who posted the tweet.
- 'cluster_id': The assigned ID related to the area from which the tweet was posted.
- 'timestamp': The date and time when the tweet was posted.
- 'lat': The latitude of the tweet.
- 'lng': The longitude of the tweet.

# Added Features
Additional features were incorporated into the model, including:

- 'region': The region location of the tweet.
- 'language': The language of the tweet.
- 'tweet_day': The day the tweet was posted.
- 'tweet_month': The month the tweet was posted.

#Model Inputs and Loss Metrics
The model takes two inputs: 'text' and three different Natural Language Processing (NLP) features. These NLP features are:

- 'tweet month': The month in which the tweet was posted.
- 'tweet day': The day of the tweet.
- 'language of tweet': The language in which the tweet was written.

# The model's loss metrics include:

- 'haversine_distance': Calculates the distance in kilometers.
- 'mse': Mean Squared Error.

# Results
The model was trained for 7 epochs, and the performance on the test set was as follows:

- haversine_distance: 1334 KM
- mse: 149 km squared

It is worth noting that a similar model trained solely on tweet text as input yielded higher loss and mse values, indicating that incorporating NLP features improves the overall performance.

Please explore the code and documentation within this repository for more details about the project and its implementation.

- Note: The provided results are based on a specific experiment, and your results may vary depending on the dataset and configuration used.
![image](https://github.com/dsaadeh21/Geolocation-Prediction-from-Tweets-Yachay.ai/assets/110855552/ef67720b-bb92-40f8-ae9e-9bd5f4ffb889)
![image](https://github.com/dsaadeh21/Geolocation-Prediction-from-Tweets-Yachay.ai/assets/110855552/f1a9f22a-0144-4427-b3dc-c46aff6ad0ad)

