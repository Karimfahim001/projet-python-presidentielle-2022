# Projet Python — Présidentielle 2022 (T1/T2) — EDA (Open Data)

## Contexte
Produire une analyse exploratoire (EDA) sur un dataset complexe, sans prédiction.  
Mon objectif e de st comparer le Tour 1 et le Tour 2 et comprendre l’évolution de la participation/abstention, la qualité du vote (blancs/nuls) et les écarts territoriaux.

## Dataset
Résultats agrégés par bureau de vote — Présidentielle 2022 (T1 & T2).  
Limites : données agrégées (pas de variables socio-démographiques), interprétation prudente sur certains territoires spécifiques.

## Méthodologie
- Contrôles qualité : valeurs manquantes, doublons, types, cohérence métier (inscrits/votants/abstentions).
- Création de variables dérivées :
  - taux participation / abstention
  - blancs et nuls en % des votants
  - segmentation par taille de bureau (selon inscrits)
- Visualisations : distributions, comparaisons territoriales, corrélations (heatmap).
- Export d’un fichier final nettoyé en CSV.

## Insights
- Participation moyenne en baisse au T2 (≈ -1,37 point) et abstention en hausse.
- Hausse marquée des votes blancs et nuls au T2.
- Forte variabilité territoriale (départements) et dispersion entre bureaux.
- Relation très faible entre abstention et vote blanc (comportements différents).

## Contenu du repo
- Notebook : `KARIM_FAHIM_ATELIER_DEV.ipynb`
- Données Kaggle: `resultats_elections_2022_presidentielle_T1_T2_clean.csv`
- Rapport : `Rapport_analytique_Atelier_Developpement.pdf`

## Outils
Python (pandas, numpy, matplotlib, seaborn) — Google Colab / Jupyter.

