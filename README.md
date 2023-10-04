# datafun-07-ml-predictive

By Solomon Stevens

[Github Repository](https://github.com/Stone-Snevets/datafun-07-ml-predictive)

Date: October 6,2023 

Focus: 

1. Work with Object Oriented Programming (OOP)

2. Use Linear Regression

3. Understand basics of Machine Learning

### Create and Activate Virtual Environment in VS Code
To **CREATE** a new virtual environment

1. Open a new terminal

-> Click "View" then "Terminal" or type Ctrl+`

2. Type the following into the terminal:
```shell
python -m venv .venv
```
If that doesn't work try replacing "python" with "python3" or "py"

3. Check if a new .venv folder was created

-> If so, you have successfully created a new virtual environment

To **ACTIVATE** this virtual environment

1. In the terminal, type the following depending on your operating system:

-> For PowerShell: `.venv\Scripts\Activate`

-> For macOS/Linux:  `source .venv/bin/`

### Install All Required External Dependencies

1. Type the following in the terminal:
```shell
python -m pip install --upgrade -r requirements.txt
```

This will install all the dependencies found in "requirements.txt" in this repository

### Execute Python Files

1. Create a python kernel for the virtual environment

-> In the terminal, type the following line:
```shell
python -m ipykernel install --user --name .venv --display-name "Python (.venv)"
```
-> Again, if you are having issues with this, try "python3" or "py" instead of "python"

2. In a Python Notebook (.ipynb)

A. Select the appropriate kernel... the one we just created

B. Run the Python Notebook

-> You can clear the kernel whenever you need by clicking "Restart" at the top of the page