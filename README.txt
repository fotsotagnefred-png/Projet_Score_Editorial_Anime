Projet Final : Score Éditorial Anime

   Description du Projet

Ce projet a pour objectif d'identifier rapidement des animés à forte valeur éditoriale pour une plateforme de streaming, en se basant sur des données limitées. Nous avons développé un score composite pour évaluer la qualité et la régularité des animes, permettant ainsi de prendre des décisions éditoriales éclairées.

  Contexte Métier

Une plateforme de streaming souhaite mettre en avant des animes de haute qualité sans attendre des mois de données d'engagement utilisateur. Les contraintes incluent un large catalogue, des ressources éditoriales limitées et le risque de promouvoir des animes surcotés ou irréguliers.

   Données Utilisées

Le projet utilise le fichier animes.csv contenant des informations sur divers animes, notamment :
- Titre, Genre, Studio
- Nombre d'épisodes
- Notes globales, notes du meilleur et du pire épisode
- Commentaires éditoriaux sur différents arcs narratifs

   Méthodologie

1.  Data Cleaning & EDA (Exploratory Data Analysis):
       Nettoyage des données (gestion des valeurs manquantes, conversion des types).
       Analyse des distributions et corrélations.
2.    Construction d'un Score Métier:
     Création de nouvelles métriques : Ecart (différence entre meilleure et pire note d'épisode) et Regularite (basée sur l'écart).
      Développement d'un  Score_Qualitecomposite combinant la note globale et la régularité.
3.   Validation des Hypothèses:
     Comparaison du nouveau score avec la note brute.
    Analyse des top animes selon le nouveau score.
4.  Segmentation Éditoriale:
       Classification des animes en catégories comme Chef-d'œuvre , Très bon mais inégal , Culte mais risqué , À éviter basée sur le `Score_Qualité la Regularite

      Livrables

   Notebook Jupyter(Projet_Score_Editorial_Anime.ipynb ) : Contient tout le code, les analyses et les visualisations.
   Dataset Nettoyé ( animes_propre.csv ): Version nettoyée et enrichie du dataset original.
  Rapport EDA : Intégré au Notebook Jupyter, avec statistiques et insights clés. Visualisations: Graphiques générés dans le Notebook pour illustrer les analyses.
 Classification : Résultats de la segmentation éditoriale.
Documentation (README.md): Ce fichier.
Présentation: Slides synthétiques (voir ci-dessous).
Vidéo Storytelling: Courte vidéo de présentation (voir ci-dessous).

Comment Exécuter le Projet

1.  Avoir Python, Pandas, Matplotlib et Seaborn installés via Anaconda 
2.  Placez le fichier animes.csv et le Notebook Projet_Score_Editorial_Anime.ipynb dans le même répertoire.
3.  Ouvrez le Notebook avec Jupyter et exécutez les cellules séquentiellement.

Auteur

FRED FOTSO