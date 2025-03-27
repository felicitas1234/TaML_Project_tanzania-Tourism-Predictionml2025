# Tanzania Tourism Prediction Project

## Project Overview

This project is a **Machine Learning (ML) model development** conducted during my Weiterbildung in **Data Science, Machine Learning, and AI**. The goal is to build a predictive model to estimate **tourist expenditure** when visiting Tanzania based on the provided dataset.

### Challenge Overview

The dataset consists of **6,476 rows** of data collected by the **National Bureau of Statistics (NBS) in Tanzania**. It aims to provide insights into the **status of the tourism sector** and serve as a tool for sector growth. The challenge is hosted on **Zindi Africa**: [Tanzania Tourism Prediction](https://zindi.africa/competitions/tanzania-tourism-prediction/data).


## Deliverables

1. Develop a **machine learning model** that accurately predicts **tourist expenditure**.
2. Perform **feature engineering and selection** to identify the most relevant predictors.
3. Evaluate the model using appropriate **metrics (e.g., RMSE, R², MAE)**.
4. Provide **at least three key insights** derived from the dataset.
5. Offer **at least three actionable recommendations** for stakeholders in the tourism sector.

## Project Documentation

- **Data Preprocessing & ML Model Development**: available as `tanzania-tourism-ml.ipynb`
- **Dataset description and feature explanations**: Located in the `documentation` folder.
- **Final presentation**: Available as a PDF in the repository.

# Setup

This repo contains a `requirements.txt` file with all necessary dependencies.

### **Prerequisites**

Before using **Plotly in Jupyter Lab**, ensure you have **Node.js** installed.

#### Check Node.js Version:

```sh
node -v
```

If Node.js is not installed, follow the steps below.

### Installation Instructions

#### **For macOS**

- **Step 1:** Update Homebrew and install Node.js
  ```sh
  brew update
  brew install node
  ```
- **Step 2:** Set up a virtual environment and install dependencies
  ```sh
  pyenv local 3.11.3
  python -m venv .venv
  source .venv/bin/activate
  pip install --upgrade pip
  pip install -r requirements.txt
  ```

#### **For Windows**

- **Step 1:** Update Chocolatey and install Node.js
  ```sh
  choco upgrade chocolatey
  choco install nodejs
  ```
- **Step 2:** Set up a virtual environment and install dependencies
  - **For PowerShell:**
    ```PowerShell
    pyenv local 3.11.3
    python -m venv .venv
    .venv\Scripts\Activate.ps1
    pip install --upgrade pip
    pip install -r requirements.txt
    ```
  - **For Git Bash:**
    ```sh
    pyenv local 3.11.3
    python -m venv .venv
    source .venv/Scripts/activate
    pip install --upgrade pip
    pip install -r requirements.txt
    ```

#### **Note:**

If you encounter errors running `pip install --upgrade pip`, try:

```sh
python.exe -m pip install --upgrade pip
```

---

## License

This project is for educational purposes as part of a Weiterbildung program in **Data Science, Machine Learning, and AI**.

---

**Author:** Felicitas Bartsch & Marina Moya Sánchez
**Date:** 27-January-2025

