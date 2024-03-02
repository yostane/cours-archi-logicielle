---
sidebar_position: 3
---

# Projet

Vous pouvez vous aider de [ces outils](https://softwarearchitecture.tools/) et de ce [modèle de documents](https://github.com/bflorat/modele-da).

## Sujet 1

Rédiger un document d'architecture logicielle pour un TP ou projet que vous avez déjà réalisé.
Profitez-en aussi pour proposer une architecture améliorée par rapport à votre retour d'expérience.

Les diagrammes à faire obligatoirement sont listés ci-dessous:

- Diagramme d'architecture d'application général et détaillé
- Diagramme de déploiement
- Diagramme de séquence
- Diagramme de cas d'usage

Vous êtes libre d'utiliser UML ou tout autre système de représentation commun.

Voici quelques liens pour vous aider à faire les diagrammes:

- [5 types de diagrammes d’architecture logicielle](https://www.lucidchart.com/blog/fr/les-diagrammes-d-architecture-logicielle)
- [L'Art De Créer Des Diagrammes d'Architecture](https://www.infoq.com/fr/articles/crafting-architectural-diagrams/)
- [Types de diagrammes d'architecture](https://www.edrawsoft.com/fr/architecture-diagram-types.html)

## Sujet 2

On vous propose de proposer une architecture logicielle pour un besoin formulé par votre client (l'enseignant sera votre client).

- Rédiger un document d'architecture complète pour une application complexe en se basant sur ce [modèle](https://github.com/bflorat/modele-da).
- Il est aussi demandé de créer des squelettes d'application.
- Utiliser au maximum des librairies et technologies open-source.

- Application de mailing.
- Système de billetterie avec génération de code-barres sur le mobile.
- Système de contrôle de la maison à distance.
- Site de vente en ligne.
- Jeu vidéo compétitif en ligne de type MOBA.
Veuillez choisir un sujet parmi les sujets ci-dessous.

### Application de mailing

Je souhaite développer une application qui permet aux utilisateurs d'échanger des mails sur téléphones, tablettes et ordinateurs.
Mon application proposera son propre serveur de mails. Les applications peuvent notifier les utilisateurs en temps réel dès qu'un mail arrive.
Les différentes applications auront des interfaces graphiques et fonctionnalités similaire au maximum.

Au niveau des standard mails, je souhaite m'orienter sur du [jmap](https://jmap.io/).

### Système de billetterie avec génération de code-barres sur le mobile

Je souhaite développer un système de billetterie pour un musée.
Il est possible au utilisateurs de réserver en ligne avec leurs ordinateurs ou téléphones.
Une fois la réservation faite, un code-barre sera envoyé par email et sera accessible aussi depuis le compte utilisateur.
Un utilisateur non authentifié peut aussi réserver, dans ce cas, il faut au moins avoir son adresse mail pour lui envoyer le code-barres.
Un utilisateur peut se connecter via ses identifiant Google, Apple ou Facebook.
Il est aussi demandé de développer l'application mobile qui permet de vérifier un code-barre.
Cette application sera utilisée par les agents qui valident l'entrée au musée.
Les utilisateurs pourront payer avec le CB, PayPal, Google Pay et Apple Pay.

### Site de vente en ligne

Je souhaite développer un site qui met en relation des vendeurs et des acheteurs.
Je souhaite aussi proposer système de favoris et de fidélisation.
Les utilisateurs pourront payer avec le CB, PayPal, Google Pay et Apple Pay.

### Jeu d'échecs en ligne

Je souhaite développer un jeu d'échecs jouable sur smartphone et ordinateur.
Le premier joueur créé une partie, ce qui va générer un code unique.
Le deuxième joueur devra saisir ce code depuis son smartphone ou tablette.

### Système de gestion de la scolarité (cours, planning, notes, etc.)

Développer une application qui propose les fonctions suivantes pour les enseignants et les étudiants:

- Authentification gérée via KeyCloack
- Calendrier des cours
- Saisie et consultation des notes
- Saisie et consultation des supports de cours et exercices
- Application consultable sur smartphone et desktop
- Système de notification push avant le début d'un cours ou quand du contenu est déposé par l'enseignant
