# Analyse de l'impact du sommeil sur la performance cognitive

## Présentation

Ce projet vise à étudier l'influence des habitudes de sommeil et de différents facteurs liés au mode de vie sur la performance cognitive des étudiants. L'analyse repose sur un jeu de données relatif à la santé du sommeil et utilise des méthodes statistiques et de visualisation afin d'identifier les variables les plus significatives.

## Structure du projet

```text
Data_processing/
│
├── data/
│   └── sleep_health_dataset.csv
│
├── figures/
│   ├── fig1_exploration.png
│   ├── fig2_coefficients.png
│   ├── fig3_residus.png
│   ├── fig4_crossval.png
│   ├── fig_all_correlations.png
│   ├── fig_conditional_probability.png
│   └── fig_multidimensional.png
│
├── notebook/
│   └── recreate_sleep_figures_github.ipynb
│
├── slides/
│   └── groupe11_zellama_boumaiza_louati.pdf
│
└── README.md
```

## Objectifs

Les principaux objectifs de ce projet sont :

* Étudier les facteurs influençant la performance cognitive.
* Analyser la relation entre la qualité du sommeil et les capacités cognitives.
* Identifier les variables les plus corrélées à la performance cognitive.
* Construire et évaluer des modèles statistiques explicatifs.
* Produire des visualisations facilitant l'interprétation des résultats.

## Jeu de données

Le jeu de données contient des informations relatives à :

* La durée du sommeil ;
* La qualité du sommeil ;
* Le pourcentage de sommeil profond ;
* Le pourcentage de sommeil paradoxal (REM) ;
* L'activité physique quotidienne ;
* Le nombre de pas effectués ;
* Le temps d'écran avant le coucher ;
* Le niveau de stress ;
* Les indicateurs de santé mentale ;
* Les troubles du sommeil ;
* Les performances cognitives.

## Méthodologie

### 1. Prétraitement des données

* Nettoyage des données ;
* Sélection des individus ayant le statut d'étudiant ;
* Encodage des variables catégorielles ;
* Préparation des variables pour l'analyse statistique.

### 2. Analyse exploratoire

Une analyse descriptive est réalisée afin de mieux comprendre la distribution des variables et leurs relations potentielles.

### 3. Analyse de corrélation

Le coefficient de corrélation de Pearson est utilisé pour mesurer l'intensité des relations entre les différentes variables et la performance cognitive.

### 4. Modélisation statistique

Des modèles de régression sont utilisés pour identifier les facteurs ayant le plus d'influence sur la performance cognitive.

### 5. Validation des modèles

Les performances des modèles sont évaluées à l'aide :

* d'une validation croisée (cross-validation) ;
* d'une analyse des résidus ;
* de mesures d'erreur adaptées.

## Figures générées

| Figure                          | Description                                                  |
| ------------------------------- | ------------------------------------------------------------ |
| fig1_exploration.png            | Analyse exploratoire des données                             |
| fig2_coefficients.png           | Importance des variables explicatives                        |
| fig3_residus.png                | Analyse des résidus du modèle                                |
| fig4_crossval.png               | Résultats de la validation croisée                           |
| fig_all_correlations.png        | Corrélations entre les variables et la performance cognitive |
| fig_conditional_probability.png | Analyse probabiliste conditionnelle                          |
| fig_multidimensional.png        | Représentation multidimensionnelle des données               |

## Installation

### Prérequis

* Python 3.10 ou supérieur

### Bibliothèques utilisées

```bash
pip install pandas numpy matplotlib scipy scikit-learn
```

## Exécution

Lancer le notebook Jupyter :

```bash
jupyter notebook notebook/recreate_sleep_figures_github.ipynb
```

Puis exécuter l'ensemble des cellules afin de :

1. Charger les données ;
2. Effectuer le prétraitement ;
3. Générer les visualisations ;
4. Sauvegarder automatiquement les figures dans le dossier `figures`.

## Résultats

Les résultats mettent en évidence les facteurs du sommeil et du mode de vie les plus associés à la performance cognitive des étudiants, permettant une meilleure compréhension des mécanismes influençant les capacités cognitives.



## Cadre académique

Projet réalisé dans le cadre d'un travail universitaire portant sur l'analyse de données et les méthodes statistiques appliquées à la santé et aux performances cognitives.

## Licence

Ce projet est destiné à un usage pédagogique et académique.
