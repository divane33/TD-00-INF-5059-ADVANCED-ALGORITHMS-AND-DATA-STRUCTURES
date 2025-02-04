# RAPPORT DU TD 00 (INF 5059): ADVANCED ALGORITHMS AND DATA STRUCTURES

## Description

Il s'agit d'une application web simple qui permet aux utilisateurs d'exécuter directement différents exercices d'algorithmes dans leur navigateur. Les algorithmes suivants sont implémentés :

1. **Recherche Binaire**
2. **Parcours de Graphes (BFS & DFS)**
3. **Problème du Sac à Dos 0/1 (Programmation Dynamique)**
4. **Fusion d'Intervalles**
5. **Somme Maximale de Sous-Tableau (Algorithme de Kadane)**

Chaque exercice permet à l'utilisateur de saisir des données pertinentes, d'exécuter l'algorithme et de voir instantanément le résultat.

## Fonctionnalités

- **Recherche Binaire** : Étant donné un tableau trié et une valeur cible, trouvez la cible (c'est-à-dire la valeur à rechercher) dans le tableau en utilisant la recherche binaire.
- **Parcours de Graphes** : Il s'agit ici d'effectuer une recherche en largeur (BFS) ou une recherche en profondeur (DFS) sur un graphe défini par des arêtes.
- **Problème du Sac à Dos** : Il s'agit ici de résoudre le problème du sac à dos 0/1 en utilisant la programmation dynamique pour maximiser la valeur des éléments sélectionnés sans dépasser une capacité spécifiée.
- **Fusion d'Intervalles** : Il s'agit ici de fusionner les intervalles qui se chevauchent en un nombre minimal d'intervalles.
- **Somme Maximale de Sous-Tableau** : Il s'agit ici d'utiliser l'algorithme de Kadane pour trouver la somme maximale d'un sous-tableau contigu dans un tableau donné.

## Utilisation

1. Ouvrez le fichier `tdd0.html` dans n'importe quel navigateur web moderne.
2. Sélectionnez l'exercice souhaité parmi les boutons en haut de la page.
3. Saisissez les entrées requises pour l'exercice sélectionné.
4. Cliquez sur le bouton "Exécuter" pour exécuter l'algorithme et voir la sortie en dessous.

## Format des Entrées

- **Recherche Binaire** : Entrez un tableau trié (par exemple, `1,2,3,4`) et la valeur cible (valeur à rechercher) (par exemple 3).
- **Parcours de Graphes** : Entrez les arêtes du graphe au format `A-B, B-C, C-D` et le nœud de départ (par exemple `A`).
- **Sac à Dos** : Entrez les éléments sous le format `valeur,poids` (par exemple, `60,10;100,20`) et spécifiez la capacité du sac à dos.
- **Fusion d'Intervalles** : Entrez les intervalles sous le format `début-fin` (par exemple, `1-3,2-4,5-7`).
- **Somme Maximale de Sous-Tableau** : Entrez le tableau d'entiers (par exemple, `-2,1,-3,4`).

## Exemple de Sortie

- **Recherche Binaire** : Si la cible (valeur recherchée) est trouvée, le résultat sera l'index de la cible. Sinon, il renverra `-1`.
- **Parcours de Graphes** : Le résultat affichera les nœuds visités dans l'ordre du BFS ou du DFS.
- **Sac à Dos** : Le résultat sera la valeur maximale qui peut être obtenue avec la capacité donnée.
- **Fusion d'Intervalles** : Le résultat affichera les intervalles fusionnés sous forme de paires début-fin.
- **Somme Maximale de Sous-Tableau** : Le résultat affichera la somme maximale d'un sous-tableau contigu.

## Installation

Aucune installation n'est requise. Il suffit d'ouvrir le fichier `tdd0.html` dans un navigateur web.

## Technologies Utilisées

- HTML5
- JavaScript
- CSS

