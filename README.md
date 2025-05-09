# Machine-learning---Classification

Ce projet est réalisé dans le cadre du TP2 du cours **Machine Learning** (SIA3611, S7) à l'ENSEA. Il s'intéresse à des techniques de **classification supervisée** appliquées à des données réelles de l'OMS. L'objectif est d'entraîner plusieurs modèles et de comparer leur capacité à séparer les pays développés des pays en développement en 2000.

## 🎯 Objectifs pédagogiques

- Visualiser un espace de caractéristiques (feature space)
- Normaliser un jeu de données
- Entraîner et évaluer différents modèles de classification :
  - K-Nearest Neighbors (KNN)
  - Arbre de décision
  - Forêt aléatoire (Random Forest)
  - SVM (Support Vector Machine)
- Tracer les frontières de décision
- Ajuster les hyperparamètres et corriger les biais de classes
- Tester la robustesse des modèles avec des données d’une autre année (2012)

## 🗂 Jeu de données

Les données proviennent de l’**Organisation Mondiale de la Santé** et couvrent l’évolution de 20 caractéristiques pour différents pays entre 2000 et 2015. Le fichier `Life_Expectancy_Data.csv` est utilisé, comme dans le TP1.

## 🧰 Librairies utilisées

- `pandas`
- `numpy`
- `matplotlib`
- `scikit-learn`

## ▶️ Exécution

1. Ouvrir le notebook Jupyter :
```bash
jupyter notebook TP2_Classification.ipynb
