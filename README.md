# Projet de Prédiction des Troubles du Sommeil

# Aperçu
Ce projet implique l'analyse et la classification des métriques liées au sommeil et au système cardiovasculaire, ainsi que des facteurs de mode de vie, pour près de 400 personnes fictives. Le jeu de données est conçu pour répondre aux besoins d'une compagnie d'assurance santé, visant à identifier si un client potentiel est susceptible de souffrir d'un trouble du sommeil. L'entreprise souhaite utiliser ces informations pour déterminer la prime que le client devra payer.

# Objectif
L'objectif principal de ce projet est d'identifier automatiquement les troubles du sommeil à l'aide de techniques de classification basées sur l'apprentissage automatique.

# Solution du Problème
Pour atteindre l'objectif du projet, un classificateur sera construit pour prédire la présence d'un trouble du sommeil en fonction des différentes colonnes du jeu de données.

# Source des Données
Le jeu de données provient de [Kaggle] https://www.kaggle.com/datasets/uom190346a/sleep-health-and-lifestyle-dataset/

# Structure du Projet
- data.csv : Le fichier principal du jeu de données.
- prediction.ipynb : Jupyter Notebook contenant le code d'analyse des données.

# Informations sur le Jeu de Données
Le jeu de données contient les colonnes suivantes :

- ID de la personne
- Sexe
- Âge
- Profession
- Durée du sommeil : Nombre moyen d'heures de sommeil par jour
- Qualité du sommeil : Note subjective sur une échelle de 1 à 10
- Niveau d'activité physique : Nombre moyen de minutes d'activité physique par jour
- Niveau de stress : Note subjective sur une échelle de 1 à 10
- Catégorie IMC
- Pression artérielle : Indiquée sous la forme pression systolique sur pression diastolique
- Fréquence cardiaque : En battements par minute
- Nombre de pas quotidiens
- Trouble du sommeil : L'un des choix suivants : Aucun, Insomnie, Apnée du sommeil


# Workflow du Projet
1. Compréhension des Données :
- Charger les données et vérifier les premières lignes.
- Examiner les types de données et identifier les valeurs manquantes.

2. Analyse Exploratoire des Données (EDA) :
- Visualiser les relations entre les variables.
- Identifier les tendances et les corrélations.

3. Prétraitement des Données :
- Encoder les variables catégorielles.
- Explorer et transformer les caractéristiques au besoin.

4. Développement du Modèle :
- Diviser les données en ensembles d'entraînement et de test.
- Expérimenter avec différents algorithmes de classification (régression logistique, Ridge, SVM, Random Forest Classifier) avec validation croisée.

5. Évaluation du Modèle :
- Évaluer les performances des modèles (F1_score avec validation croisée et rapport de classification).
- Réglage fin des modèles.

6. Résumé Exécutif et Recommandations :
- Résumer les résultats et fournir des recommandations basées sur les prédictions du modèle.


# Instructions
1. Clonez le dépôt.
2. Explorez le jeu de données et suivez l'analyse dans le Jupyter Notebook fourni.
3. Exécutez le notebook pour comprendre le workflow du projet.
4. Contribuez à l'amélioration du modèle si vous le souhaitez.

N'hésitez pas à explorer, apprendre et contribuer au projet de classification des troubles du sommeil !










