# Fiche sujet F1 : Risque de crédit en Allemagne

## 1. Problématique
Quels attributs du client et du prêt permettent d'identifier les mauvais risques de crédit ?

## 2. Objectif du projet
L'objectif est de construire un modèle de classification binaire permettant de distinguer les bons clients des mauvais clients afin d'aider à la prise de décision en matière d'octroi de crédit.

## 3. Jeu de données
- Nom : German Credit Data
- Source : UCI Machine Learning Repository
- Lien : https://archive.ics.uci.edu/dataset/144/statlog+german+credit+data
- Nombre d'observations : 1 000
- Nombre de variables explicatives : 20
- Nombre de mauvais risques : 300

## 4. Méthodes utilisées
Trois modèles de classification sont étudiés :
- Régression logistique
- Arbre de décision
- Forêt aléatoire

## 5. Évaluation
Les modèles sont évalués à l'aide de l'AUC et du coût financier total, en tenant compte des coûts asymétriques des erreurs de classification.

Le coût d'acceptation d'un mauvais risque est fixé à cinq fois celui du refus d'un bon client.

## 6. Résultat principal
La régression logistique présente le coût total de validation le plus faible parmi les trois modèles comparés, avec un coût de 100 pour le seuil retenu de 0,11.
