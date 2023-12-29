# health_data_sport_recommendation

Objectif : Mise en oeuvre d’un système de recommandation qui permet de prédire les meilleures activités sportives à partir de la base de données d’un réseau social appelé
Endomondo. L’application possède de multiples sources de données tels que des capteurs présents dans le téléphone de l’utilisateur, des capteurs de température et d’humidité, ou des capteurs de pouls.

Traitement et Analyse de la donnée :
• Corrélations entre les valeurs ‘durée’ et ‘distance’ → le modèle d'apprentissage automatique pourra utiliser ces données pour ses prédictions.

• Création d’une nouvelle colonne ‘duration’ qui prend, pour chaque ligne, la différence entre le dernier timestamp et le premier timestamp afin d’établir la durée en secondes pour chaque activité.

Résultats : Les algorithmes 'Random Forest Classifier', 'KNN Classifier', 'SVM Classifier' et 'LightGBM' ont été testés. LightGBM a montré les meilleures performances en termes de MSE, MAE et RMSE pour une meilleure prédiction d’activités sportives à partir de la base de données d’Endomondo
