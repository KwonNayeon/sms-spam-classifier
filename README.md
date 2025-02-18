# SMS Spam Detection Project

Part of my data science portfolio - Building a machine learning system for binary classification of SMS messages.

## Project Overview
Developing a spam detection system using ML techniques, currently focusing on establishing strong baseline models and evaluation metrics.

### Motivation
This project builds on prior work in text analysis (e.g., [Word Cloud Visualization](https://nayeonkwonds.medium.com/deep-dive-into-word-cloud-creation-c2fc7fc09c12), [Travel Blog Analysis](https://nayeonkwonds.medium.com/web-scraping-and-text-analysis-of-travel-trends-on-blogs-e83a453d34ed)) and classification (e.g., [SME Closure Prediction](https://github.com/KwonNayeon/numble)). It establishes a solid foundation before diving into more sophisticated techniques, starting with strong baseline models and robust evaluation metrics to develop a deep understanding of the core challenges in classification.

## 🛠 Tech Stack
### Current
- Python 3.9.13
- **Data Processing**: Pandas, NumPy
- **Machine Learning**: Scikit-learn
- **NLP**: NLTK, WordCloud
- **Data Visualization**: Matplotlib, Seaborn

## 📊 Project Structure
```tree
/sms-spam-classifier
│
├── README.md                        # Project overview and documentation
├── LICENSE                          # Project license file
├── requirements.txt                 # Python dependencies
├── vs_code_setup.md                # VS Code configuration guide
├── notebooks/                       # Jupyter notebooks for analysis
├── src/                            # Source code directory
│   ├── data/                       # Data storage and processing
│   ├── models/                     # Machine learning models
│   └── utils/                      # Utility functions and helpers
├── tests/                          # Unit tests
└── docs/                           # Project documentation
```

## 🚧 Current Progress
- Implemented initial baseline models using different approaches:
  - Count Vectorizer + Logistic Regression
  - TF-IDF + Random Forest
- Conducted comprehensive EDA including:
  - Text complexity analysis
  - Word patterns visualization
  - Sentence structure analysis
- Basic text preprocessing and model evaluation completed

## 📝 Next Steps
1. Model Performance Improvement
2. Code Structure Enhancement
3. EDA Expansion

## 📁 Dataset
- Using the UCI SMS Spam Collection Dataset from Kaggle
- Binary classification: spam vs ham (non-spam) messages

## 🔧 Setup
1. Create virtual environment
```bash
python -m venv spam_detector_env
```
2. Activate virtual environment
```bash
# Windows
spam_detector_env\Scripts\activate
# Mac/Linux
source spam_detector_env/bin/activate
```
3. Install dependencies
```bash
pip install numpy pandas scikit-learn jupyter
```

---
*This project is part of my journey to become a data scientist who solves real-world problems through data-driven solutions.*
