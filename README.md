# Analyse des Données d'Arrestation à Los Angeles

## Introduction

Ce projet, intitulé **Precognition Police**, se concentre sur l'analyse et l'exploration d'un ensemble de données contenant plus d'un million d'arrestations dans la ville de Los Angeles, allant de 2010 à 2019. L'objectif est de découvrir des tendances, des modèles et des insights précieux sur les arrestations effectuées au fil des ans.

![Precognition Police](https://media0.giphy.com/media/pcKoz7f46DSa0B569s/giphy.gif?cid=ecf05e47gyrxbqea86o53p998pzp08th57c5hjrsdqetxkig&rid=giphy.gif&ct=g)

## Équipe de Projet

Ce projet a été développé par **Firas Dridi** et **Altin Hajda**, étudiants en 2ème année à la HE-ARC en ingénierie des données.

## Démarche

Notre analyse commence par le nettoyage du fichier CSV pour assurer la qualité des données. Nous utilisons `pandas`, une bibliothèque Python puissante pour le traitement des données, pour charger, nettoyer et explorer cet ensemble de données volumineux.

### Nettoyage des Données

Le nettoyage des données inclut la suppression des valeurs manquantes, la correction des formats de date et la normalisation des noms des colonnes pour faciliter l'analyse.

## Aperçu des Données

L'ensemble de données contient les colonnes suivantes, offrant diverses informations sur chaque arrestation :

- `Report ID` : Identifiant unique de l'arrestation.
- `Report Type` : Type de rapport associé à l'arrestation.
- `Arrest Date` : Date de l'arrestation.
- `Time` : Heure de l'arrestation.
- `Area ID` : Identifiant de la zone de l'arrestation.
- `Area Name` : Nom de la zone où l'arrestation a eu lieu.
- `Reporting District` : District rapportant l'arrestation.
- `Age` : Âge de la personne arrêtée.
- `Sex Code` : Sexe de la personne arrêtée.
- `Descent Code` : Code de descente de la personne arrêtée.
- `Charge Group Code` : Code du groupe de charges.
- `Charge Group Description` : Description du groupe de charges.
- `Arrest Type Code` : Code du type d'arrestation.
- Divers autres champs relatifs à l'adresse, la géolocalisation, et les détails de la mise en accusation.


## Technologies Utilisées

- **Python** : Langage de programmation pour le traitement des données et l'analyse.
- **Pandas** : Bibliothèque Python pour la manipulation et l'analyse des données.
- **Matplotlib/Seaborn** : Bibliothèques Python pour la visualisation des données.

## Conclusion

Au terme de notre analyse approfondie des données d'arrestation à Los Angeles, nous avons pu identifier plusieurs facteurs importants qui influencent la probabilité et la nature des arrestations. Parmi ces facteurs, le lieu du crime et l'heure se sont révélés être des indicateurs clés, mettant en lumière des modèles spécifiques de criminalité et d'activité policière à travers la ville. En outre, notre étude a mis en évidence le rôle significatif que jouent le niveau social et éducatif dans les tendances d'arrestation. 

Ces découvertes soulignent l'importance d'une approche multidimensionnelle dans l'analyse des données d'arrestation, qui prend en compte à la fois les aspects géographiques et socio-économiques. En identifiant les zones à haut risque et les heures critiques, les forces de l'ordre peuvent optimiser leur déploiement et leurs stratégies de prévention. Parallèlement, la corrélation entre le niveau d'éducation et les taux d'arrestation appelle à une réflexion plus profonde sur les politiques publiques et les initiatives éducatives comme moyens de prévention de la criminalité.

Ce projet met en évidence le potentiel de l'analyse des données pour éclairer et guider les décisions en matière de sécurité publique et de justice sociale. En continuant à explorer ces données avec des méthodes analytiques avancées, nous pouvons non seulement mieux comprendre les dynamiques actuelles, mais aussi anticiper et prévenir les futurs défis en matière de criminalité et d'application de la loi.



## Comment Exécuter le Projet

Pour installer les dépendances et exécuter ce notebook, suivez les étapes ci-dessous :

1. Clonez le dépôt : git clone https://github.com/firas-dridi/precognitionpolice.git
2. **Installez les dépendances nécessaires :**
3. **Lancez Jupyter Notebook :**

Naviguez vers le notebook dans l'interface utilisateur de Jupyter et exécutez les cellules pour voir l'analyse.

---

Nous sommes ouverts à toute collaboration ou questions concernant ce projet. N'hésitez pas à nous contacter ou à contribuer au projet.



