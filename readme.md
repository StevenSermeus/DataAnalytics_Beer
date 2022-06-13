# BI

Ces données viennent de Kaggle et ont été créé le 2 octobre 2018. Il y a environ 1 500 000 lignes
contenant pour chacune des critiques pour les bières servies dans des brasseries. Les brasseries
reçoivent donc des notes sur la qualité de leurs bières.
Il y a 13 colonnes dans ce fichier de données. En voici la liste :
• Brewery_id : l’identifiant de la brasserie
• Brewery_name : le nom de la brasserie
• Review_time : la date où a eu lieu la critique
• Revieuw_overall : la note générale de la critique
• Review_aroma : la note de l’arome
• Review_appearance : la note de l’apparence de la bière
• Review_profilename : le nom de profil de la personne qui fait la critique
• Beer_style : le type de bière
• review_palate : la note du palais de la bière
• review_taste : la note du gout
• beer_name : le nom de la bière
• beer_abv : alcohol by volume, le taux d’alcool par volume
• beer_beerid : l’id de la bière
On a commencé la fouille de données en vérifiant les colonnes qui possèdent le plus de valeurs
nulles. La colonne brewery_name possède 15 valeurs nulles, review_profilename en a 348. La
beer_abv possède la grosse somme de 67785 valeurs nulles. 

# Utilisation

Déziper le fichier csv avant de lancer le programme 