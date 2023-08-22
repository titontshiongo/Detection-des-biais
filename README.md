# Détection-des-biais dans les tâches de classification avec les modèles Transformers (DistilBert)

Le jeux de données utilisé concerne l'analyse des sentiments contenant 20.000 tweets,constitué d’un ensemble de textes chacun étiquetés avec une catégorie pour indiquer le sentiment associé aux tweets. 
Les auteurs ont construit un ensemble de hashtags pour collecter un ensemble de données distinct de tweets anglais de l'API Twitter appartenant à huit émotions de base, dont la colère, l'anticipation, le dégoût, la peur, la joie, la tristesse, la surprise et la confiance. Les données ont déjà été prétraitées sur la base de l’approche décrite dans leur article (CARER: Contextualized Affect Representations for Emotion Recognition(https://aclanthology.org/D18-1404/))

Nous avons testé une approche exploratoire combinant l'utilisation des méthodes d'analyse semi-supervisée,de réduction de dimensionnalité avec Auto encodeur pour la recherhe de la variable sensible dans l'espace latent, conduisant à une possible détection de variable cachée susceptible de produire du biais dans nos données textes.


Les différents notebook traitent de la recherche de biais inconnus dans les tâches de classification multiclasse de texte.
Le premier concerne la détéction de la variable sensible à partir des clusters analysés en mettant l'humain dans la boucle.
Le deuxième notebook traite l'entraînement du modèle DistilBert avec la variable sensible détectée pour identifier un éventuel comportement déviant du modèle.
