# Spotify_API_DB:
#Presentation du projet :

  Ce projet consiste a construire une base de données relationnelle et de la remplir avec des données provenant d'une API.
  Pour ce faire Nous devons :
  1) faire le choix d'une API.
  2) Faire le dictionnaire de données decrivant les attributs necessaires pour stocker les données.
  3) Contruire un schéma de données pouvant stocker les données de manieres structuré.
  4) Créer une base de données avec la structure definit.
  5) Remplir la base de données en ce servant des données parvenant de l'API.
  
 # 1) Choix de l'API:
   Nous avons fait le choix d'utliser l'API de SPOTIFY qui est basé sur une architecture REST.
   
   Elles possede un certin nombre de points de terminaison qui renvoient des métadonnées sous fome d'objet JSON sur les artistes musicaux, les albums et les pistes. directement à partir du catalogue de données Spotify.
   
   Toutes les demandes adressées à l'API Web nécessitent une authentification. Ceci est réalisé en envoyant un jeton d'accès OAuth valide dans l'en-tête de la demande.
   
   La première chose a faire est d'aller sur la page des développeurs Spotify et de configurer un compte développeur et une application.
    
   C'est une étape importante, car vous aurez besoin de votre ID client et de votre secret client pour construire le token et accéder à leurs points de terminaison.
   https://developer.spotify.com/dashboard/
 
 # 2) Faire le dictionnaire de données:
  Nous avons etudier la reponse de l'API et nous en avons deduit le dictionnaire de données suivant:
  https://docs.google.com/spreadsheets/d/1PYIsKgsFiI9L5YfAqMpZ4u77125iybxKHr3nyohcoro/edit?usp=sharing
  
# 3) Contruire un schéma de données:
  Nous avons deduis les relations entre les tables a partir du dictionnaire et construit le diagramme suivant: 
  
  ![Diagramme entité-association Spotify_DB](https://user-images.githubusercontent.com/31952379/103778318-5df73100-5032-11eb-8d37-5945933165f8.jpeg)
  
# 4) database:

<img width="282" alt="diagramme_sql_server" src="https://user-images.githubusercontent.com/31952379/103779351-ec1fe700-5033-11eb-980a-1dee6d760492.png">



# 5) Résultats aprés remplissage de la base avec l'API sur SQL server:

<img width="449" alt="affichage_tables_remplis" src="https://user-images.githubusercontent.com/31952379/103779202-b2e77700-5033-11eb-8bbf-b73b6d05765a.png">






  

  

    
   
   
