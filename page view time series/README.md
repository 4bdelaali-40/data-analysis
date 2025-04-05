# Page Views Analysis

Ce projet visualise les données de fréquentation du forum FreeCodeCamp entre mai 2016 et décembre 2019.  
Il a été réalisé avec **Pandas**, **Matplotlib** et **Seaborn** pour explorer des tendances temporelles et saisonnières à travers différents types de graphiques.

## Fichiers

- `fcc-forum-pageviews.csv` : Données sources.
- `app.ipynb` : Fichier principal contenant les fonctions de visualisation.
- `line_plot.png` : Graphique des vues quotidiennes.
- `bar_plot.png` : Moyenne mensuelle des vues par année.
- `box_plot.png` : Répartition annuelle et mensuelle des vues (boxplots).


## Fonctionnalités

### `draw_line_plot()`
Affiche l’évolution quotidienne du trafic sur le forum.

### `draw_bar_plot()`
Affiche la moyenne des vues quotidiennes pour chaque mois, groupées par année.

### `draw_box_plot()`
Affiche deux boxplots :
- Répartition des vues par année (tendance).
- Répartition des vues par mois (saisonnalité).