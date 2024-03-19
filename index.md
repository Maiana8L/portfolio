---
title: "Logiciel métier aviculture"
order: 0
in_menu: true
---
## Contexte métier

La filière avicole française est structurée de telle manière que les élevages de volailles font généralement partie d'organisations de production (OP). En plus des éleveurs-ses qui s'occupent de leurs animaux quotidiennement et effectuent un suivi journalier (mortalité, poids, consommations d'eau et aliment, paramètres d'ambiance, etc), des techniciens-ciennes des OP viennent régulièrement compléter ce suivi par des visites techniques, voire des audits sur des thématiques précises.
Toutes ces données sont intéressantes à traiter par les OP et les autres maillons de la filière (vétérinaires, firme-service, généticiens, etc) afin d'avoir une vision claire de la production.

## Contexte pratique

Concrètement, les données en élevages dont notées sur support papier, parfois sur des boitiers internes aux élevages dont la récupération est complexe. Les données ne sont donc pas analysées en temps réelles, parfois en interne via excel, souvent à des entreprises tiers via des logiciels qui sollicitent beaucoup de petites main pour insérer les données et dont les graphiques et tableaux de bord sont très limités.

## Objectif

Créer un outil s'adressant aux différents métiers de la filière, afin que les données soient saisies en direct par les éleveurs-euses et techniciens-ciennes puis accessibles par les personnes qui en ont besoin, tout en étant consolidées afin de faciliter leur lecture, et permettre de réaliser des prises de décision et des projections techniques et économiques sur les productions.
![Objectif de l'outil : renforcer les liens entre les parties prenantes de la filière, être plus rapide et plus précis dans l'analyse des données d'élevage]({% link images/Objectif.png %})
![L'outil s'articule en différents modules : élevage, technicien, pilotage et stratégie]({% link images/Modules et fonctionnalités principales.png %})

## Challenges

- Diversité des profils utilisateurs-trices  
- Diversité des fonctionnalités et personnalisation  
- Asymétrie mobile et web  
- Gestion du hors-ligne  
- Création d'API (et import de l'historique de données)  
- Révolution d'usage  
- Contexte international 


## Process
- Recueil du besoin initial
- Priorisation et sprints
- Ateliers de conception et maquettage
- Tests
- Déploiement
  - Communication
  - Supports d'accompagnement
  - Formation

## Visuels
![Page d'accueil web d'un utilisateur type profil éleveur avec le menu pour accéder aux différentes fonctionnalités à gauche, des accès rapides concernant ses lots de volailles en cours et passés au centre, des widgets de rappels et notifications à droite]({% link images/Page accueil éleveur.png %})
![Déroulé des écrans mobile pour saisir les informations techniques journalières d'un lot de poulets comme la mortalité, le poids, etc]({% link images/Mobile - Fiche élevage.png %})
![Comparatif de 2 écrans, l'un web et l'autre mobile, pour saisir les données de la catégorie poids. Sur mobile, il n'y a que les champs du jour que l'on veut compléter, avec possibilité de changer de jour sur le haut de l'écran. Sur le web, on voit aussi un tableau récapitulant d'autres poids renseignés les jours précédents, en plus de la possibilité de saisir un poids pour un jour donné]({% link images/Saisie poids - mobile et web.png %})
L'outil étant riche en fonctionnalités, il y a de nombreux autres écrans tels que des tableaux de bord avec une diversité de graphiques ou de tableaux, des formulaires de saisie d'information diverses, du paramétrage, de la consultation d'informations brutes, de l'export de pdf, etc

### Si c'était à refaire, je demanderais ...
- Un accès direct aux utilisateurs-trices
- Une simplification des fonctionnalités de départ (pour commencer par un vrai MVP)
- Plus de disponibilité des personnes décisionnaires

Je serai ravie d'échanger sur ce projet avec vous, il y a tant à dire ! 