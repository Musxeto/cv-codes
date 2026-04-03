# Computer Vision & Deep Learning Tutorials

This repository contains beginner-friendly Jupyter Notebooks covering traditional computer vision and deep learning techniques using OpenCV, PyTorch, and TensorFlow.

## Setup Instructions (Windows)

Follow these steps to set up the environment and run the notebooks on your Windows machine.

### 1. Prerequisites
Ensure you have [Python](https://www.python.org/downloads/) installed on your system. During installation, make sure to check the box that says **"Add Python to PATH"**.

### 2. Open Command Prompt or PowerShell
Navigate to the root directory of this project where the files are located:
```cmd
cd path\to\cv-codes
```

### 3. Create a Virtual Environment
It is highly recommended to use a virtual environment to keep dependencies isolated:
```cmd
python -m venv venv
```

### 4. Activate the Virtual Environment
To activate the virtual environment on Windows, run:
```cmd
venv\Scripts\activate
```
*(Once activated, you should see `(venv)` appear at the beginning of your command prompt line).*

> **Note for PowerShell users:** If you get an *Execution Policy* or *cannot be loaded because running scripts is disabled* error, you may need to temporarily allow scripts by running this command first:
> `Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope CurrentUser`

### 5. Install Dependencies
With the virtual environment activated, install the required packages using the provided `requirements.txt` file:
```cmd
pip install -r requirements.txt
```
*Note: PyTorch and TensorFlow will automatically download the necessary MNIST dataset files the first time you run their respective code cells.*

### 6. Start Jupyter Notebook
To view and run the code, start the Jupyter Notebook server:
```cmd
jupyter notebook
```
This command will open a new tab in your default web browser showing the project files. From there, you can click on any of the `.ipynb` files (`opencv_tutorial.ipynb`, `pytorch_tutorial.ipynb`, or `tensorflow_tutorial.ipynb`) to open them, read the explanations, and execute the cells step-by-step.
