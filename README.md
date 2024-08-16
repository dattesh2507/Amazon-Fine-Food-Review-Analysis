# Amazon-Fine-Food-Review-Analysis

# Amazon_Food_Reviews
In this repository, I am practiced and implemented  machine learning algorithm(**SVM**) using the real-world dataset amazon food reviews from Kaggle.

![Amazon_Food_Reviews](https://miro.medium.com/max/523/1*bXDiOoCFTSJJdTQ7JbuijQ.png)


### First We want to know What is Amazon Fine Food Review Analysis?
This dataset consists of reviews of fine foods from amazon. The data span a period of more than 10 years, including all ~500,000 reviews up to October 2012. Reviews include product and user information, ratings, and a plaintext review. We also have reviews from all other Amazon categories.

Amazon reviews are often the most publicly visible reviews of consumer products. As a frequent Amazon user, I was interested in examining the structure of a large database of Amazon reviews and visualizing this information so as to be a smarter consumer and reviewer.

Source: https://www.kaggle.com/snap/amazon-fine-food-reviews

### Introduction

The Amazon Fine Food Reviews dataset consists of reviews of fine foods from Amazon.

1. Number of reviews: 568,454
2. Number of users: 256,059
3. Number of products: 74,258
4. Timespan: Oct 1999 — Oct 2012
5. Number of Attributes/Columns in data: 10

### Attribute Information:
1. Id
2. ProductId — unique identifier for the product
3. UserId — unqiue identifier for the user
4. ProfileName
5. Helpfulness Numerator — number of users who found the review helpful
6. HelpfullnessDenominator — number of users who indicated whether they found the review helpful or not
7. Score — rating between 1 and 5
8. Time — timestamp for the review
9. Summary — brief summary of the review
10. Text — text of the review

## Objective
The main objective of this project is to build a machine learning model that can accurately classify customer sentiment using Natural Language Processing techniques. The best classifier will be selected based on metrics such as F1-score and accuracy.

## Methodology
**Data Collection & Cleaning:**
The dataset is loaded and cleaned to remove irrelevant, duplicated, or improperly formatted data.

**Text Preprocessing:**

Tokenization: Splitting the review text into individual words.
Stop Words Removal: Removing common words that do not carry significant meaning.
TF-IDF Vectorization: Converting text into numerical features using the Term Frequency-Inverse Document Frequency method.
Exploratory Data Analysis (EDA):

Distribution of ratings across reviews.
Visualization of common words in positive and negative reviews using word clouds.

**Model Training:**
The dataset is split into training and test sets (70:30 ratio). Several models are trained including:
Support Vector Machine (SVM)

**Model Evaluation:**
Performance is measured using metrics like accuracy, precision, recall, and F1-score. Confusion matrices are used to analyze the performance further.

**Exploratory Data Analysis**
Key insights from the dataset include:

Imbalance: A large proportion (64%) of the reviews are 5-star ratings.
Skewed Distribution: The majority of reviews are positive, which skews the dataset.
Visualizations, including word clouds, are used to highlight common words in positive and negative reviews.

**Modeling**
The models used in this analysis include:
Support Vector Machine (SVM)
The text data is converted into vectors using TF-IDF Vectorizer, and models are trained to classify the sentiment of the reviews.

**Results**
Accuracy: The best performing model achieved an accuracy of 67% .
The SVM classifier performed best in this case, based on a combination of accuracy, precision, recall, and F1-score.

**Conclusion**
This project demonstrates the use of sentiment analysis to classify reviews as positive, neutral, or negative using NLP and machine learning techniques. Business insights derived from this analysis can help companies like Amazon to improve customer satisfaction by understanding their feedback more effectively.

**Key Takeaways:**
The dataset is highly imbalanced, with a skew towards positive reviews.
Sentiment analysis is an effective tool for gauging customer opinions.
