# Political Predictive Model

Welcome to the "Political Predictive Model" project! This project aims to build a machine-learning model that can accurately predict the winning political party based on USA citizens' donations. This README file provides an overview of the project, including its purpose, the data used, the methodology employed, and instructions on how to set up and run the project.

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
- [Data](#Data)
- [Results](#Results)
- [Contributors](#Contributors)

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

# Data

The data used in this project is sourced from publicly available records of political donations in the USA. This dataset includes information such as donor donation amounts, dates, and the political parties or candidates receiving the donations. We have meticulously cleaned and preprocessed the data to ensure its suitability for training our machine-learning model

- [Current and historic federal campaign finance data](https://www.fec.gov/data/receipts/individual-contributions/)
- [Cost of Living & Disposable Incomes by State](https://www.forbes.com/advisor/mortgages/cost-of-living-by-state/)

---

# Results

The results of our machine learning model reults as follow:

- There is no particular Correlation between the economical situation of the state and the amount of Individual Contributions
- The Individual Contributions are not a good feature to consider when predicting the outcome of elections
---

# Contributors

This project was created and developed by:

- Cesar Fernandez
- Connor Finnerty
- Manuel Flores
