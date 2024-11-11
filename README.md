Projet de Classification de Texte avec Quatre Modèles Différents
Ce dépôt contient deux notebooks dédiés à la classification de texte en utilisant quatre modèles différents : Naïve Bayes, SVM, BERT et Longformer.

Notebook 1: Préparation des Données et Visualisation
Description: Ce notebook est consacré à la concaténation de deux ensembles de données : 10_data et le dataset BBC. L'objectif est de fusionner ces données pour créer un ensemble de données plus large pour la classification de texte.

Problème Rencontré: Après la concaténation, il a été observé que les données résultantes étaient déséquilibrées. Cela signifie que certaines classes étaient surreprésentées tandis que d'autres étaient sous-représentées, ce qui peut affecter la performance des modèles de classification.

Environnement: Ce notebook a été exécuté localement sur Jupyter Notebook.

Notebook 2: Entraînement des Modèles avec Jeu de Données Équilibré
Description: Dans ce notebook, nous avons utilisé un jeu de données généré et équilibré pour entraîner les modèles de classification. Le notebook inclut également des visualisations pour comprendre la distribution des classes et les performances des modèles.

Modèles Entraînés:

Naïve Bayes
SVM (Support Vector Machine)
BERT (Bidirectional Encoder Representations from Transformers)
Longformer
Résultats: Les modèles ont été évalués, et il a été constaté que, bien que certains modèles atteignent une précision de 100%, ils ne souffrent pas de surapprentissage (overfitting) car ils maintiennent de bonnes performances sur des données non vues.

Environnement: Ce notebook a été exécuté sur Kaggle, ce qui permet d'utiliser des ressources computationnelles plus importantes, notamment pour l'entraînement des modèles basés sur les Transformers.
