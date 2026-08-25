# Détection de faux avis Amazon

Ce dépôt contient les notebooks utilisés dans le cadre de mon mémoire de fin d'études consacré à la détection de faux avis à partir d'avis consommateurs Amazon.

L'objectif du projet est de comparer différentes approches de classification fondées sur des modèles de machine learning et de deep learning, puis d'étudier leur comportement en présence d'un déséquilibre des classes.

## Organisation du projet

```text
amazon_reviews_experimentation/
├── data/
│   ├── amazon_reviews.txt
│   ├── amazon_reviews_preprocessed.csv
│   ├── amazon_reviews_80_20.csv
│   └── amazon_reviews_90_10.csv
├── notebooks/
│   ├── 01_exploration_donnees.ipynb
│   ├── 02_pretraitement_textes.ipynb
│   ├── 03_modeles_machine_learning.ipynb
│   ├── 04_modeles_deep_learning.ipynb
│   └── 05_desequilibre_classes.ipynb
└── README.md