# 🎬 Analyse du Catalogue Netflix – Dashboard Power BI  
### Projet réalisé dans le cadre d’un bootcamp de Data Analyse

## 🧩 Contexte

Ce projet a été réalisé dans le cadre d’un bootcamp de reconversion en data analyse.  
Le brief initial *“In Netflix Data Analyst Shoes”* consistait à analyser le catalogue Netflix afin d’identifier :

- les genres dominants,
- les pays producteurs majeurs,
- la présence géographique de Netflix,
- les tendances temporelles,
- la saisonnalité des sorties.

👉 De manière proactive, j’ai enrichi le dataset initial avec une base **IMDb** afin d’ajouter une dimension **qualité**, **budget** et **ROI**, orientant ainsi le projet vers une véritable lecture business.

---

# 🎯 Objectifs du projet

- Réaliser une EDA complète du catalogue Netflix  
- Identifier les tendances clés (genres, formats, pays, périodes)  
- Mesurer la performance via les scores IMDb  
- Calculer des indicateurs ROI orientés business  
- Créer un dashboard Power BI multi-pages  
- Fournir des recommandations stratégiques basées sur les données

---

# 🔧 Sources & Méthodologie

## 📥 Données utilisées
- **netflix_titles.csv** – Catalogue officiel Netflix  
- **imdb_movies.csv** – Enrichissement IMDb (ajout proactif)

## 🛠 Étapes d’analyse
1. Nettoyage des données & conversion des types  
2. Harmonisation des colonnes & jointure Netflix × IMDb  
3. Création de mesures (score moyen, ROI, croissance…)  
4. Détection et qualification des biais  
5. Construction d’un dashboard Power BI à 6 pages  
6. Recommandations business (genres, pays, publics)

---
## 📊 Aperçu du Dashboard Power BI

<a href="./dashboard/Projet_netflix_data_analysis.pbip">
  <img src="./dashboard/Dashboard_overview.png" alt="Aperçu du Dashboard Power BI" width="800">
</a>

***Clique sur l’image pour ouvrir le fichier Power BI (.pbip)***  
---

# 📊 Principaux insights

## 📌 Composition du catalogue
- **8 802 titres**  
- **69,63 % Films** / **30,37 % Séries**  
- **36 genres**  
- Présence dans **123 pays producteurs**  
- Croissance du catalogue : **+17,27 % entre 2015 et 2021**

## ⭐ Qualité & performance
- Score IMDb global : **65,69** (supérieur à IMDb global : 63,52)  
- Durée moyenne films : **99,55 min**  
- Séries : **1,77 saison en moyenne**

## 👥 Analyse audience
- Public majoritaire : **Adultes (42,63 %)**  
- Très bon potentiel ROI : **Adolescents** et **Kids TV**

## 🌍 Analyse pays producteurs
- USA (51 %), Inde, UK = 3 leaders  
- Plus forte croissance : **Nigeria (+27 %)**

---

# 🧪 Analyse de fiabilité

L'échantillon IMDb apporte une vraie valeur business mais présente des biais :

- Films surreprésentés (83 % vs 70 % dans le catalogue)  
- Fiabilité :  
  - **Genres** : Haute  
  - **Pays** : Haute  
  - **Publics** : Variable (biais > 30 % pour certains segments)

👉 Toutes les comparaisons Films vs Séries sont invalidées.  
👉 Les analyses segmentées Genre / Pays / Public restent valides.

---

# 🖥️ Dashboard Power BI

**6 pages interactives :**

1. **Overview** – KPIs clés, évolution du catalogue  
2. **Genres** – Top genres, tendances IMDb, distributions  
3. **Public** – Segmentation audience & scores moyens  
4. **Format** – Durées, saisons, corrélations Score × Format  
5. **Recommandations business** – ROI, qualité, opportunités  
6. **Fiabilité & biais** – Analyse méthodologique

---

# 🚀 Compétences démontrées

- Data cleaning  
- Fusion et modélisation multi-sources  
- DAX avancé & mesures personnalisées  
- Data visualisation & design UX (branding Netflix)  
- Analyse statistique & détection de biais  
- Storytelling avec les données  
- Business intelligence & recommandations stratégiques

---

# 🎨 Design

- Palette **Netflix (rouge / noir)**  
- Navigation multi-pages  
- Graphiques variés (barres, treemap, scatter, cartes)  
- Mise en avant visuelle des insights et de la fiabilité  

---

# 📁 Structure

netflix-analysis/
- dashboard Power BI
    - Dashboard pdf
    - Dashboard pbix
- data
    - netflix
    - imbd
- README.md

---

# 📬 Contact

📧 Email : marine.layral@gmail.com 
🔗 LinkedIn : https://www.linkedin.com/in/marine-layral-0207b359/  
💼 GitHub : https://github.com/marinelayral  
🌐 Portfolio : https://marinelayral.github.io/










