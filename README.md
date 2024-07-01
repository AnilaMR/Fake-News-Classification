# Fake-News-Classification

This project aims to classify news articles as real or fake using machine learning techniques. The dataset consists of news articles labeled as true or fake.

## Dataset

The dataset comprises two CSV files:
- `True.csv`: Contains real news articles.
- `Fake.csv`: Contains fake news articles.

Each file has the following columns:
- `title`: The title of the news article.
- `text`: The content of the news article.
- `subject`: The subject category of the news article.
- `date`: The publication date of the news article.

### Prerequisites

Make sure you have the following libraries installed:
- numpy
- pandas
- scikit-learn
- matplotlib
- seaborn

### Model

The model is trained using the following steps:

- Load and inspect the data.
- Preprocess the data (e.g., removing stopwords, stemming).
- Vectorize the text data using TF-IDF.
- Train a machine learning model (e.g., Logistic Regression, SVM).
- Evaluate the model's performance using metrics like accuracy, precision, recall, and F1-score.
