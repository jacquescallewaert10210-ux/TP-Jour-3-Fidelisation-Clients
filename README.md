# TP Jour 3 - Fidélisation Clients

## Objectif

Ce projet analyse la fidélisation des clients à partir de données de commandes, de produits et de profils clients.

La problématique étudiée est :

**Quels profils de primo-clients transforment le mieux leur premier achat en réachat rentable dans les 90 jours ?**

## Analyses réalisées

- Taux de réachat à 90 jours
- Comparaison de la marge entre clients fidèles et non fidèles
- Analyse par canal d'acquisition
- Analyse par catégorie de premier achat
- Analyse de l'impact des remises

## Données

Le dossier data contient :

- clients.csv
- commandes.csv
- produits.csv

## Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Fichiers principaux

- J3_01_TP_angle_libre.ipynb : analyse principale du Jour 3
- J3_02_exercices_avances.ipynb : exercices complémentaires

## Méthodologie

L'analyse porte uniquement sur les commandes livrées.

Le client est utilisé comme unité statistique principale.

Le réachat est défini comme une deuxième commande livrée dans les 90 jours suivant le premier achat.

Une fenêtre fixe de 90 jours permet de comparer les clients sur une durée identique.

## Limites

Les résultats montrent des associations mais ne permettent pas d'établir directement une causalité.

Les coûts marketing des différents canaux d'acquisition ne sont pas disponibles.
