# Analyse de la performance des produits – Sephora

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

Période étudiée : 2011 – 2023

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
- Les produits exclusifs sont les plus performants
- Les nouveautés performent moins que les produits installés
- Le prix optimal se situe entre 20 et 50 USD
- Le volume d’avis augmente dans le temps, mais pas nécessairement la satisfaction

---

## 🚀 Recommandations
- Mettre en avant les produits les mieux notés dans le parcours client
- Développer des stratégies autour des produits exclusifs
- Maintenir un positionnement prix optimal
- Travailler la qualité produit en parallèle de la visibilité

---

## 🛠️ Outils utilisés
- Python (analyse exploratoire)
- Power BI (modélisation et visualisation)

---

## 📎 Fichiers
- Dashboard Power BI (PDF)
- Rapport d’analyse
- Présentation finale
- Notebook Python
