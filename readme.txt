Composer install
Faire un compier coller du .env.sample changer les Mots de passes / login
make up
Dans web/sites/default créer un dossier files
Dans web/sites/default/files créer un dossier translations
Créer le fichier settings.php en utilisant le template default.settings.php à mettre dans web/site/default
Make shell puis taper les commandes "chmod -R 777 web/sites/default/files/" & "chmod -R 777 web/sites/default/settings.php"
Remplir dans le setting.php la partie $databases['default']['default'] avec les infos du .env (mot de passe user ect..)
Aller sur l'installeur drupal http://drupal.docker.localhost:8000/core/install.php
