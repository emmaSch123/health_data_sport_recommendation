# health_data_sport_recommendation

Objectif : Analyser et filtrer la base de données du réseau social Endomondo, utilisé pour le suivi des performances chez les sportifs de tout types. Le projet vise à identifier les critères pour trier ou filtrer les données sportives, et à choisir des algorithmes optimaux pour l'implémentation et l'amélioration de la précision de nos résultats. Ce modèle d'apprentissage automatique pourrait par exemple servir à des coachs ou à des médecins pour surveiller la fréquence cardiaque de sportifs de haut niveau ou de malades.

Observations : Transformation des données brutes issues de la base de données en un format exploitable pour l'analyse, en se concentrant sur les variables clés liées à la performance sportive.

Les valeurs ‘durée’ et ‘distance’ sont très corrélées donc le modèle d'apprentissage automatique pourra utiliser ces données pour faire des prédictions plus facilement.

Résultats : Les algorithmes 'Random Forest Classifier', 'KNN Classifier', 'SVM Classifier' et 'LightGBM' ont été testés. LightGBM a montré les meilleures performances en termes de MSE, MAE et RMSE.
