Bonjour, bienvenue dans les explications de lancement de "1 image 1 mot" :


1- Vérifier que sur votre ordinateur il y a bien les librairies  de SDL2, SDL_Image, SDL_TTF ainsi que la commande gcc d'installer :  
    a. Si c'est le cas passer au point suivant  
    b. si ce n'est pas le cas alors il vous faudra installer c'est trois librairies et la commance gcc pour pouvoir continuer, rentrez les commandes suivantes dans un               terminal pour les installées :  
    - sudo apt-get install libsdl2-dev libsdl2-image-dev libsdl2-ttf-dev  
    - sudo apt-get instal build-essential

2- Si vous êtes arrivez ici c'est que vous êtes opérationnel pour pouvoir jouer à ce jeu alors placez vous simplement dans le dossier du Projet (double-clic gauche sur le dossier), puis si tout ce passe bien vous verrez apparaitre des dossiers, un Makefile et ce README

3- Maintenant il vous suffit simplement d'ouvrir un invite de commande (CMD) et de vous placez exactement au meme endroit dans le terminal grace à la commande : cd 1_image_1_mot

4- Ensuite vous devez rentrer la commande "make" dans votre terminal

5- Puis pour lancer le jeu il vous suffit de rentrer la commande "./bin/prog" puis suivre les indications que vous verrez à l'écran pour commencez à jouer ! 

(PS: Dans le jeu quand on parle des touches "1" et "2" ont parle du "1" qui est aussi "&" et du "2" qui est aussi "é")

Pour le mode 2v2: 
    Le joueur n°1, qui doit saisir le mot à faire deviner au joueur n°2, va pouvoir trouver la liste de tout les mots disponible dans assets puis dans le dossier Theme puis dans le fichier Mot.txt (le mot qu'il doit saisir coresspond au mot de la première colonne)

ATTENTION : 
    Quand on vous demande de rentrez un mot, il ne faut pas mettre :
        - les accents 
        - remplacer les apostrophes ("'"), les tirets des mots composés ("-") et les underscores ("_") par des espaces 
        - si dans le mot il y a des lettres comme "ç" mettre simplement la lettre à laquelle elle corespond de base (ex: ç devient c)
