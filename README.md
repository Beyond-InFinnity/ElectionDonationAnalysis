# Project Title

Welcome to the ___ project! This project aims to build a machine-learning model that can accurately predict ____. This README file provides an overview of the project, including its purpose, the data used, the methodology employed, and instructions on how to set up and run the project.

The main objectives of this project are to:

- Explore and preprocess the data
- Perform exploratory data analysis (EDA).
- Build and evaluate multiple machine learning models to select the best-performing one.
- Interpret the results and provide conclusions based on the findings.
- This project is a collaborative effort by our team of data scientists, and we hope it will serve as a valuable resource for anyone interested in political analytics and predictive modeling.

---

# Table of Contents

- [Introduction](#Introduction)
- [Installation](#Installation)
- [Usage](#Usage)
- [Project Structure](#Project-Structure)
- [Data](#Data)
- [Results](#Results)
- [Contributors](#Contributors)
- [References](#References)
- [Apendix](#Apendix)

---

# Introduction

Here is the full intro to the project

---

# Installation

The necessary libraries for this project are stored in the `requirements.txt` file

To install and run this project locally, follow these steps:

1. Fork the repository(Optional for committing changes):
    - On the top-right section of the Repository's page, click the `fork` button and choose the account you want to have the repository on
2. Clone the repository
    - Copy your `HTTPS`, `SSH` or `GitHub CLI` link
    - In GitBash(preferably) type: `git clone <your-link>`
3. Create and start a virtual environment (replace `<my-env>` with a custom name):
    - With Python:
        - Create: `python -m venv <my-env>`
        - Start on Windows: `myenv\Scripts\activate`
        - Start on macOS/Linux: `source myenv/bin/activate`
    - With Conda:
        - Create: `conda create --name <my-env>`
        - Start: `conda activate <my-env>` 
5. Install the requirements:
   - `pip install -r requirements.txt`

---

# Usage

To Use this model with your custom data:

`python main.py --input data/input.csv --output output/predictions.csv`


---

# Project Structure

```
project/
├── data/
├── notebooks/
├── output/
├── README.md
├── requirements.txt
└── main.py

```

---

# Data

The data used for the project is the following:

- [Current and historic federal campaign finance data](https://www.fec.gov/data/receipts/individual-contributions/?two_year_transaction_period=2024&min_date=01%2F01%2F2023&max_date=12%2F31%2F2024)
- 

---

# Results

The results of our machine learning model reults as follow:

---

# Contributors

This project was created and developed by:

- Cesar Fernandez
- Connor Finnerty
- Manuel Flores

---

# References

- 

---

# Apendix

The following is supplementary data to this project: 

- 