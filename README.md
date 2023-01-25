# Carte des séismes dans le monde en 2022
***

Ce projet avait pour but de réaliser une carte du monde des séismes de magnitude supérieure ou égale à 4,5 en 2022. Tout a été réalisé dans le langage Python. On y trouve un notebook avec le code ayant permis de tracer la carte ainsi que le jeu de données et la carte finale au format png.

## Données
***

Les données sont issues de l'US Geological Survey (https://www.usgs.gov/programs/earthquake-hazards/earthquakes, 2023). Elles sont regroupées en deux fichiers geojson :

 - un fichier pour les séismes ayant eu lieu entre janvier et juin (*seismes01-06.geojson*)
 - un fichier pour les séismes ayant eu lieu entre juillet et décembre (*seismes07-12.geojson*)

 Le fond de carte du monde est le fichier *world_map.geojson*