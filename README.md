# Data Science Consulting Projects
This repository contains my independent data science projects focusing on solving real-world business problems using data-driven solutions.

## 🎯 Current Project: Modern Spam Detection
This project aims to develop an advanced spam detection system that addresses the evolving nature of unwanted communications. Traditional binary spam classification is becoming inadequate as spam tactics grow more sophisticated, operating in "gray areas" that challenge conventional filters.

### Motivation
Motivated by personal experiences with subtle spam across various platforms (messaging apps, YouTube comments), this project seeks to create a more nuanced detection system that can identify and filter sophisticated, ambiguous cases that current systems often miss.

### Industry Applications
- **Retail**: Customer communication quality, review authenticity detection
- **Finance**: Enhanced fraud detection, security communication
- **Manufacturing**: Supply chain communication security, B2B communication optimization

## 🛠 Tech Stack
### Core
- Python 3.9.13
- AWS Cloud Services
- Causal Inference Tools

### Python Libraries
- **Data Processing**: Pandas, NumPy
- **Machine Learning**: Scikit-learn
- **NLP**: NLTK, spaCy
- **Deep Learning**: TensorFlow/PyTorch
- **Data Visualization**: Matplotlib, Seaborn

### Cloud Infrastructure (Planned)
- AWS S3
- AWS SageMaker
- AWS Lambda

## 📊 Project Structure
```tree
/data-science-consulting-solutions
│
├── README.md                    # Project overview and basic information
├── LICENSE                       # License file for the project
├── requirements.txt              # Python package dependencies
├── vs_code_setup.md              # VS Code setup guide
├── notebooks/                    # Jupyter notebooks
│   ├── 01_exploratory_analysis/  # Exploratory data analysis
│   ├── 02_modeling/              # Model building and training
│   └── 03_evaluation/            # Model evaluation
├── src/                          # Source code
│   ├── data/                     # Data processing
│   ├── models/                   # ML models
│   └── utils/                    # Utility functions
├── tests/                        # Unit tests
└── docs/                         # Documentation
```

## 🎯 Current Focus
- Development of ML models for "gray area" spam detection
- Integration of causal inference for better understanding of spam patterns
- Cross-platform approach (messages, social media comments)
- MVP development with focus on user experience

## 🚧 Development Status
Initial Planning Phase:
- Setting up project infrastructure
- Documenting motivation and requirements
- Planning data collection strategy

## 📝 Setup Notes
- **Python environment setup**
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
pip freeze > requirements.txt
```
- **AWS configuration** [Coming soon]
- **Data collection guidelines** [Coming soon]

For detailed instructions on setting up your environment in VS Code, refer to the [`vs_code_setup.md`](vs_code_setup.md) guide.

## 📁 Dataset
- The dataset used for this project is the **UCI SMS Spam Collection Dataset**, which is publicly available on Kaggle.
- The dataset contains SMS messages labeled as **spam** or **ham**.
- For details on how to access and use the dataset, please refer to the [`src/data/README.md`](src/data/README.md) file.

## 📚 Documentation
- See [`docs/motivation.md`](docs/motivation.md) for detailed project background and vision.
- For API details, see [`docs/api_documentation.md`](docs/api_documentation.md).
- For system design details, see [`docs/design.md`](docs/design.md).
- For an explanation of the project structure, see [`docs/repository_structure.md`](docs/repository_structure.md).
---
*This project is part of my journey to become a data scientist who solves real-world problems through innovative data-driven solutions.*
