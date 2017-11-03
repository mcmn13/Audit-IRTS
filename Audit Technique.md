# Audit technique

## 1) Présence de Partage Sociaux

Bouton de partage des réseaux sociaux :
- Facebook   OK
- Twitter    OK
- LinkedIn   Erreur de lien > redirige vers Viméo
- Viméo      OK

Mauvaise visibilité ; icones trop basses.

Ces boutons sont des liens vers les différents profils/comptes de l'IRTS.
Il n'y à pas de bouton permettant de partager du contenu sur les réseaux sociaux.
### Préconisation : 
- Ajouter bouton de partage RS sur les Actualités ?
- Ajouter une barre RS en hauteur ou sur les côtés ?
___

## 2) Formulaire de contact

La page "Qui sommes-nous" contient les adresses mails de l'équipe
Mail générique séparé des mails de l'équipe

Attention aux robots récupérateurs d'adresses mails ! (Spams et autres mails indésirables)

### Préconisation : 
- Regrouper l'adresse mail générique avec les adresses mails de l'équipe ?
- Mise en place d'un formulaire de contact avec un champs permettant de choisir à qui l'on s'adresse.

___

## 3) Rejet des données saisies

Lors de la connexion à l'espace personnel : message prévenant lors d'une erreur d'authentification

___

## 4) Contrôle sur la lecture des médias

Les vidéos sont hébergées sur Viméo et Youtube.
Les vidéos intégrées de Youtube se lance uniquement après interaction de l'utilisateur

___

## 5) & 6) Newsletter (en construction)

Actuellement, aucun espace dédié à l'inscription/désinscription d'une newsletter

___

## 7) Moteur de recherche dynamique

Le moteur de recherche basique garde un historique des recherches effectuées
Le moteur de recherche avancé possède 3 champs de recherches dynamiques (Auteur, Mot-clés,Collection) 

___

## 8) Flux RSS (en construction)

### Préconisation :
- Amélioration de la visibilité via l'ajout d'un icône RSS à la barre de Réseaux Sociaux

___

## 9) Page 404

La page 404 n'est pas personnalisée (nginx)

### Préconisation
- Création et mise en place d'une page 404 personnalisée (voir exemple sur google image "page 404")

___

## 10) Les balises "title"

Chaques pages possède un contenu de balise <title> différents

___

## 11) Les balises meta "keywords" & "description"

Le contenu des balises meta "keywords" et "description" sont identiques sur toutes les pages du sites avec pour contenu :

- keywords : "OPAC, web, library, opensource, catalog, catalogue, bibliothèque, médiathèque, pmb, phpmybibli"
- description : "Catalogue en ligne Nom de bibliothèque"

### Préconisation 
- Travail sur les mots-clés et création d'une description reprenant ces mots-clés (dans l'idéal, tavailler sur chaques pages individuellement)

___

## 12) Réecriture des URLs

Les URLs ne sont pas réecritre de manière lisible pour l'utilisateur 
("http://crd.irts-pacacorse.com/index.php?lvl=cmspage&pageid=6&id_rubrique=23" et non "http://crd.irts-pacacorse.com/qui-sommes-nous/)

### Préconisation
- Activer la réecriture automatique des URLs 

___

## 13) Toutes les pages sont accessibles par un lien HTML en dur 

Vérification impossible sans accès au BackOffice

___

## 14) Hiérarchisation des titres "h1/h2/h3/h4/h5/h6"

h1 : 1 titre
h2 : pas de titre
h3 : 35 titres
h4 : 5 titres
h5 : 6 titres

### Préconisation
- Travail de hiérachisation des titres à faire : donner un sens à votre document en hiérarchisant l'information !

___

## 15) Balises "strong"

Les mots-clés ne sont pas balisés !

Analyse grader.rezoactif.com :  - texte(s) en gras      (1)
                                - texte(s) en italique  (3)
                                - texte(s) en soulignés (0)

### Préconisation
- Travail sur mots-clés et intégration dans les pages
___
