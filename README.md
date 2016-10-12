# -Chapitre-F (English)

This experiments of Netlogo Ants are inspirated by the version developped by OpenMOLE team, avalaible directly from OpenMOLE software into [market](http://www.openmole.org/current/Documentation_Market%20Place.html) or directly from [github](https://github.com/openmole/openmole-market/tree/6-dev/ants) repository.

## Simulations and Workflows 

- Ants simulation used for design experiments : `./ants.nlogo`

- OpenMOLE workflow for calibration : `./scripts_experience/calibration/ants_calibration.oms`

- OpenMOLE workflow for replication :  `./scripts_experience/replication/ants_replication.oms`

After the import of Netlogo `.nlogo` and Workflow `.oms`files into [OpenMOLE](http://www.openmole.org/current/) software, you need to modify the path of file !!

## Results

Results used to build visualisation can be found into `/calibration`, and `/replication` folders into  `/scripts_experience/data-book/` folder.

Requierements to reproduce the differents visualisations are : 

- Ubuntu 16.04 (ou autre Linux)
- R scripting front-end version 3.3.1 (2016-06-21) with plugins : 
 - dplyr 0.4.3
 - ggplot2 2.1.0
 - readr 0.2.2
 - tools 3.3.1
- gnuplot 5.0 patchlevel 3

In order to generate the first 3 visualisations (`./scripts_graphique/graphique_stochasticite/*.pdf`) of replication design experiment : 

```
cd ./scripts_graphique/graphique_stochasticite/
./replication.sh
```

If you want to generate the video (`./scripts_graphique/video_pareto/replications.webm`) to follow the evolution of Pareto Front during optimisation : 

```
cd ./scripts_graphique/video_pareto/
./video.sh
```

# -Chapitre-F (French)

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

