# Ririgram

Ceci est une version aléatoire du jeux Nonogram


# Installation 

cloner le repo
dans un terminal :
```bash
composer install
yarn install
```
(yarn install --no-bin-links si sous vagrant)

Pour créer la BDD :<br/>
ouvrir le fichier \src\DatabaseCreation\DatabaseCreation.php<br/>
Remplir la partie 'Configuration de la BDD avec les infos désirées<br/>
Renommer le fichier .env.sample en .env et le remplir avec les valeurs concernant dbUser et non root<br/>
Dans un terminal, se placer dans \src\DatabaseCreation\ puis taper :
```bash
php DatabaseCreation.php
```

Pour finir
faire pointer apache vers le dossier public

