# Prévisions Météorologiques

## Description

Ce projet universitaire a pour objectif d'explorer les données météorologiques historiques de Londres (2011-2020) afin de construire des modèles prédictifs pour la température moyenne. Nous avons utilisé des méthodes de Machine Learning et de Deep Learning, en passant par des approches traditionnelles et des architectures neuronales complexes (GRU et CatBoost). Les prévisions résultantes peuvent être appliquées à des secteurs tels que la gestion des ressources énergétiques, le tourisme et la planification urbaine.

## Objectifs

L'objectif est de construire et de comparer plusieurs modèles prédictifs de la température moyenne sur une période d'un an à Londres, tout en testant leur performance sur des horizons plus courts (7 jours, 31 jours).

### Approches principales :
1. **GRU** pour modéliser la dépendance séquentielle et saisonnière des données.
2. **CatBoost** en exploitant des features retardées (lagged features) d’au moins un an.

Les résultats de ces modèles permettent d'améliorer la précision des prévisions, utiles dans des domaines comme la gestion énergétique ou le tourisme saisonnier.

## Installation

1. **Cloner le dépôt :**

    ```bash
    git clone https://github.com/lea19-ds/weather-forecast.git
    ```

2. **Créer et activer un environnement virtuel :**

    ```bash
    python -m venv venv
    source venv/bin/activate   # Pour MacOS/Linux
    venv\Scripts\activate      # Pour Windows
    ```

3. **Installer les dépendances :**

    ```bash
    pip install -r requirements.txt
    ```

## Utilisation

1. Ouvrez le fichier **weather-forecast.ipynb** dans Jupyter Notebook :

    ```bash
    jupyter notebook
    ```

2. Suivez les étapes décrites dans le notebook pour exécuter les modèles et visualiser les résultats.

## Résultats

Les résultats finaux des modèles, incluant les visualisations et comparaisons de performances, sont disponibles à la fin du notebook. Les prédictions sont évaluées sur des horizons de 7 jours, 31 jours et 1 an.
