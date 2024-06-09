# Movie Rating Prediction using Machine Learning

This project aims to predict movie ratings based on various features such as genre, director, and actors using machine learning techniques in Python. Movie rating prediction is valuable for understanding audience preferences and aiding decision-making processes in the film industry.

Features

Dataset: The dataset includes movie data with features like year, duration, genre, director, and actors, along with corresponding ratings.
Data Preprocessing: Missing values are handled, categorical variables are encoded, and feature engineering is performed to prepare the data for modeling.
Modeling: Several machine learning models, including Linear Regression, Random Forest Regressor, Gradient Boosting Regressor, and XGBoost Regressor, are trained and evaluated for predicting movie ratings.
Model Evaluation: Mean Squared Error (MSE) and R-squared metrics are used to evaluate model performance. Feature importances are analyzed to understand the factors influencing movie ratings.
Model Deployment: The final XGBoost Regressor model is saved for future use, and an example of predicting the rating of a new movie is provided.

Key Findings

The XGBoost Regressor model achieved the best performance in terms of MSE and R-squared.
Features such as genre, director, and actors play significant roles in predicting movie ratings.
The deployed model can be used to predict the rating of new movies based on their features.

Future Improvements

Explore additional features such as movie budget, language, and production studio for enhanced prediction accuracy.
Implement advanced techniques like natural language processing (NLP) for analyzing movie reviews and incorporating sentiment analysis into the model.
Develop a user interface or web application for interactive movie rating prediction and recommendation.

Tools and Libraries Used

Python

- pandas
- NumPy
- scikit-learn
- XGBoost
- Matplotlib
- seaborn

Dataset

The dataset used in this project contains movie data and is available in the file "IMDb Movies India.csv". It includes information such as movie title, release year, duration, genre, director, actors, and ratings.
Source : https://www.kaggle.com/datasets/adrianmcmahon/imdb-india-movies/data

Feel free to explore the notebook for detailed analysis and code implementation.
