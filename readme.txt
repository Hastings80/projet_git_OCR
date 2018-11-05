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

on passe donc au commit de ces deux fichiers par git commit -am "Ajout des deux fichiers dans le commit du projet git"

on créé un autre fichier nommé page.php afin d'avoir deux autres fichiers s'ajoutant à readme.txt par touch page.php

en faisant git status on voit que ce fichier n'est pas à l'index
on le passe par git add page.php

on fait une modification dans ce fichier en ajoutant la ligne  <?php namespace Mapage; echo "ceci est une page"; ?>

on page sur le fichier index.php afin de modification la phrase affichée "Hello my world"
on commit avec la git commit -am "modification de la phrase en hello my world" (on met -a car le fichier à déjà été ajouté à l'index)

Afin de faire plusieurs commit on modifie les deux fichiers (ajout, modif, supp de ligne de code)

on commit et on verifie qu'il y a bien au moins 4 commit avec git log

On enregistrer ce fichier readme.txt pour préparer l'envoi de tout cela :)
et on fait le dernier commit 

On prépare l'envoi sur le repo GITHUB avec
git remote add origin https://github.com/Hastings80/projet_git_OCR.git
git push -u origin master