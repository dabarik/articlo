# articlo

Plateforme où l'on retrouve des articles qui appartiennent à certaines catégories.

J'ai utilisé Bootstrap pour l'interface graphique et j'ai utilisé la méthode CRUD pour gérer les articles, catégories, directement donné par la commande suivante : 

php bin/console make:crud

Pour le projet, j'ai eu un peu de mal à trouver comment les 2 entités pouvaient se parler entre elles mais au final, j'ai trouvé grâce à votre mail qui m'a bien
aidé. A part cela, c'était plûtot facile d'utilisation notamment grâce au framework Symfony.

Ma version de PHP : PHP 7.3.24

Commandes à faire pour la base de données : 

composer create-project symfony/website-skeleton NOM ^4.4.99
cd NOM/
composer require symfony/web-server-bundle --dev
php bin/console server:run

XU THIERRY
