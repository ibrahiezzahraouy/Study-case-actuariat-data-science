# Study-case-actuariat-data-science

## But de l’Exercice
Le principe général de l’exercice est semblable à une compétition de type « Kaggle » : l’objectif est de construire un modèle prédictif à partir d’un jeu données.
Nous vous proposons d’estimer le bénéfice net annuel attendu par client sur un contrat d’assurance automobile en fonction des caractéristiques du client.

## Consignes
Nous avons 2 fichiers csv:
1. Labeled_dataset.csv contient 1 ligne de noms de variables, et 1 000 lignes de données. Chacune de ces 1 000 lignes contient :1 index de 0 à 999, représentant de façon unique chaque client ;
  - 12 variables (age, salaire, coefficient bonus-malus…) caractéristiques du client ;
  - 1 « label cible », benefice, indiquant le bénéfice net annuel réalisé pour ce client ;
3. Scoring_dataset.csv contient 1 ligne de noms de variables, et 300 lignes de données. Chacune de ces lignes contient :
  - 1 index, de 1000 à 1299 ;
  - 12 variables (age, salaire, coefficient bonus-malus…) ;

Nous devons utiliser les données de labeled_dataset pour construire un modèle prédictif. Nous pourrons ensuite appliquer ce modèle sur les données de scoring_dataset afin de générer vos prédictions.
La métrique utilisée pour comparer vos résultats avec les réponses sera le score RMSE (Root Mean Squared Error).

## NOTE IMPORTANTE CONCERNANT LE JEU DE DONNEES :
Le dataset pour ce test a été intégralement généré. Une connotation métier en lien avec l’assurance lui a été donnée, mais toutes les données sont purement fictives.
Plus spécifiquement, les âges, salaires, catégories socio-professionnelles, etc… ne sont pas représentatifs des clients ou d’une quelconque population. Le lien entre les caractéristiques d’un client et le bénéfice réalisé est également fictif. La précision atteignable en termes de performances du modèle n’est pas non plus nécessairement réaliste.

## Technologie
Les technologies utilisées sont disponibles en open-source. Nous utilisons Python comme langage de programmation 

## Livrable
1. Un fichier csv contenant les prédictions : ce fichier doit être composé de 300 lignes, chacune reprenant les index de scoring_dataset.csv ainsi que votre prédiction pour cet index.
2. Le code ayant permis la génération du modèle et les instructions permettant d’exécuter le code le cas échéant.
3. Une présentation de la méthodologie mise en place ainsi que des résultats obtenus.
