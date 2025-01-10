# Rotten-Tomatoes---Audience-Rating-prediction
Audience Rating Prediction for Rotten Tomatoes

Table of Contents

Overview

Features

Dataset

Installation

Usage

File Descriptions

Model Architecture

Results

Contributing

License

Overview

This project aims to predict audience ratings for movies on Rotten Tomatoes using machine learning techniques. By analyzing movie metadata, reviews, and other relevant features, the model can provide insights into how audiences might perceive a movie.

Features

Predict audience ratings based on:

Movie metadata (e.g., genre, release year, runtime)

Review sentiments (critic and audience)

Cast and crew information

Preprocessing pipeline for text and numerical data.

Model performance evaluation with metrics such as Mean Absolute Error (MAE) and Root Mean Squared Error (RMSE).

Dataset

The dataset includes:

Movie metadata: Information such as title, genre, runtime, release year.

Audience reviews: User-generated reviews with text and ratings.

Critic reviews: Professional critic ratings and sentiments.

Data can be collected from  Kaggle.

Note: Ensure you comply with data usage policies and licensing terms when sourcing datasets.

Installation

Clone this repository:

git clone https://github.com/yaswanthreddy3/Rotten-Tomatoes---Audience-Rating-prediction.git
cd audience-rating-prediction

Install the required dependencies:

pip install -r requirements.txt

Set up the dataset by placing it in the data/ directory. Update the config.json file with the dataset path.

Usage

P
README.md: Project documentation.

Top_5_Ratings.png: Visualization showing the top 5 ratings or related metrics.

cleaned_df.pkl: Pickled file containing the cleaned dataset.

df.pkl: Pickled file containing the raw or intermediate dataset.

eda.ipynb: Jupyter notebook for Exploratory Data Analysis (EDA).

feature engineering.ipynb: Notebook for engineering features from the dataset.

model_training.ipynb: Notebook for training and evaluating machine learning models.

target.pkl: Pickled file containing the target variable for prediction.

Model Architecture

The model architecture includes:

Feature Engineering: Combining numerical, categorical, and text features.

Text Analysis: Sentiment extraction using pre-trained models (e.g., BERT, TF-IDF).

Machine Learning Models: Algorithms like Random Forest, Gradient Boosting
Results


Note: Results may vary based on the dataset and preprocessing steps.

Contributing

Contributions are welcome! To contribute:

Fork the repository.

Create a feature branch:

git checkout -b feature-name

Commit your changes and push the branch:

git commit -m "Add new feature"
git push origin feature-name

Open a pull request.

License

This project is licensed under the MIT License.

Feel free to report issues or request new features by opening an issue in the repository!

