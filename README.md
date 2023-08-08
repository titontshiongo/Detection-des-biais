# Détection-des-biais dans les tâches de classification avec les modèles Transformers

Le jeux de données utilisé concerne l'analyse des sentiments contenant 20.000 tweets,constitué d’un ensemble de textes chacun étiquetés avec une catégorie pour indiquer le sentiment associé aux tweets. L'objectif étant d'utiliser les méthodes l'analyse semi-supervisée,la réduction de dimensionnalité avec Auto encodeur pour la recherhe de la varaible sensible conduisant à la détection des biais dans le cadre du langage naturel.

Les différents notebook traitent de la recherche de biais inconnus dans les tâches de classification de texte.
Le premier notebook traite de l'analyse exploratoire des données textes.
Le Deuxième concerne la détéction de la variable sensible à partir des clusters analysés en mettant l'humain dans la boucle.
Le Troisième notebook traite l'entraînement du modèle Transformers avec la variable sensible détectée.
