# -Chapitre-F

Ces expériences sur le modèle Netlogo Ants sont inspirés du travail réalisés par l'équipe d'OpenMOLE sur le modèle Ants, disponible au téléchargement directement depuis OpenMOLE via le [market](http://www.openmole.org/current/Documentation_Market%20Place.html), ou plus directement encore sur le dépôt [github](https://github.com/openmole/openmole-market/tree/6-dev/ants) correspondant.

## Modèle et Workflows 

- Le modèle Ants utilisé pour les expériences : `./ants.nlogo`

- Le workflow openMOLE pour la calibration : `./scripts_experience/calibration/ants_calibration.oms`

- Le workflow openMOLE pour la replication :  `./scripts_experience/replication/ants_replication.oms`

Lorsque vous importez le modèle Netlogo et ces deux workflows dans le logiciel [OpenMOLE](http://www.openmole.org/current/), pensez à modifier les chemins pointant vers le modèle dans les deux fichier `.oms` !!

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

Pour générer les trois premiers graphiques (`./scripts_graphique/graphique_stochasticite/*.pdf`) illustrant les différents résultats de l'expérience replication : 

```
cd ./scripts_graphique/graphique_stochasticite/
./replication.sh
```

Pour générer la vidéo  (`./scripts_graphique/video_pareto/replications.webm`) montrant l'évolution du front de Pareto lors de l'optimisation : 

```
cd ./scripts_graphique/video_pareto/
./video.sh
```

