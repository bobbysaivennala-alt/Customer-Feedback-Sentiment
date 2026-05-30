# Customer Feedback Sentiment Analysis
__________________________________________
**Intern Details**
Intern ID: **CITS787**
GitHub Username: **bobbysaivennala**

## Project Overview
Customer Feedback Sentiment Analysis is a Data Analytics and NLP project developed using Python. The purpose of this project is to analyze customer reviews and classify them into Positive or Negative sentiments. This helps businesses understand customer opinions and improve products or services.

---

## Project Objective
The main objectives of this project are:

- Analyze customer feedback data
- Clean and preprocess text data
- Convert text into numerical features
- Train a machine learning model
- Predict customer sentiment
- Visualize sentiment analysis results

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- NLP (TF-IDF Vectorization)

---

## Project Structure

```bash
Customer-Feedback-Sentiment-Analysis/
│
├── customer_feedback.csv
├── sentiment_analysis.ipynb
├── README.md
└── requirements.txt
```

---

## Dataset Information

The dataset contains customer review text and sentiment labels.

### Dataset Columns

| Column Name | Description |
|-------------|-------------|
| Review | Customer feedback text |
| Sentiment | Positive or Negative |

Example:

| Review | Sentiment |
|----------|------------|
| Product quality is excellent | Positive |
| Delivery was very slow | Negative |
| Amazing customer support | Positive |

---

## Data Preprocessing Steps

The following preprocessing techniques are applied:

1. Remove missing values
2. Remove duplicate records
3. Separate input and output variables
4. Convert text into numerical form using TF-IDF

---

## Machine Learning Model

Model used:

**Multinomial Naive Bayes**

Steps:

- Split dataset into training and testing data
- Train the model
- Predict sentiment values
- Evaluate model performance

---

## Data Visualization

The project includes:

- Confusion Matrix
- Sentiment Distribution Chart

---

## Model Evaluation Metrics

Performance is evaluated using:

- Accuracy Score
- Classification Report
- Confusion Matrix

---

## Installation

Install required libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

---

## Run the Project

Open Jupyter Notebook and run:

```bash
jupyter notebook
```

Load dataset:

```python
df = pd.read_csv("customer_feedback.csv")
```

Run all notebook cells.

---

## Expected Output

- Customer review sentiment prediction
- Positive and Negative classification
- Visual analysis of customer feedback

---

## Future Improvements

- Add Neutral sentiment category
- Use larger real-world datasets
- Deploy using Streamlit
- Improve model accuracy using Deep Learning
