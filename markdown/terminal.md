# Documentation terminal

Version: V0
Type: Technique
Date de création: 24 juillet 2023 00:11
Dernière modification: 14 décembre 2023 15:29

# Notes

Les arguments d'une commande sont des "options" que l'on ajoute à la commande de base pour adapter son comportement, elles sont précédées d'un ou deux tiret(s) exemple :

`ls` affiche la liste des fichiers du répertoire courant

`ls -l` même chose mais la liste est à la verticale

`ls -la` même chose et le `a` indique d’afficher les fichiers commençant par un point

`ls --help` décrit l'usage de commande

# Commandes

| pwd | Affiche le chemin du répertoire courant |
| --- | --- |
| ls | Afficher horizontalement le contenu du répertoire courant |
| ls -l | Afficher verticalement le contenu du répertoire courant |
| cd ou cd ~ | Retour au répertoire racine de l’utilisateur |
| cd ../ | Retour au répertoire parent ( précédent ) |
| cd mon_dossier | Accéder au répertoire “mon_dossier” |
| touch mon_fichier.txt | Créer un fichier “mon_fichier.txt” dans le répertoire courant |
| mkdir mon_dossier | Créer un dossier “mon_dossier” dans le répertoire courant |
| cd mon_dossier && ls -l | Le symbole && permet d’exécuter des commandes à la suite, ici on accède au répertoire “mon_dossier” puis afficher verticalement le contenu du répertoire |
| cp mon_fichier.txt mon_fichier_copie.txt
cp -r mon_dossier mon_dossier_copie | Copie / colle un fichier ou un répertoire ( et son contenu, avec l’arguement -r ). Se compose de la manière suivante : cp <source> <cible> |
| mv mon_fichier.txt mon_fichier_deplace.txt
mv mon_dossier mon_dossier_deplace
mv ancien_nom.txt nouveau_nom.txt | Coupe / colle un fichier ou un répertoire ( et son contenu ). Se compose de la manière suivante : mv <source> <cible>
Il peut aussi être utilisé pour renommer un fichier |
| rm rm -r rm -rf | Supprimer un fichier ou un répertoire ( et son contenu, avec argument -r ) |
| sudo <votre_commande> | Exécuter des commandes en tant qu’administrateur ( attention ) |
| cat | Afficher le contenu d’un fichier dans le terminal |
| cat presentation.txt > nouveau.txt | Copie le contenu du fichier presentation.txt dans le fichier nouveau.txt , cela écrasera le contenu du fichier nouveau.txt |