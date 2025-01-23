# VS Code Setup Guide
This guide explains how to set up your development environment in VS Code.

## 1. Virtual Environment Setup
1. Create virtual environment (in project root directory):
   ```bash
   python -m venv spam_detector_env
   ```

2. Activate virtual environment:
   - Windows:
     ```bash
     spam_detector_env\Scripts\activate
     ```
   - Mac/Linux:
     ```bash
     source spam_detector_env/bin/activate
     ```

3. Install required packages:
   ```bash
   pip install -r requirements.txt
   ```

## 2. VS Code Interpreter Setup
1. Press `Ctrl+Shift+P` (Open Command Palette)
2. Type "Python: Select Interpreter"
3. Choose interpreter from `spam_detector_env`

## 3. Jupyter Notebook Setup
- Open notebook file (.ipynb)
- Select `spam_detector_env` kernel from the kernel picker in top right

## 4. Useful VS Code Shortcuts
- Ctrl+Shift+P: Command Palette
- Ctrl+Shift+`: New Terminal
- Ctrl+S: Save
