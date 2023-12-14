# Examen DWWM

Version: V0
Type: Pédago
Date de création: 7 novembre 2023 09:32
Dernière modification: 14 décembre 2023 14:49

## Avant le jour de l’examen

### 📂 **Votre dossier doit contenir :**

- l’ECF signé par le/la chargé(e) de promotion, le(s) formateur(s) et vous même
- La synthèse de votre projet
- Votre dossier professionnel
- Votre dossier projet chef d’oeuvre

## Le jour de l’examen

### 📋 Déroulé de l’examen

| Étape | Durée | Description |
| --- | --- | --- |
| Présentation d'un projet
réalisé en amont de la
session | 35 min | Présentation de votre projet chef d’oeuvre à l’aide de votre support de présentation. La présentation inclus votre démonstration |
| Entretien technique | 40 min | Le jury questionne le candidat sur la base de son dossier de projet et de sa présentation orale.
Un questionnement complémentaire lui permet d’évaluer les compétences qui ne sont pas couvertes par le projet. |

Les examinateurs ont la possibilité de vous suggérer de combiner les 35 minutes de présentation et les 40 minutes d'entretien technique, mais vous avez la liberté de décider de la manière dont vous souhaitez les organiser.

### 🥙 Matériel à prévoir

| Étape | Description |
| --- | --- |
| Dossier projet | Peut être pas à l’imprimer |
| Support de présentation |  |
| Projets complémentaires | Pour garantir votre arrières, si une compétence n'est pas suffisamment illustrée dans votre projet principal, assurez-vous d'avoir les projets complémentaires installés et prêts à fonctionner sur votre machine. |
| Convocation à l’examen |  |
| 🚨 Pièce d’identité |  |

### 💡 À savoir

- N'oubliez pas de signer pendant les jours d'examen, même si ce n'est pas votre jour de passage.
- Les résultats seront disponibles à la fin de l'examen, le vendredi, dernier jour. Vous recevrez un appel le lundi matin.

## Votre orale

Encore une fois, vous avez la possibilité de combiner la durée de la présentation (35 minutes) et celle de l'entretien technique (40 minutes), mais nous veillerons à ce que votre présentation, y compris la démonstration, reste de 35 minutes. 

Combiner le temps de présentation et l'entretien technique ne prolonge pas le temps imparti pour la présentation.

### **📑 Idée de sommaire**

Utiliser le sommaire de votre dossier chef d’oeuvre !

- Présentation 2 ~ 3 minutes (vous, le stage, votre projet …)
- Spécifications fonctionnelles ~ 5 minutes (organisation, maquette …)
- Spécifications techniques ~ 5 minutes (technos, base de données, …)
- Démonstration ~ 20 minutes (démo en temps réel, demo de code screen/IDE, …)
- Veille et conclusion 2 ~ 3 minutes

### 💡 Conseils

- Argumentez vos choix en mettant en avant les contraintes techniques ou fonctionnelles qui les sous-tendent. Expliquez-les pour fournir un contexte clair. Toutefois, veillez à ne pas exagérer et soyez ouvert à la critique.
- Il est préférable d'opter pour un "je ne sais pas" plutôt que de fournir une explication complexe que vous ne pourrez pas défendre. Il est tout à fait acceptable de ne pas avoir toutes les réponses, surtout dans le domaine du développement.
- Il est essentiel de bien comprendre le code que vous présentez lors d'une capture d'écran ou d'une démonstration, notamment les fonctions telles que `filter`, `map`, `reduce`, les spread opérateurs, etc.
- Attention aux captures d'écran ! Elles peuvent trahir. Il est indispensable de prendre le temps de vérifier que leur contenu n'est pas problématique, comme un commentaire inapproprié, du code obsolète commenté ou des traces de conversation avec ChatGPT…
- Évitez de mentionner volontairement des lacunes comme une fonctionnalité manquante ou un code complexe. Ne soulevez pas ces points vous-même. Si le jury les aborde, assurez-vous d'avoir une réponse ou une justification pertinente à ce moment-là.
- Projeter du code sur un fond blanc le rend bien plus lisible avec un rétroprojecteur.

## Foire aux questions

- **📂 Dois-je imprimer mon dossier projet ?**
    
    ❗Question en suspend, peut être pas nécessaire d’imprimer
    
- 🎨 **Ai-je besoin d’un wireframe ?**
    
    Idéalement, oui. Une ébauche du site réalisée à main levée (proprement) sur une feuille A4 pourrait constituer une annexe intéressante à inclure dans le dossier, accompagnée d'une explication détaillée du processus allant du wireframe à la maquette.
    
- 🎨 **Quels écrans ai-je besoin de maquetter ?**
    
    Tous les écrans présents sur votre site, au minimum. Si le temps est limité, il n'est pas nécessaire de concevoir les écrans que vous n'allez pas développer.
    
- 🎨 **Ai-je besoin de maquetter les écrans mobile ?**
    
    Bien sûr, vous adoptez une approche "mobile first" pour la conception et le développement, ce qui signifie que vous démarrez vos maquettes par les écrans mobiles.
    
- **🎨 Ai-je besoin d’un prototype de maquette ?**
    
    Pas nécessairement, cela dépend de ce que vous présentez de votre maquette. Si vous prévoyez de parcourir l'intégralité de votre maquette, il est préférable d'utiliser un prototype plutôt que de naviguer de manière aléatoire dans l'espace de travail Figma.
    
- **❓ Est-ce qu’il y a des questions sur l’agilité ?**
    
    Non, on peut vous en parler mais ce n’est pas rédhibitoire pour l’examen. 
    
- **❓ Est-ce que mes formulaires doivent être sécurisés ?**
    
    Absolument. Des contraintes devraient être mises en place à la fois du côté frontend (formulaire) et du côté backend (entité) afin de garantir la sécurité de vos formulaires.
    
- **❓Mon mot de passe est-il haché, crypté, encodé ?**
    
    Les mots de passe (du moins dans Symfony) sont hachés et non cryptés ou encodés. Il est important de retenir qu'un mot de passe n'est ni crypté ni encodé car il ne peut pas être décrypté ou décodé ! Il est donc nécessairement haché.
    
- **❓À propos des `console.log()` dans mon code ?**
    
    À supprimer !
    
- **❓Ai-je besoin d’une veille sur la sécurité dans mon projet chef d’oeuvre ?**
    
    Absolument, c'est un prérequis pour l'examen, que ce soit dans le dossier écrit ou durant la présentation. Il est important de ne pas trop en faire, mais plutôt de fournir ce qu'il faut avec des explications pertinentes. Pour la présentation orale finale, une slide à ce sujet est indispensable. Cependant, le temps imparti de 35 minutes pour la présentation détermine si tu dois insister sur ce point ou non. Il est probable qu'il y ait d'autres aspects plus intéressants à aborder, et si les examinateurs le jugent nécessaire, ils reviendront sur ce sujet.