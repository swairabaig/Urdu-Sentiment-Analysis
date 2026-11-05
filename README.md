
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


## Model Performance

The Logistic Regression model was evaluated on 5,210 test samples.

### Overall Evaluation Results

| Metric | Score |
|---|---:|
| Accuracy | 89.27% |
| Weighted Precision | 89.47% |
| Weighted Recall | 89.27% |
| Weighted F1-Score | 89.28% |

### Classification Report

| Sentiment | Precision | Recall | F1-Score | Support |
| Positive | 0.86 | 0.92 | 0.89 | 1557 |
| Negative | 0.87 | 0.91 | 0.89 | 1509 |
| Neutral | 0.93 | 0.86 | 0.90 | 2144 |

### Model Evaluation Summary

- The model achieved 89.27% overall accuracy.
- Positive sentiment achieved 0.89 F1-score.
- Negative sentiment achieved 0.89 F1-score.
- Neutral sentiment achieved 0.90 F1-score.
- The model was evaluated using accuracy, precision, recall, F1-score, and a confusion matrix.

These results demonstrate the model's ability to classify Urdu text into positive, negative, and neutral sentiment categories.


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
