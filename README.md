 python-data-cleaner
  script pour nettoyer des données (Python & Pandas)

Un script d'automatisation conçu pour nettoyer et préparer des données clients (CSV).
Ce projet résout un problème courant en entreprise .Les bases de données  qui contiennent des erreurs de saisie, des doublons ou des informations manquantes. Grâce à la bibliothèque Pandas, ce script transforme un fichier brut inexploitable en un dataset propre prêt pour l'analyse.

Problématiques résolues
 Le script traite automatiquement les erreurs suivantes dans un fichier CSV :
  - Doublons : Identification et suppression des lignes identiques.
  - Erreurs de type : Conversion des âges écrits en lettres (ex: "vingt") en chiffres.
  - Valeurs manquantes (Imputation) : Pour l'âge : Remplacement des cases vides par la moyenne statistique du groupe.
  -Pour la ville  Attribution d'une valeur par défaut ("Inconnue").
 
Technologies utilisées
  Python
  la blibliotheque Pandas Pour la manipulation de données à haute performance.
  blibliotheque NumPy  Pour la gestion des valeurs nulles.
