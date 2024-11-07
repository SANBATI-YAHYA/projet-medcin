# Projet d'Analyse de Données : L'Effet du Lavage des Mains par le Dr Semmelweis

## Introduction
Ce projet vise à analyser les données collectées entre 1841 et 1849 à l'Hôpital Général de Vienne, afin de comprendre l'impact des pratiques d'hygiène, comme le lavage des mains, introduites par le Dr Ignaz Semmelweis sur le taux de mortalité en maternité.

## Contenu
- **Data/** : contient les fichiers de données nécessaires à l'analyse (`monthly_deaths.csv`, `annual_deaths_by_clinic.csv`).
- **Support/** : documents de support expliquant les étapes de l'analyse.
- **Solutions/** : solutions et résultats finaux de l'analyse.

## Objectifs de l'Analyse
1. Explorer les données : examiner la forme des DataFrames, les doublons, les valeurs manquantes, et les statistiques de base.
2. Visualiser les tendances des naissances et décès sur le temps.
3. Comparer le taux de mortalité dans deux cliniques distinctes de l'hôpital.
4. Mesurer l'impact du lavage des mains introduit en juin 1847.

## Techniques Utilisées
- Python (Pandas pour la manipulation de données, Matplotlib et Seaborn pour la visualisation, Plotly pour des graphiques interactifs).
- Analyses statistiques (tests de signification, moyennes mobiles, etc.)
- Estimation de densité par noyau (KDE) et tests T pour valider l'impact statistique.

## Résultats Attendus
L'analyse vise à démontrer l'impact statistiquement significatif du lavage des mains sur la réduction du taux de mortalité, montrant ainsi l'importance des pratiques d'hygiène en milieu hospitalier.

## Instructions
1. Charger les données dans les DataFrames `df_yearly` et `df_monthly`.
2. Suivre les étapes de l'exploration, visualisation, et analyse comme indiqué dans les documents de support.
3. Comparer les résultats obtenus avant et après l'introduction du lavage des mains pour évaluer son effet.

## Auteurs
Ce projet a été réalisé pour analyser les données médicales historiques et démontrer les impacts des pratiques d’hygiène.