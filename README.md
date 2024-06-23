# Projet hydraulic monitoring

## Objectifs

* Objectif : Construire un modèle ML pour prédire si la condition valve est optimale (=100%) ou non, pour chaque cycle. Vous utiliserez les 2000 premiers cycles pour construire le modèle et le reste comme échantillon de test final.   

* Données : Les données sont disponibles dans le dossier **data**. 

Les données sont décrites dans le lien suivant : https://archive.ics.uci.edu/dataset/447/condition+monitoring+of+hydraulic+systems. 

Le dossier data contient les 3 fichiers de données suivants, chaque ligne représentant un cycle : 
* PS2 (Pression (bar) echantillonnage 100Hz) 
* FS1 (Volume flow (l/min) echantillonnage 10Hz) 
* Profile : Fichier avec les variables dont la "valve condition" qui nous intéresse. 


## Contenu
Les résultats sont actuellement présentés sous forme de notebooks:
* Analyse: Analyse rapide des données
* Classifieur: Construction et évaluation d'un classifieur

## Comment utiliser
* Cloner le repo localement
* Puis, créer un environement virtuel (plutôt avec poetry)

## Pour créer un environement virtuel avec les librairies nécéssaires (avec poetry)
Il faut utiliser poetry:
* install [poetry](https://python-poetry.org/docs/)
* run `poetry install`

To run notebooks (with local jupyter server):
* run `poetry run jupyter notebook`

Or to run (with VS Code):
* run `poetry shell` and `code .`

