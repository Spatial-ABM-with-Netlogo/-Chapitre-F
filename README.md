# -Chapitre-F

## Résultats
Les workflows OpenMOLE sont disponibles dans les repertoires 

## Résultats

Les résultats utilisés pour produire les graphiques sont dans les sous-repertoires  `/calibration`, et `/replication` dans le répertoire `/scripts_experience/data-book/`

Les pré-requis pour reproduire les graphiques sont les suivants : 

- Ubuntu 16.04 (ou autre Linux)
- R scripting front-end version 3.3.1 (2016-06-21) avec les librairies suivantes : 
 - dplyr 0.4.3
 - ggplot2 2.1.0
 - readr 0.2.2
 - tools 3.3.1
- gnuplot 5.0 patchlevel 3

Pour générer les trois premiers graphiques (`./scripts_graphique/graphique_stochasticite/*.pdf`) illustrant la replication : 

```
cd ./scripts_graphique/graphique_stochasticite/
./replication.sh
```

Pour générer la vidéo montrant l'évolution du front de Pareto (`./scripts_graphique/video_pareto/replications.webm`): 

```
cd ./scripts_graphique/video_pareto/
./video.sh
```

