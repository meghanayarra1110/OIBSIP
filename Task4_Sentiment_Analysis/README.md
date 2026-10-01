**LEVEL 1 — TASK 4**

**SENTIMENT ANALYSIS**

**Project Overview**

This project focuses on performing sentiment analysis on a dataset containing text-based social media data. The objective is to preprocess textual data, extract meaningful features using TF-IDF, and develop machine-learning models to classify text into broad sentiment categories.

**Objective**

The main objectives of this project are:

- To inspect and understand the given sentiment dataset.
- To clean and preprocess the text data.
- To analyze the distribution of sentiment categories.
- To transform text into numerical features using TF-IDF.
- To train and evaluate two machine-learning classification models.
- To compare model performance using appropriate evaluation metrics.
- To perform error analysis on the model predictions.

### Dataset Overview

The dataset contains **732 records and 15 columns**. Important columns include:

- `Text` — the original text data.
- `Sentiment` — the original detailed sentiment/emotion label.
- `Timestamp` — timestamp associated with the text.
- `Platform` — platform information.
- `Hashtags` — hashtags associated with the text.
- `Retweets` — number of retweets.
- `Likes` — number of likes.
- `Country` — country information.

The original sentiment column contained a large number of detailed emotion labels. After removing unnecessary whitespace, **191 distinct sentiment labels** were identified.

For practical classification, the detailed sentiment labels were grouped into three broad categories:

- **Positive**
- **Neutral**
- **Negative**

The original detailed sentiment labels were preserved separately in `Sentiment_Original`.

### Tools and Technologies

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- TF-IDF
- Logistic Regression
- Multinomial Naive Bayes

### Project Workflow

**Data Loading → Data Inspection → Sentiment Analysis → Data Cleaning → Text Preprocessing → Train/Test Split → TF-IDF → Model Training → Model Evaluation → Model Comparison → Error Analysis → Conclusion**
