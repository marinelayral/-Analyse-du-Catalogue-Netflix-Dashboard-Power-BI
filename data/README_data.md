# 📁 Documentation des données

## 📌 Source des données
Les données utilisées pour ce projet proviennent de deux sources principales :

### **1️⃣ Netflix Titles Dataset**
- Source : Kaggle — Netflix Movies and TV Shows Dataset  / transmis par Jedha
- Contenu : Films, séries, genres, pays d’origine, date d’ajout, durée, etc.  
- Utilisation : Analyse des tendances, géographie, genres dominants.

### **2️⃣ IMDb Dataset (enrichissement)**
- Source : IMDb  / accessibles via Jedha
- Contenu : Notes, votes, informations qualité des œuvres.  
- Utilisation : Ajouter une dimension « qualité » (notes IMDb), ROI et budget.

---

## 📌 Nettoyage et préparation des données
Voici les principales étapes réalisées :

- Suppression des doublons  
- Standardisation des dates  
- Normalisation des champs texte (genres, pays, acteurs)  
- Jointure entre le dataset Netflix et IMDb  
- Création de variables dérivées :
  - `score_imdb`
  - `popularity`
  - `ROI`
  - `categorie_duree`

---

## 📌 Objectif du jeu de données
Créer une base exploitable permettant d’obtenir :

- un aperçu global du catalogue Netflix  
- une lecture business grâce aux métriques issues d’IMDb  
- une segmentation pertinente pour le dashboard Power BI  

