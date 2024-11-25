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
├── notebooks/          # Jupyter notebooks
│   ├── 01_exploratory_analysis/  # Exploratory data analysis
│   ├── 02_modeling/              # Model building and training
│   └── 03_evaluation/            # Model evaluation
├── src/               # Source code
│   ├── data/          # Data processing
│   ├── models/        # ML models
│   └── utils/         # Utility functions
├── tests/             # Unit tests
└── docs/              # Documentation
    ├── motivation.md  # Detailed project motivation
    └── design.md      # System design decisions
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

## VS Code Setup
1. Install recommended extensions
   - VS Code will automatically prompt you to install recommended extensions when you open the project
   - Alternatively, go to Extensions view (Ctrl+Shift+X) and search for "@recommended"

2. Select Python Interpreter
   - Press Ctrl+Shift+P
   - Type "Python: Select Interpreter"
   - Choose the interpreter from spam_detector_env

3. Setup Jupyter Notebook
   - Install ipykernel: `pip install ipykernel`
   - Select kernel from spam_detector_env when opening notebooks

4. Useful VS Code Shortcuts
   - Ctrl+Shift+P: Command Palette
   - F5: Start Debugging
   - Ctrl+Shift+`: New Terminal
   - Ctrl+Shift+M: Problems Panel
   - Ctrl+Shift+D: Debug Panel

## 📚 Documentation
See [`docs/motivation.md`](docs/motivation.md) for detailed project background and vision.

---
*This project is part of my journey to become a data scientist who solves real-world problems through innovative data-driven solutions.*
