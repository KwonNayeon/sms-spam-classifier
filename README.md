# Data Science Consulting Projects
This repository contains my independent data science projects focusing on solving real-world business problems using data-driven solutions.

## 🎯 Current Project: SMS Spam Detection
This project aims to develop a spam detection system using machine learning techniques. Currently focusing on building and improving baseline models for binary classification of SMS messages.

### Motivation
The project starts with traditional binary spam classification to establish strong baseline models before moving on to more sophisticated approaches. This systematic approach will help understand core spam detection challenges and establish reliable evaluation metrics.

## 🛠 Tech Stack
### Current
- Python 3.9.13
- **Data Processing**: Pandas, NumPy
- **Machine Learning**: Scikit-learn
- **NLP**: NLTK
- **Data Visualization**: Matplotlib, Seaborn

## 📊 Project Structure
```tree
/data-science-consulting-solutions
│
├── README.md                    # Project overview and basic information
├── LICENSE                      # License file for the project
├── requirements.txt             # Python package dependencies
├── vs_code_setup.md            # VS Code setup guide
├── notebooks/                   # Jupyter notebooks
│   ├── 01_exploratory_analysis/# Exploratory data analysis
│   ├── 02_modeling/            # Model building and training
│   └── 03_evaluation/          # Model evaluation
├── src/                        # Source code
│   ├── data/                   # Data processing
│   ├── models/                 # ML models
│   └── utils/                  # Utility functions
├── tests/                      # Unit tests
└── docs/                       # Documentation
```

## 🚧 Current Progress
- Implemented initial baseline models (Logistic Regression, Random Forest)
- Basic text preprocessing and feature extraction
- Initial model evaluation completed

## 📝 Next Steps
- Improve model performance by addressing class imbalance
- Enhance text preprocessing techniques
- Implement feature engineering
- Document findings and insights

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
