# 📊 Analyse des Performances Académiques des Étudiants (Projet R)

Ce projet a été réalisé dans le cadre d'une étude statistique et prédictive des facteurs influençant la réussite scolaire. L'intégralité du projet suit le Data Science Workflow professionnel.

# 🎯 Objectif du Projet

L'objectif est de comprendre l'influence des variables socio-éducatives (genre, type de repas, cours de préparation) sur les scores de Mathématiques, de Lecture et d'Écriture.

# 🛠️ Méthodologie : Le Workflow

Le projet est structuré en quatre étapes clés, conformément aux standards de la Data Science :

**1. Data Access (Importation)**

Importation du jeu de données "Students Performance" depuis Kaggle.

Utilisation de tidyverse et read_delim pour une lecture structurée.

**2. Data Pre-Processing (Nettoyage)**

Nettoyage des noms de colonnes avec janitor.

Traitement des données manquantes et conversion des types.

Création de variables binaires (Encoding) pour le modèle XGBoost.
**3. Extract Insights (Analyse & Modélisation)**

Cette étape itérative comprend :

 **Analyse Exploratoire :** Statistiques descriptives et visualisation de la distribution(Histogrammes & Densité).

Tests Statistiques :

Test de normalité de Shapiro-Wilk et comparaison de groupes via le Test t de Student.

**Modélisation Classique :** Régression linéaire simple pour corréler la lecture et l'écriture.

**Machine Learning :** Utilisation de XGBoost pour déterminer l'importance des variables (Feature Importance).

**4. Produce Insight (Conclusions)**
   
 Synthèse des résultats via des graphiques ggplot2.

 Interprétation des facteurs clés de succès.
 
# 📈 Résultats Majeurs

**L'effet Préparation :** Les étudiants ayant complété le cours de préparation réussissent significativement mieux dans toutes les matières.

**Interdépendance :** Une corrélation très forte ($R^2$ élevé) existe entre les capacités de lecture et d'écriture.

**Prédictions XGBoost :** Les scores littéraires s'avèrent être les meilleurs prédicteurs de la note de mathématiques, soulignant l'importance de la compréhension d'énoncé.

# 📂 Contenu du Dépôt

**Analyse_Performance.ipynb :** Le notebook complet (Colab) contenant le code R, les explications et les graphiques.

**StudentsPerformance.csv :** Le jeu de données utilisé pour l'étude.

**README.md :** Présentation du projet (ce fichier).
