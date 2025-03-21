# TP_IA2

# Maintenance prédictive avec LSTM

Ce projet vise à prédire l'état d'une pompe industrielle en utilisant un modèle de réseau de neurones à mémoire à long terme (LSTM). L'objectif est de prédire l'état de la pompe (fonctionnement normal ou panne) en se basant sur les données temporelles collectées par des capteurs.

## Structure du projet

- **`app.py`** : API Flask pour effectuer des prédictions.
- **`lstm_model.h5`** : Modèle LSTM entraîné.
- **`random_forest_model.pkl`** : Modèle Random Forest entraîné.
- **`maintenance_predictive.csv`** : Dataset utilisé pour l'entraînement.
- **`README.md`** : Documentation du projet (ce fichier).

## Installation

1. Clonez ce repository :
   ```bash
   git clone https://github.com/mohamedafdailat/TP_IA2.git
   cd maintenance-predictive
