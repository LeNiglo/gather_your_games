# RegroupeVosJeux (GatherYourGames)

## Description

RegroupeVosJeux (GatherYourGames) est une plateforme de mise en commun de bibliothèque de jeux (vidéos, de société, sportifs?, ...) pour organiser vos soirées.

## Besoin

Lors de l'organisation d'une soirée jeux avec un groupe d'amis ou d'invités, il est parfois difficile de satisfaire le plus grand nombre.
Il serait donc intéressant de pouvoir statistiquement trouver le jeu le plus adapté à votre groupe.

## Solution

RegroupeVosJeux (**RVJ**) vous permettrai de vous authentifier individuellement et de constituer des groupes d'utilisateurs.
L'application serait accessible de en_GB et fr_FR, pensée mobile-first et disponible en PWA et AMP.

### Gestion des groupes et utilisateurs

Ces groupes peuvent être permanents ou éphémères et les utilisateurs qui les composent peuvent être des utilisateurs de RVJ, ~~du site [boardgameatlas.com](https://www.boardgameatlas.com/)~~ ou des utilisateurs éphémères créé spécialement pour ce groupe.
Le créateur du groupe aura la possibilité d'envoyer des invitations par mail aux utilisateurs temporaires pour les inviter à transformer leur compte en définitif.

### Gestion du catalogue de jeux

Tous les utilisateurs auront la possibilité de configurer un whitelist et une blacklist de jeux.
Lors de l'ajout du jeu, s'il existe dans notre base de données, il sera directement ajouté à la liste de l'utilisateur. Sinon, il pourra récupérer les informations de son jeu sur une API de board games ou de jeux vidéos (à déterminer), ou bien même renseigner les informations minimales lui-même s'il s'agit d'un jeu inventé par exemple.

### Utilisation

Une fois les groupes créés, il serait alors simple de voir quel jeu pourrait plaire au plus de personne et ne pas être apprécié par certaines.
Possibilité d'anonymiser les choix, afin de ne pas stigmatiser les personnes ne souhaitant pas jouer à un jeu donné.

## Financement

Dans un premier temps, la totalité de la solution serait gratuite d'utilisation. L'hébergement se fera sur mon serveur personnel pour ne pas ajouter de coût additionnel.
Pour obtenir un minimum de revenu non fonctionnel, un (ou plus) bandeau publicitaire sera présent de manière non intrusive.
Lorsqu'un adblocker sera détecté, un message agréable sera affiché à la place, l'invitant à financer le site.

## Technique

*À déterminer*

Laravel / Blade classique ?

## Etude de l'existant

- https://what.bryou.se/
- https://www.boardgameatlas.com/ (avec une API => https://www.boardgameatlas.com/api/docs)

## Remarques

- Ajouter la possibilité de dire "je veux bien jouer à ce jeu avec lui, mais pas avec lui" ?? complexe mais utile ?
