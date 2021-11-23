 

## Énoncé

L’objectif de ce projet est la réalisation d’un jeu de type tron/snake en python. Il devra offrir deux
possibilités de jeu :

    1 un mode solo,
    2 un mode deux joueurs.
### Mode solo

Le mode solo reprenant les règles classiques d’un snake. Dans ce jeu, le joueur contrôle un serpent.
L’objectif est alors de manger les fruits qui apparaissent régulièrement à l’écran. Lorsque le serpent
mange un fruit, i.e. lorsque la tête du serpent passe sur la case contenant le fruit, sa longueur aug-
mente. De plus la vitesse de ce dernier augment à intervalles régulier. La partie s’arrête lorsque le
serpent mord son corps ou rencontre un mur. L’objectif étant d’obtenir le meilleur score possible.

### Mode deux joueurs

Le mode deux joueurs permet à deux joueurs de s’affronter sur le même plateau. Ce mode reprend
les règles du mode solo à ceci près qu’il est possible d’éliminer son adversaire en le poussant à la faute,
i.e. en forçant la collision en la tête du serpent adverse et le corps de son propre serpent.
L’élimination d’un adversaire entraîne l’arrêt de la partie mais octroie un bonus de points au joueur
ayant éliminé son adversaire. Le gagnant de la partie est le joueur ayant le plus de points (et donc pas
nécessairement le joueur ayant éliminé son adversaire).
Dans ce mode les deux joueurs jouent sur le même clavier.

### Hall of fame
Les scores des meilleurs joueurs devront être sauvegardés par l’application afin d’offrir la possibi-
lité d’accéder au Hall of Fame : un tableau reprenant les noms et les scores des meilleurs joueurs.
Consignes
Le programme doit être codé en Python. Le code sera testé sur la dernière version de ce langage,
à savoir Python 3.9.7.
Le développement se fera en binôme (imposé par les enseignants) et devra suivre les principes de
l’Extreme Programming (XP) détaillés en cours, à savoir (mais de manière non exhaustive) :

    - Pair Programming,
    - TDD,
    - Création et gestion des User Stories,
    - ...

Les interactions avec le client se feront par l’intermédiaire d’un forum sur Moodle. L’information
donnée par ces derniers (M. Tillieux et M. Duvillié) font office de consignes et doivent être respectées.
Assurez-vous de créer une discussion par sujet abordé et de bien vérifier que votre question n’a pas
été posée au préalable.
## Évaluation
Vous aurez à présenter une démonstration de votre programme le 30 novembre 2021. Lors de cette
présentation orale, des questions vous seront posées :

    — sur vos choix techniques,
    — sur la gestion de votre projet,
    — sur votre code,
    — sur la théorie abordée en cours,
    — ...
Attention cette liste n’est pas exhaustive. Il est important de rappeler que l’incapacité à expliquer
tout ou une partie du code entraînera un échec à l’évaluation. Le code servant à la démonstration
pourra être modifié jusqu’à la veille de l’évaluation orale à savoir le 29 novembre 2021 à 23 :59.
Il vous est également demandé de rendre un rapport expliquant :

    — vos choix techniques et la justification de ces derniers,
    — vos choix en terme de structures de données et la justification de ces derniers,
    — les algorithmes utilisés ainsi qu’une analyse de leur complexité lorsqu’elle est pertinente,
    — les difficultés rencontrées,
    — ainsi que toute information nécessaire à une bonne appréhension du projet pour un developpeur tiers.

Cette partie compte pour 35% de la note finale.
## Modalités de remise
Comme le stipule l’XP, votre attention est attirée sur le fait, que le code doit être hébergé sur
gitlab et que la branche principale de votre dépôt doit héberger, en tout temps du projet, un exécu-
table fonctionnel.
Le rapport est à rendre via Moodle pour le 25 novembre 2021