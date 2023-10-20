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

le notebook est un guide complet sur l'analyse de données et la création d'un modèle de prédiction pour les données d'assurance. Voici un résumé des principales étapes effectuées dans le notebook :

### Données :

1.1. Importation des données à partir de deux fichiers CSV (labeled_dataset.csv et scoring_dataset.csv) situés dans le répertoire Google Drive.

1.2. Description des données, qui comprennent des informations sur les différentes colonnes et leurs significations.

1.3. Évaluation de la qualité des données, y compris la détection et la correction des erreurs et des valeurs manquantes dans le jeu de données.

### Statistiques descriptives :

2.1. Calcul de la corrélation entre les différentes variables du jeu de données, ce qui permet de comprendre les relations entre elles.

2.2. Visualisation des distributions des variables numériques et de leur relation avec la variable cible.

2.3. Visualisation des distributions de la variable cible par rapport aux variables catégorielles.

### Modèle :

3.1. Encodage des données catégorielles et séparation des données en ensembles d'entraînement et de test.

3.2. Utilisation d'une stratification pour la séparation des données afin de préserver la distribution de la variable cible.

3.3. Réglage des hyperparamètres du modèle à l'aide de l'optimisation bayésienne et validation des hyperparamètres.

3.4. Entraînement du modèle final à l'aide des hyperparamètres optimisés et évaluation de la capacité de généralisation du modèle.

3.5. Analyse de l'explicabilité et de l'importance des caractéristiques à l'aide des valeurs SHAP.


### Prédiction :

4.1. Traitement des données de soumission pour s'assurer qu'elles sont prêtes à être utilisées par le modèle.

4.2. Imputation des valeurs manquantes pour certaines variables en se basant sur des informations provenant de l'ensemble d'entraînement.

Le notebook a couvert de nombreuses étapes essentielles, de l'exploration des données à la création et à l'évaluation du modèle.





