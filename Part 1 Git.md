# PARTIE I – GIT

**Les commits : machines à voyager dans le temps

Avant de parler de Github nous devons d’abord parler de Git, le logiciel originel sur lequel se greffe cette interface.

Git est un logiciel qui fonctionne sur toutes les plateformes (Windows, Mac, Linux), sa spécificité est de permettre à plusieurs développeurs de garder l’historique de modification de leurs fichiers, ligne par ligne. Cela peut sembler anodin si on ne code pas mais en réalité cette particularité permet de s’assurer que son site ne va pas se crasher suite à une erreur de code. En cas de bugs Git permet de revenir au dernier commit qui fonctionnait et de prendre le temps de travailler sur ce qui ne marchait pas.

 


On peut faire un parallèle avec un Google Docs qui permet de revenir sur l’historique des modifications du document.

A la différence, sur Git on « commit » tous les nouveaux fichiers que l’on ajoute ou supprime, ainsi que les lignes modifiées dans le code, elles sont « commitées ». Le développeur choisit quand il souhaite commiter (donc “enregistrer” sous forme de commit) un ensemble cohérent de modifications.

**Les branches : univers parallèles

Le but des branches est de pouvoir développer une nouvelle fonctionnalité sans qu’elle impacte le code stable (qui réside sur la branche « master »). Une branche est un univers parallèle qui démarre à partir d’un commit du master et sur lequel on ajoute des commits le temps de construire quelque chose de stable.

 

Par exemple : je gère un site de e-commerce et je souhaite rajouter un bouton « s’inscrire à la newsletter ». Si je le fais directement sur le master et que je fais une erreur cela peut rendre tout mon site inutilisable. Je vais donc travailler sur une branche en parallèle (qui ne sera pas encore effective sur le site) et au fur et à mesure je vais commiter les différentes parties de mon code. Quand je suis content du résultat, je peux partager cette branche avec mes collègues pour leur faire une démo de la nouvelle fonctionnalité, ou leur faire relire le code. Quand tous les critères de qualité sont au vert je peux fusionner ma branche de travail dans la branche master du projet et envoyer le code sur le serveur de production.

Utiliser Git permet donc d’optimiser son code au quotidien. A la Wild Code School nos développeurs mais aussi nos élèves l’utilisent au quotidien.
On vous explique dans un prochain article pourquoi nous utilisons Github !
