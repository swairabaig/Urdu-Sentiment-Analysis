
# Urdu Sentiment Analysis Using Machine Learning

## Project Description

This project uses Natural Language Processing and Machine Learning to classify Urdu text into three sentiment categories:

- Positive
- Negative
- Neutral

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- TF-IDF
- Logistic Regression

## Dataset

The project uses an Urdu text classification dataset.

Dataset source:

https://huggingface.co/datasets/umar178/UrduMultiDomainClassification

The original dataset contains 34,819 records.

Records outside the three sentiment categories are excluded during preprocessing.

## Machine Learning Workflow

1. Dataset loading
2. Exploratory Data Analysis
3. Data cleaning
4. Text preprocessing
5. TF-IDF vectorization
6. Train-test splitting
7. Logistic Regression training
8. Model evaluation
9. Sentiment prediction
10. Model saving

## Evaluation Metrics

The model is evaluated using:

- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

Actual evaluation results are available in the project notebook.

## Installation

Clone the repository:

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

Open the project directory:

```bash
cd Urdu-Sentiment-Analysis
```

Create a virtual environment:

```bash
python -m venv .venv
```

Activate it on Windows CMD:

```bash
.venv\Scripts\activate.bat
```

Install the requirements:

```bash
pip install -r requirements.txt
```

Download the dataset from the source above and place it inside:

`data/urdu_sentiment.csv`

## Run the Project

Open the notebook:

`Urdu_Sentiment_Analysis.ipynb`

Run all cells in order.

## Author

BSCS Student | Aspiring AI/ML Engineer
