# Analyse de la performance des produits – Sephora - Power BI - Python

<img width="1435" height="809" alt="Capture d&#39;écran 2026-04-15 114409" src="https://github.com/user-attachments/assets/0b034b0e-9b21-40f4-970b-faebc99d22cd" />


## 📊 Contexte
Projet réalisé dans le cadre de la formation Data Analyst.

Objectif :
Analyser les facteurs qui influencent la performance des produits de beauté sur une plateforme e-commerce et proposer des recommandations marketing exploitables.

---

## 📁 Dataset
- 1 table produits (8 494 lignes)
- 1 table de reviews sélectionnée parmi 6 fichiers (échantillon représentatif)
- 602 130 avis clients analysés
- 250 produits distincts

Période étudiée : 2018 – 2023

---

## ⚙️ Méthodologie
- Nettoyage et transformation des données (Power Query)
- Fusion des tables via `product_id` (Left Join)
- Création d’un dataset final enrichi
- Agrégation au niveau produit (Product_Summary)
- Construction d’un score de performance :

Score_performance = 0.5 × Popularité (likes) + 0.5 × Satisfaction (rating)

---

## 📈 Analyses réalisées
- Impact de l’exclusivité, des éditions limitées et des nouveautés
- Influence du prix sur la performance
- Top produits les plus performants
- Analyse temporelle des avis et du rating

---

## 💡 Principaux insights
- Les produits exclusifs sont les plus performants avec 93 du score
- Les nouveautés performent moins que les produits installés 
- Le prix optimal se situe entre 20 et 50 USD
- Le volume d’avis augmente dans le temps, mais pas nécessairement la satisfaction

---

## 🚀 Recommandations
- Mettre en avant les produits les mieux notés dans les points clés du parcours client (homepage, fiches produits, recommandations) pour améliorer la conversion
- Capitaliser sur les produits exclusifs comme levier de performance et de différenciation marketing
- Maintenir un positionnement prix entre 20 et 50 USD, zone où performance et attractivité sont maximisées
- Ne pas se limiter à augmenter la visibilité : renforcer la qualité produit pour stabiliser la satisfaction client dans le temps
---

## 📎 Fichiers
dashboard_powerbi.pdf
analysis_python.ipynb
rapport_business.pdf

---

## 🛠️ Outils utilisés

- Power BI (dashboard & visualisation)
- Python (data cleaning & analysis)
- SQL (data extraction)
- Power Query (transformation des données)
