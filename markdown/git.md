# Documentation Git

Version: V0
Type: Technique
Date de création: 24 juillet 2023 00:12
Dernière modification: 14 décembre 2023 15:26

### Liens

---

🔗 [Tutoriel installation Git](https://phoenixnap.com/kb/how-to-install-git-on-ubuntu)

🔗 [Markdown pour créer son README.md](https://www.markdownguide.org/cheat-sheet/)

### Mettre à jour APT Ubuntu

```bash
sudo apt update # télécharge les mises à jours des paquets
sudo apt upgrade # installe les mises à jours téléchargées
```

**Puis installer Git sur votre machin**

```bash
sudo apt install git # installer Git
git --version # vérifier si l'installation est ok + donne le n° de version installé
```

**Puis configurer votre utilisateur Git**

```bash
git config --global [user.name](http://user.name) "votre nom" # enregistre le nom d’utilisateur que vous souhaitez utiliser pour vos commit
git config --global [user.email](http://user.email) "votre adresse email" # enregistre l’adresse email que vous souhaitez utiliser pour vos commit
git config --global init.defaultBranch master
```

### Git SSH

Créer une clé SSH

```bash
cd ~/.ssh
ssh-keygen -o -t rsa -C "email@example.com"
```

### Procédure pour lier mon répertoire local à Github (1er push)

```bash
git init # j'initialise Git dans mon projet
git remote add origin <adresse_ssh_de_votre_projet> # créer le lien entre votre projet local et celui créé sur Github
git add . # ajouter tous mes fichiers au suivi de fichier
git commit -m "mon message de commit" # créer un comit, un "point de sauvegarde"
git push --set-upstream origin master # pour le premier push
```

### Procédure pour pousser mon code sur Github (pas 1 push)

```bash
git add <nom_du_fichier> # ou git add . si vous voulez ajouter tous les fichiers
git commit -m "mon message de commit"
git push
```

### Procédure pour travailler sur une branche

```jsx
git branch <nom_de_votre_branche> # Créer votre branche
git checkout <nom_de_votre_branche> # Vous bascule sur votre branche
```

### Commandes Git

| git init | Créer un nouveau repository Git dans le répertoire courant |
| --- | --- |
| git clone <url-du-repo> | Télécharge un projet et son historique |
| git fetch | Télécharge toutes les branches distantes en locale |
| git log | Liste l’historique de la branche courante |
| git status | Liste les fichiers modifiés sur la branche courante |
| git branch | Liste les branches locales |
| git branch <nom-de-la-branche> | Créer une branche locale  |
| git checkout <nom-de-la-branche> | Bascule sur la branche locale spécifiée |
| git checkout -b <nom-de-la-branche> | Créer une branche locale et bascule sur cette branche |
| git branch -d <nom-de-la-branche> | Supprime la branche locale spécifiée |
| git add <nom-du-fichier-ou-dossier> | Ajoute le fichier / dossier modifié au commit en cours |
| git add . | Ajoute tous les fichiers / dossiers modifiés au commit en cours |
| git commit -m "votre message" | Créer un commit et ajoute le message lié à celui-ci |
| git push | Pousse le / les commit(s) sur la branche distante si elle est existe |
| git push -u origin <votre-branch> | Créer la branche distante et pousse le / les commit(s) sur celle-ci |
| git pull | Met à jour la branche locale avec sa version distante |
| git rm <-rf> --cached <votre-fichier-ou-dossier> | Supprime le fichier / dossier du suivis de l’historique |
| git merge <branche-a-merger> | Fusionne la branche sélectionnée avec la branche courante |
| git stash . | Met de coter le travail en cours |
| git stash pop | Récupère le travail mis de coté |