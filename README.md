# Classification du diabète avec un réseau de neurones

Ce projet implémente un réseau de neurones simple (MLP) en Python avec NumPy pour prédire le diabète à partir du jeu de données Pima Indians Diabetes.

## Objectif

Prédire si un patient est atteint de diabète en fonction de ses caractéristiques médicales. Le réseau est construit et entraîné sans utiliser de bibliothèques de deep learning comme TensorFlow ou PyTorch.

## Fichiers

- `neural_network.py` : classe du modèle MLP avec l'optimiseur Adam  
- `train.py` : code pour charger les données, entraîner et évaluer le modèle  
- `diabetes.csv` : données utilisées  
- `README.md` : ce fichier

## Fonctionnalités

- Implémentation manuelle du MLP
- Optimiseur Adam
- Métriques : accuracy, F1-score, matrice de confusion
- Courbes de perte et de précision

## Exécution

```bash
pip install -r requirements.txt
python train.py
