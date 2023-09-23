# Detection_de_Fraude
# Détection de Fraude par Carte de Crédit

Ce projet vise à développer un modèle de détection de fraudes par carte de crédit en utilisant des techniques de machine learning.

## Description

La base de données utilisée contient des transactions effectuées par des titulaires de cartes de crédit européennes en septembre 2013. Le jeu de données est hautement déséquilibré, avec un petit nombre de fraudes parmi un grand nombre de transactions normales. L'objectif principal de ce projet est de développer un modèle capable de détecter de manière précise les fraudes parmi les transactions normales.

## Modèles de Machine Learning

### Forêt Aléatoire

J'ai utilisé le modèle de Forêt Aléatoire pour détecter les fraudes dans les transactions par carte de crédit. Le modèle a été entraîné sur l'ensemble de données d'entraînement et évalué sur l'ensemble de test. Les performances du modèle ont été évaluées à l'aide de métriques telles que la précision, le rappel et le score F1.

### Arbre de Décision

Un autre modèle que j'ai exploré est l'Arbre de Décision. J'ai entraîné cet arbre de décision sur les données d'entraînement et analysé ses performances en termes de précision et de rappel.

### Régression Logistique

J'ai également utilisé un modèle de Régression Logistique pour détecter les fraudes. Ce modèle est particulièrement adapté à la classification binaire. J'ai évalué sa précision, son rappel et son score F1.

## Évaluation des Modèles

J'ai comparé les performances de ces trois modèles en utilisant des métriques telles que le rappel (pour détecter les vraies fraudes), la précision (pour minimiser les faux positifs) et le score F1 (pour l'équilibre entre précision et rappel). Ces métriques m'ont permis de choisir le modèle le plus adapté à la détection de fraudes par carte de crédit.

## Conclusion

La détection de fraudes par carte de crédit est un défi important pour les institutions financières. Ce projet a montré comment différents modèles de machine learning peuvent être utilisés pour aborder ce problème. Les performances des modèles peuvent être améliorées en ajustant les hyperparamètres et en utilisant des techniques d'équilibrage des classes pour les ensembles de données déséquilibrés.

N'hésitez pas à explorer les codes sources de ce projet pour plus de détails sur la mise en œuvre des modèles et des évaluations.


## Technologies Utilisées

- Python
- Scikit-Learn
- Keras
- TensorFlow
- Collab

## Structure du Projet

- `code/`: Ce répertoire contient le code python utilisés pour l'exploration des données, l'entraînement des modèles et l'évaluation des performances.
- `data/`: Vous pouvez télécharger le jeu de données à partir du [lien Kaggle](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud?resource=download) et le placer dans ce répertoire.
- `models/`: Ce répertoire contiendra les modèles entraînés une fois que le projet sera terminé j'ai sauvegarder que  celui de la foret aleatoire.
- `README.md`: Le fichier que vous lisez actuellement, fournissant des informations sur le projet.


## Prétraitement des Données

Avant de construire mes modèles, j'ai effectué une exploration de base des données pour comprendre la nature des transactions et leur répartition entre les classes (fraude et non-fraude). J'ai également divisé les données en ensembles d'entraînement et de test, et j'ai examiné les statistiques descriptives.


## Guide d'Utilisation

- Assurez-vous de spécifier le chemin d'accès correct du ficher dans le code.

## Contributeurs

- [HEBBADJ NESRINE ](https://github.com/Nesrineheb)

N'hésitez pas à contribuer à ce projet en créant des pull requests ou en signalant des problèmes.
