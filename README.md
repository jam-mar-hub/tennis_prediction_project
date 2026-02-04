# ATP Tennis Match Prediction 🎾

Ce projet vise à prédire l'issue des matchs de tennis du circuit ATP en utilisant des techniques de Machine Learning. Il a été conçu pour démontrer une méthodologie complète de Data Science, du nettoyage des données à l'évaluation d'un modèle prédictif.

## 🚀 Structure du Projet

Le projet est divisé en trois notebooks principaux :

1.  **`01_Data.ipynb`** : Chargement des données historiques (2000-2024), nettoyage et analyse exploratoire (EDA).
2.  **`02_Features.ipynb`** : Feature Engineering, création de variables relatives (différence de classement, d'âge, de taille) et préparation du dataset pour l'entraînement.
3.  **`03_Model.ipynb`** : Entraînement d'un modèle Random Forest, évaluation des performances et analyse de l'importance des variables.

## 📊 Données

Les données proviennent du dépôt de [Jeff Sackmann](https://github.com/JeffSackmann/tennis_atp), référence dans le domaine des statistiques de tennis. Elles incluent :
- Les classements ATP
- Les statistiques détaillées par match (aces, doubles fautes, balles de break, etc.)
- Les caractéristiques des joueurs (âge, taille, main dominante)

## 🛠️ Installation

```bash
# Cloner le dépôt
git clone https://github.com/votre-username/tennis-machine-learning.git

# Installer les dépendances
pip install -r requirements.txt
```

## 📈 Résultats

Le modèle actuel (Random Forest) atteint une précision d'environ **70%** en utilisant uniquement des données disponibles avant le début du match (classement et caractéristiques physiques).

---
*Projet réalisé dans le cadre d'un portfolio pour un premier stage en Data Science / Ingénierie.*
