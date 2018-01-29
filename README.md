![GitHub Logo](logo/logoconcepts.png)
----------
> "Tu vas devoir donc *créer un repo GitHub* avec un README qui explique tous ces concepts, en **_vulgarisant un maximum._**"
>
> -- *Félix Gaudé*

## Concepts:
 +  _Site statique / dynamique_
 + _MVC_
 + _Routes_
 + _Databases_
 + _GET / POST_
 + _Migration_
 + _Relations entre modèles des BDD_
 + _CRUD_
------
### -La différence entre un site statique :zzz: et un site dynamique :running: ?
Un site statique, [comme celui-ci](http://motherfuckingwebsite.com/), est écrit exclusivement en HTML/CSS, et pourrait en théorie être imprimé et lu sur papier sans perdre de valeur (on imprime chaque page du site et on perd seulement les liens).
  
Un site dynamique, lui, a comme principal objectif d'être intéractif, il contient donc des scripts et permet à ses différentes pages de s'échanger des informations.

### -Que signifie l'acronyme M.V.C. ?
Model, View, Controller:
Le 'model' manipule des données de la database, Le 'view' affiche en HTML/CSS ces mêmes données accompagnées de formatage, et le 'controller', comme son nom l'indique, controle toutes les actions de notre site, que ce soit l'appel au view pour afficher quelque chose, ou l'appel au model pour recuperer des valeurs dans la database.

### -Les routes, comment ça marche :car: ?
Les routes sont les liens entre les url et les appels aux actions de controllers. Elles se trouvent dans config/routes.rb

### -Les bases de données ou 'databases' :cloud:
Les bases de données regroupent des informations que l'on peut extraire et/ou insérer (par exemple 'utilisateur' avec login=jules et password=mot2passe). Les modèles sont une architecture particulière et standardisée sur rails d'une base de données.

### -GET & POST :email:
GET et POST sont des méthodes qui permettent respectivement de récupérer des informations depuis le serveur et d'envoyer des informations au serveur.

### -La migration :arrow_up:
Les migrations, ce sont comme des versions de ta database et en même temps ce qui te permettent d'en modifier le contenu.

### -Les modèles et leurs relations dans la base de données :blue_book:
Les relations entre modèles sont définis sur rails par l'ActiveRecord qui nous permet de déclarer des liens de parenté et des heritages de methodes entre modèles. On peut par exemple déclarer que certaines reviews sont liées à une certaine instance de la classe Produit, elles ont donc bien une relation parent/enfant.

### -C.R.U.D. 
Create, Read, Update et Destroy/Delete. Ce sont les methodes(actions) de base possibles sur chaque controller qui sont heritées de l'ActiveRecord dont on parlait un peu plus haut.

------
### Merci de m'avoir lu ! :cat:
