# Analyse des ventes Online Retail II

Ce projet vise à analyser les ventes d'une entreprise britannique entre 2009 et 2011.
Il comprend le nettoyage des données, un dashboard Power BI, une exploration statistique et un modèle de machine learning.

## Source des données

- **Dataset** : Online Retail II
- **Période** : décembre 2009 à décembre 2011
- **Lien** : https://www.kaggle.com/datasets/mashlyn/online-retail-ii-uci
- **Fichier attendu** : `online_retail_II.csv`, à placer dans `data/raw/` à la racine du projet

Le fichier n'est pas inclus dans le dépôt (il est ignoré via `.gitignore`), il faut donc le télécharger avant de lancer les notebooks.

## Questions business

### Ventes dans le temps

- Comment le chiffre d'affaires évolue-t-il mois par mois, et y a-t-il une saisonnalité ?

### Produits et pays

- Quels pays génèrent le plus de chiffre d'affaires ?
- Quels produits génèrent le plus de chiffre d'affaires ?

### Clients

- Quelle part des clients a commandé plus d'une fois, et quelle part du chiffre d'affaires représentent-ils ?

## Définitions

- **Chiffre d'affaires** = `Quantity` × `Price`
- **Client fidèle** : client ayant au moins deux factures distinctes (`Invoice`).
- La question sur les clients ne porte que sur les lignes où `Customer ID` est renseigné.

## Plan du projet

- Nettoyage des données
- Dashboard Power BI
- Exploration statistique
- Machine learning (entraînement d'un modèle prédictif)
