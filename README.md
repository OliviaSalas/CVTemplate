# Documentation technique

Version utilisée : HTML5/CSS3 – JS Vanilla





Mise en ligne du cv sur votre serveur Apache 2.0 : 

Ouvrir la console/terminale tapez soit :

Pour Debian et Ubuntu :

locate apache

Cherchez l'adresse du dossier par défaut (/var/www/index,html) d'apache puis transferez dans le dossier www la totalité des fichiers de votre cv, puis relancez votre serveur.


Mise en ligne sur votre serveur Nginx



Récupérer la configuration dans le dossier conf.d de votre serveur Nginx. Dans le fichier de configuration vous aurez l'adresse du root  par défaut ( /home/dev/www ) puis transferez dans le dossier www la totalité des fichiers de votre cv, puis relancez votre serveur.
