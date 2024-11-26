# Repository Structure

The structure of this project is as follows:

```tree
/data-science-consulting-solutions          # Root directory of the project
│
├── README.md                             # Project overview and basic information
├── LICENSE                                # License file for the project
├── requirements.txt                       # Python package dependencies
├── vs_code_setup.md                       # VS Code setup guide
├── notebooks/                             # Jupyter notebooks for project development
│   ├── 01_exploratory_analysis/           # Exploratory data analysis (EDA)
│   │   └── 01_spam_data_exploration.ipynb # Spam data exploration notebook
│   ├── 02_modeling/                      # Model building and training
│   │   └── 01_baseline_model.ipynb       # Baseline model notebook
│   └── 03_evaluation/                    # Model evaluation
├── src/                                   # Source code for the project
│   ├── data/                              # Data processing and manipulation
│   │   ├── README.md                      # Explanation of the data processing and structure
│   ├── models/                            # Machine learning models and algorithms
│   ├── utils/                             # Utility functions (e.g., data loaders, helpers)
│   │   ├── __init__.py                    # Initialization file for utils module
│   │   ├── data_loader.py                 # Data loading utility script
│   │   └── preprocessor.py                # Preprocessing utility script
├── tests/                                 # Unit tests for validating the project
└── docs/                                  # Documentation related to the project
    ├── motivation.md                      # Detailed project motivation and background
    ├── design.md                          # System design decisions and architecture
    ├── repository_structure.md            # Explanation of the project structure
    └── api_documentation.md               # API documentation (if applicable)
```
