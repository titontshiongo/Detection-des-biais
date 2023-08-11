# Détection-des-biais dans les tâches de classification avec les modèles Transformers (DistilBert)

Le jeux de données utilisé concerne l'analyse des sentiments contenant 20.000 tweets,constitué d’un ensemble de textes chacun étiquetés avec une catégorie pour indiquer le sentiment associé aux tweets. 
Nous avons testé une approche exploratoire combinant l'utilisation des méthodes d'analyse semi-supervisée,de réduction de dimensionnalité avec Auto encodeur pour la recherhe de la variable sensible dans l'espace latent, conduisant à une possible détection de variable cachée susceptible de produire du biais dans nos données textes.

Les différents notebook traitent de la recherche de biais inconnus dans les tâches de classification multiclasse de texte.
Le premier notebook traite de l'analyse exploratoire des données textes.
Le deuxième concerne la détéction de la variable sensible à partir des clusters analysés en mettant l'humain dans la boucle.
Le troisième notebook traite l'entraînement du modèle DistilBert avec la variable sensible détectée pour identifier un éventuel comportement déviant du modèle.
