# Azure Data Factory – Simple ETL Pipeline

## Objectif
Pipeline ETL simple permettant d’ingérer un fichier CSV stocké dans Azure Blob Storage,
de sélectionner certaines colonnes et de charger les données dans une base PostgreSQL
pour visualisation dans Power BI.

## Architecture
- Source : Azure Blob Storage (CSV)
- Orchestration & ETL : Azure Data Factory
- Base de données : Azure Database for PostgreSQL
- Visualisation : Power BI

## Étapes du pipeline
1. Lecture du fichier CSV depuis Blob Storage
2. Sélection des colonnes pertinentes
3. Conversion des types (string, numeric, date) (natif)
4. Chargement des données dans PostgreSQL
5. Connexion de Power BI à PostgreSQL pour la visualisation

## Cas d’usage
- Pipeline de données batch
- Préparation de données pour reporting
- Démonstration d’un flux cloud end-to-end

## Limites
- Transformations simples
- Non adapté aux transformations lourdes ou au temps réel

## Évolutions possibles
- Ajout de contrôles qualité
- Passage à Azure Databricks pour transformations avancées
- Historisation des données
- Gestion des logs et erreurs

## Lien dashboard PowerBI
https://up13-my.sharepoint.com/:u:/g/personal/12111060_edu_sorbonne-paris-nord_fr/IQAVtyVrBZNFTa69jvEzZdefAU2tDQYGtAs2dkTI2v7f-yM?e=3jCqzZ
