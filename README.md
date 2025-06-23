
# Mana Forecasting Challenge: Rise of the Analysts

## Description
This repository contains my solution to the **Mana Forecasting Challenge**, an AI competition task from Gate 4. The goal is to predict the future mana demand ("mana_demand") for cities using a dataset with various features like weather conditions, number of open gates, hunter teams, and more. The model is evaluated using the Mean Squared Error (MSE).

In this imaginary world, mana powers cities and protects them from dungeon outbreaks. As a data sorcerer, I use machine learning to forecast mana demand and help stabilize the mana infrastructure.

## Project Structure
- `forcast_train_data.csv`: Dataset used to train the model (contains "mana_demand" values).
- `forcast_test_data.csv`: Dataset used to predict "mana_demand" (no target values).
- `predictions.csv`: File with predicted "mana_demand" values for the test dataset.
- `step1_explore_data.py`: Script to explore and understand the dataset.
- `step2_prepare_data.py`: Script to clean and preprocess the data.
- `step2_visualize_data.py`: Script to create visualizations of the data.
- `step3_train_model.py`: Script to train the linear regression model.
- `step4_predict.py`: Script to make predictions on the test data.
- `step4_visualize_predictions.py`: Script to visualize predictions vs. true values.
- `step5_evaluate.py`: Script to evaluate the model using MSE (optional).
- `model_linear_regression.pkl`: Saved trained model (optional).
- `README.md`: This file!

## Requirements
To run this project, you need the following Python libraries:
- `pandas`
- `scikit-learn`
- `matplotlib`
- `seaborn`
- `joblib`

Install them using:
```bash
pip install pandas scikit-learn matplotlib seaborn joblib
```:disable-run

## How to Run
Follow these steps to replicate my work:

1. **Clone the repository:**

   git clone https://github.com/votre-username/mana-forecasting-challenge.git
   cd mana-forecasting-challenge
   ```:disable-run

2. **Explore the data:**
   Run the exploration script to see the dataset:

   python step1_explore_data.py
   ```:disable-run

3. **Prepare the data:**
   Preprocess the data (cleaning, encoding, normalization):

   python step2_prepare_data.py
   ```:disable-run

4. **Visualize the data:**
   Generate plots to understand trends:

   python step2_visualize_data.py
   ```:disable-run

5. **Train the model:**
   Train a linear regression model:

