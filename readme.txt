Présentation du projet activité GIT pour OCR

par la console git Bash

création du répertoire du projet avec mkdir nom du repertoire

création du fichier readme.txt avec git touch

initialisation du repo git avec git init

création d'un fichier php avec touch index.php

ouverture du fichier avec notepad++ et modification avec la ligne <?php echo "Hello world"; ?>

enregistrement

commit sur la console
on verifie d'abord avec git status
2 fichiers apparaissent en rouge car non ajoutés à l'index

on les passe à l'index par git add nom du fichier

on passe donc au commit de ces deux fichiers par git commit -am "Ajout des deux fichiers dans le commit"

