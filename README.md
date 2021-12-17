# Projet

## Démarrage
Il est recommendé d'utiliser la distribution Anaconda de Python pour créer un environement python. Vous pouvez télécharger Anaconda sur leur site officiel.

Après installation d'Anaconda, créer et acriver un nouvel environement avec le nom "esd_intro_ml"
```
conda create --name esd_intro_ml python=3.8
conda activate esd_intro_ml
```
Après l'activation de l'environnement, veuillez installer les librairies nécessaires:
```
pip install -r requirements.txt
```
Après installation des librairies python, veuillez installer les extensions pour Jupyter Notebook

```
sh install_nb_extensions.sh
```

## Description 

L'objectif de ce projet est de créer une segmentation de données clients grâce à un algorithme de K-means.

Pour ce faire, il faudra réaliser les étapes suivantes:

1. Analyse de rentabilisation
2. Préparation des données
3. Segmentation avec le clustering K-means
4. Réglage des hyperparamètres
5. Visualisation et interprétation des résultats

