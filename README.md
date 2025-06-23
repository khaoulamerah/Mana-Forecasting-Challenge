
# Mana Forecasting Challenge: Rise of the Analysts

## Description
This repository contains my solution to the **Mana Forecasting Challenge**, an AI competition task from Gate 4. The goal is to predict the future mana demand ("mana_demand") for cities using a dataset with various features like weather conditions, number of open gates, hunter teams, and more. The model is evaluated using the Mean Squared Error (MSE).

In this imaginary world, mana powers cities and protects them from dungeon outbreaks. I use machine learning to forecast mana demand and help stabilize the mana infrastructure.

## Project Structure
.
├── Data/
│ ├── forcast_train_data.csv
│ ├── forcast_test_data.csv
│ ├── X_train_processed.csv
│ └── X_test_processed.csv
├── Modele/
│ └── model_linear_regression.pkl
├── predictions.csv
├── train_model.py
├── evaluate_model.py
└── README.md


## 🧪 Fonctionnalités principales

- Traitement et nettoyage des données (`fillna`, encodage One-Hot de `city`)
- Normalisation des variables numériques avec `StandardScaler`
- Entraînement d’un modèle de **régression linéaire**
- Sauvegarde du modèle avec `joblib`
- Prédiction de la demande sur des données de test
- Évaluation du modèle avec l’erreur quadratique moyenne (MSE)

## ⚙️ Dépendances

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







