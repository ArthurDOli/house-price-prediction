# House Price Prediction

This repository contains the code for a Machine Learning project that predicts
house sale prices based on the "[House Prices - Advanced Regression Techniques](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques/overview)" dataset from Kaggle.

## Overview

This repository contains notebooks used to explore, preprocess, model, and submit predictions for the Kaggle competition. The final submission currently ranks among the **top 10%~15%** best results in the competition.

## Repository Structure

- `house_price_prediction.ipynb`: "Lab" Notebook - Contains the entire exploration process and the _slow_ hyperparameter search using Cross-Validation (`cv=5`). **Output:** Best CV score and best parameters.
- `house_price_prediction_submission.ipynb`: "Production" Notebook - **Clean and fast** code that uses the best parameters found in the lab notebook to train the final model and generate the submission file.

## Installation and Setup

Follow the steps below to set up and run the project locally:

1.  **Clone the repository:**

    ```bash
    git clone https://github.com/ArthurDOli/house-price-prediction.git
    cd house-price-prediction
    ```

2.  **Create and activate a virtual environment:**

    ```bash
    python -m venv venv
    # On Windows
    venv\Scripts\activate
    # On macOS/Linux
    source venv/bin/activate
    ```

3.  **Install the dependencies:**

    ```bash
    pip install -r requirements.txt
    ```

4.  **Access the data:**
    To access the data, download it from the [official competition website](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques/data).
