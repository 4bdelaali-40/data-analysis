# Medical Examination Data Visualizer

## Description
Ce projet permet d'analyser et de visualiser les données médicales collectées lors d'examens médicaux. L'objectif est d'explorer les relations entre les maladies cardiovasculaires, les mesures corporelles, les marqueurs sanguins et les habitudes de vie.

Le projet inclut deux visualisations principales :
1. **Graphique catégoriel** : Compare les distributions des facteurs de risque (cholestérol, glucose, tabac, alcool, activité physique, surpoids) selon la présence ou non de maladies cardiovasculaires.
2. **Carte de chaleur (heatmap)** : Montre les corrélations entre les différentes variables après un nettoyage des données.

## Données utilisées
Le projet utilise le fichier **medical_examination.csv**, contenant des informations sur des patients, avec des colonnes telles que :
- `age` (en jours)
- `height` (cm)
- `weight` (kg)
- `ap_hi`, `ap_lo` (pression artérielle systolique et diastolique)
- `cholesterol`, `gluc` (niveaux de cholestérol et glucose : normal, élevé, très élevé)
- `smoke`, `alco`, `active` (habitudes : fumeur, alcool, activité physique)
- `cardio` (présence ou non de maladie cardiovasculaire)

## Résultats
Le script génère :
- Un **graphique catégoriel** (`catplot`) comparant les facteurs de risque entre patients malades et non malades.
- Une **heatmap** des corrélations entre les variables après nettoyage des données.
