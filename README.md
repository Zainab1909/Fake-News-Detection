# Fake News Detection

This repository provides a project for detecting fake news using various machine learning techniques. The goal is to identify and classify news articles as either real or fake, helping to combat misinformation.

## Features

- Data preprocessing and cleaning for news datasets
- Feature extraction (text vectorization)
- Multiple classification algorithms (e.g., Logistic Regression, Naive Bayes, SVM)
- Model evaluation and comparison
- Visualization of results

## Getting Started

### Prerequisites

- Python 3.7+
- pip

### Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/Zainab1909/Fake-News-Detection.git
   cd Fake-News-Detection
   ```

2. Install the required Python packages:
   ```bash
   pip install -r requirements.txt
   ```

### Usage

1. Prepare your dataset (CSV files containing news texts and labels).
2. Run the main script or notebook to train and evaluate the models:
   ```bash
   python main.py
   ```
   Or open and execute the Jupyter notebook:
   ```bash
   jupyter notebook FakeNewsDetection.ipynb
   ```

3. Review the output for model performance metrics and predictions.

## Project Structure

```
.
├── data/              # Datasets (train/test CSV files)
├── src/               # Source code (preprocessing, models, utils)
├── notebooks/         # Jupyter notebooks for experiments
├── requirements.txt   # Required Python packages
├── main.py            # Main script for running the pipeline
└── README.md          # Project documentation
```

## Models Used

- Logistic Regression
- Naive Bayes
- Support Vector Machines (SVM)
- Random Forest (optional)

## Evaluation Metrics

- Accuracy
- Precision, Recall, F1-Score
- Confusion Matrix
