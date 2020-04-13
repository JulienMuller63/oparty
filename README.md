# o'Party

Site vitrine créé à la fin de ma formation O'Clock, à la suite de la spé Wordpress.

![screenshot](C:\laragon\www\oparty\content\themes\oparty\screenshot.jpg)

## Liste des étapes:

- Se déplacer dans ```\content\themes\oparty```
  
  - `npm install`
  - `npm run build:prod`
  
- Revenir à la base du répertoire

- Installation de nos dépendances avec composer `composer install`

- Création de la BDD

- Importer la BBD 

- Modifier les URL dans la BDD

  - Table `oparty_options`
    - siteurl : http://__CHEMIN_DE_MON_SITE/wp
    - home :  http://__CHEMIN_DE_MON_SITE

- Création du fichier `wp-config.php` à partir du fichier `wp-config-sample.php`
  - Renseigner les informations de connexion à la BDD
  - Renseigner les clés de salage [URL pratique](https://api.wordpress.org/secret-key/1.1/salt/)
  - Renseigner la constante `WP_CONTENT_URL` avec l'url de notre projet (en local)
  - Choisir, en décommentant, la constante d'environement qui nous convient.
  
  