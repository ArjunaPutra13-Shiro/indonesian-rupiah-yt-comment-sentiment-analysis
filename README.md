# Indonesian Rupiah Youtube Comment Sentiment Analysis

This project analyzes public sentiment toward the depreciation of the Indonesian Rupiah using comments collected from YouTube. The study applies Natural Language Processing (NLP) techniques and sentiment classification models to understand how the public reacts to changes in the Rupiah exchange rate and related economic issues.

The project compares traditional machine learning approaches with transformer-based deep learning models to evaluate their effectiveness in Indonesian sentiment analysis tasks.

---

## Key Features

- Indonesian-language sentiment analysis
- YouTube comment data collection and processing
- Manual sentiment labeling
- Comprehensive NLP preprocessing pipeline
- Comparative analysis of Logistic Regression, SVM, and IndoBERT
- Exploratory Data Analysis (EDA)
- Model performance evaluation and comparison

---

## Project Objectives

The main objectives of this project are:

- Analyze public opinion regarding the weakening Indonesian Rupiah.
- Build sentiment classification models for Indonesian text.
- Compare the performance of traditional machine learning models and transformer-based models.
- Identify the most effective approach for Indonesian sentiment classification.

---

## Dataset

The dataset consists of Indonesian-language comments collected from YouTube videos discussing:

- Rupiah depreciation
- Exchange rate fluctuations
- Indonesian economy
- Government economic policies
- Public financial concerns

Each comment was manually labeled into one of three sentiment categories:

| Label | Sentiment |
|---------|-----------|
| 0 | Negative |
| 1 | Neutral |
| 2 | Positive |

Manual labeling was conducted to improve data quality and ensure contextual understanding of sentiment expressions in Indonesian.

---

## Methodology

### 1. Data Collection

Data was collected from YouTube comments related to discussions about the Indonesian Rupiah and economic conditions.

### 2. Data Preprocessing

The preprocessing pipeline includes:

- Case Folding
- Text Cleaning
- URL Removal
- Mention Removal
- Number Removal
- Punctuation Removal
- Tokenization
- Stopword Removal
- Text Normalization
- Stemming

These steps help improve text quality and reduce noise before model training.

### 3. Exploratory Data Analysis (EDA)

EDA was conducted to examine:

- Sentiment distribution
- Word frequency
- Comment length distribution
- Most frequent terms
- Class balance

---

## Models

This project evaluates three different classification approaches.

### Logistic Regression (LR)

A traditional machine learning algorithm commonly used for text classification tasks due to its simplicity and strong baseline performance.

### Support Vector Machine (SVM)

A powerful supervised learning model known for its effectiveness in high-dimensional text classification problems.

### IndoBERT

A transformer-based language model specifically pretrained on Indonesian-language corpora.

Advantages of IndoBERT:

- Context-aware understanding
- Better semantic representation
- Improved handling of Indonesian language nuances
- Strong performance on NLP tasks

---

## Evaluation Metrics

Model performance is evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

These metrics provide a comprehensive assessment of classification quality across sentiment classes.

---

## Technology Stack

### Programming Language

- Python

### Data Processing

- Pandas
- NumPy

### Natural Language Processing

- NLTK
- Sastrawi

### Machine Learning

- Scikit-learn

### Deep Learning

- PyTorch
- Hugging Face Transformers

### Visualization

- Matplotlib
- Seaborn

---

## Project Structure

```text
rupiah-sentiment-analysis/
│
├── dataset/
│   ├── label/
│
├── notebook/
│
├── results/
│
├── README.md
```

---

## Workflow

```text
YouTube Comments
        │
        ▼
Data Cleaning
        │
        ▼
Manual Labeling
        │
        ▼
Text Preprocessing
        │
        ▼
Feature Extraction
        │
        ▼
 ┌─────────────┬─────────────┬─────────────┐
 │     LR      │     SVM     │  IndoBERT   │
 └─────────────┴─────────────┴─────────────┘
        │
        ▼
Model Evaluation
        │
        ▼
Performance Comparison
```

---

## Results

The project compares the performance of:

- Logistic Regression
- Support Vector Machine
- IndoBERT

The results provide insights into how traditional machine learning methods compare with transformer-based architectures for Indonesian sentiment analysis in the context of economic discussions.

---

## Future Improvements

Potential future developments include:

- Expanding the dataset size
- Collecting data from multiple social media platforms
- Hyperparameter optimization
- Aspect-Based Sentiment Analysis (ABSA)
- Real-time sentiment monitoring dashboard
- Comparison with other Indonesian transformer models
- Topic modeling integration

---

## Applications

This project can be useful for:

- Economic sentiment monitoring
- Public opinion analysis
- Financial market research
- Social media analytics
- Indonesian NLP research
- Academic research and coursework

---

## Author

**Arjuna Putra**

Undergraduate Physics Student

---

## License

This project is intended for educational and research purposes.
