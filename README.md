# Installation du projet
1. Téléchargez ou clonez le dépôt
2. Depuis un terminal ouert dans le dossier du projet, lancer la commande : `sudo docker-compose up --build`
3. Dans docker Desktop sélectionner le container Symfony
4. Lancer un shell pour se retrouver dans le container
5. Dans le terminal executer
```composer require symfony/flex --no-interaction```
6. Puis executer
```composer install --prefer-dist --no-progress --no-interaction```
7. Enfin la dernière commande
```php -S 0.0.0.0:8081 -t public/```
3. Ouvrez le site depuis la page http://localhost:8080 
