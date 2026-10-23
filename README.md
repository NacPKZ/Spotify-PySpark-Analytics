<div align="center">

# Spotify PySpark Analytics
### Analyse Big Data · Apache Spark · Machine Learning

**Exploration d'un catalogue de 114 000 titres Spotify avec PySpark : préparation des données, analyses musicales, transformations distribuées et expérimentation de clustering.**

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white) ![Apache Spark](https://img.shields.io/badge/Apache_Spark-E25A1C?logo=apachespark&logoColor=white) ![PySpark](https://img.shields.io/badge/PySpark-Big_Data-2563EB) ![Spotify](https://img.shields.io/badge/Spotify-Dataset-1DB954?logo=spotify&logoColor=white)

</div>

---

## Le projet en chiffres

| Titres | Variables | Moteur de traitement | Approche |
|:---:|:---:|:---:|:---:|
| **114 000** | **21** | **Apache Spark** | **Analyse & clustering** |

> **Contexte :** projet universitaire de Master 1 réalisé sur un jeu de données public. Les chiffres correspondent à la description du jeu de données, et non à des performances mesurées de Spark.

## Objectifs analytiques

| Étape | Travail étudié |
|---|---|
| **01 · Ingestion** | Chargement et exploration du catalogue musical |
| **02 · Préparation** | Nettoyage, typage et contrôle des données |
| **03 · Exploration** | Popularité, genres et caractéristiques audio |
| **04 · Spark SQL** | Jointures, agrégations, pivots et fonctions de fenêtre |
| **05 · Optimisation** | Cache, broadcast join et analyse des plans d'exécution |
| **06 · Machine Learning** | Expérimentation de segmentation avec K-Means |

## Chaîne de traitement

`Spotify Tracks Dataset → PySpark → Nettoyage → Transformations Spark SQL → Analyse exploratoire → Clustering`

### Consulter le projet

[**Notebook Jupyter**](notebooks/01_setup_et_ingestion.ipynb) · [**Dépendances**](requirements.txt) · [**Code du dépôt**](notebooks/)

> **Disponibilité des livrables :** le dépôt public contient actuellement un notebook intitulé `01_setup_et_ingestion.ipynb`. Les autres étapes sont présentées comme objectifs du projet ; leur réalisation complète ne peut pas être déduite de la seule présence de ce fichier.

---

<details>
<summary><strong>Afficher la présentation d'origine et les instructions d'installation</strong></summary>

Projet universitaire **Master 1** — Introduction à PySpark.  
Analyse de 114 000 chansons du catalogue Spotify via Apache Spark en Python.

## 📊 Objectifs

1. Charger et nettoyer un dataset de 114 000 chansons
2. Explorer les caractéristiques musicales (features audio, popularité)
3. Appliquer des transformations avancées (joins, pivots, window functions)
4. Optimiser les performances (cache, broadcast join, explain)
5. Construire un modèle de clustering (K-Means)
6. Produire des visualisations et insights métier

## 🗂️ Dataset

- **Source** : Spotify Tracks Dataset (Kaggle, licence CC0)
- **Volume** : 114 000 chansons × 21 colonnes

## 🚀 Démarrage rapide

### Prérequis
- Python 3.10+
- Java 11
- PySpark 3.5.0

### Installation

```bash
conda create -n pyspark-projet python=3.10 openjdk=11 pyspark=3.5.0 \
    jupyter pandas matplotlib seaborn scikit-learn -c conda-forge -y
conda activate pyspark-projet
```

### Télécharger le dataset

Le dataset n'est pas inclus dans le repo. Il se télécharge automatiquement via la première cellule du notebook.

## 📁 Structure du projet

```text
projet-pyspark-spotify/
├── data/                          # Dataset (ignoré par Git)
├── notebooks/
│   └── 01_setup_et_ingestion.ipynb
├── slides/                        # Slides de soutenance
├── .gitignore
└── README.md
````

## 👥 Auteurs

- **Yanis Tounsi**
- **Can Pekgoz**

</details>
