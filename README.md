# flexiAir

Prototype 1 : Onboard

https://www.figma.com/proto/rAI0vtkW9p8UsPhGgETBJW/Flexi-Air-Mobility?type=design&node-id=48419-9169&scaling=scale-down&page-id=26629%3A2887&starting-point-node-id=48419%3A9169&show-proto-sidebar=1


Prototype 2 : Mobility
https://www.figma.com/file/rAI0vtkW9p8UsPhGgETBJW/Flexi-Air-Mobility?type=design&node-id=48419%3A9169&t=jkaCf18qLxBCE1Ec-1

Prototype 3 : Dashboard
https://www.figma.com/file/rAI0vtkW9p8UsPhGgETBJW/Flexi-Air-Mobility?type=design&node-id=48419%3A9104&t=jkaCf18qLxBCE1Ec-1

Prototype 4 : Badges
https://www.figma.com/file/rAI0vtkW9p8UsPhGgETBJW/Flexi-Air-Mobility?type=design&node-id=48419%3A9147&t=jkaCf18qLxBCE1Ec-1

Prototype 4 : Community
https://www.figma.com/file/rAI0vtkW9p8UsPhGgETBJW/Flexi-Air-Mobility?type=design&node-id=48419%3A9201&t=jkaCf18qLxBCE1Ec-1

## Une application qui valorise les petites actions, plutôt que les gestes héroïques.

![image](https://github.com/paulinecoudert/flexiAir/assets/67103663/c9250000-8ee4-42eb-87b8-7919b38a20f2)


1. Contexte et définition du projet

De plus en plus de gens s’inscrivent dans une lutte climatique, avec quelques actions aujourd’hui on peut arriver à économiser le C02 et cela passe on l’a vu par nos déplacements. Mais parfois on ne s’est pas trop comment s’y prendre et l’on manque de motivation seule, c’est pourquoi nous vous proposons une application qui a pour but de sensibiliser le client face à son empreinte dans ses trajets.  Elle coachera et encouragera ses acteurs.

2. Objectif du projet 

Via l’application nous souhaitons faire changer de manière douce le comportement de l’usager.  Il sera valorisé par ses actions, l’application sera comme un coach prêt à l’informer à le diriger et à le motiver. Elle permet à l’individu d’appartenir à un groupe et de se lancer des défis.

3. Périmètre du projet 

L’application s’adresse aux citoyens de Belgique mais peut prétendre par le futur à un développement international. Elle a pour but de dévoiler à l’utilisateur sa consommation de CO2 via les transports qu’il utilise et de lui proposer d’autres alternatives dans ses déplacements du quotidien.
Bien entendu le calcul de l’empreinte se fera en fonction de la routine propre à chaque personne. L’idée n’est pas de comparer une personne qui vivrait en ville avec une grande offre de services en mobilité et une personne qui vivrait à la campagne avec une offre plus réduite. Ce que nous souhaitons soulever ce sont les efforts qui vont être entrepris, sa participation à un monde plus aérer.

4. Description

On pourra télécharger l’application gratuitement , elle s’adressera à un public de +18 ans pour sensibilisé à la technologie et à la lutte climatique.  
A chaque déplacement l’utilisateur entrera sa destination et l’application lui proposera un itinéraire avec un ou plusieurs moyens de se déplacer. L’utilisateur peut à tout moment choisir un autre choix et modifier ses paramètres de déplacements.
A la fin de la semaine Il se verra attribué un type de badge au fur et à mesure qui lui donnera des réductions, bons plans, défis…
La page d’accueil sera composée d’un bouton play qui permettra à l’utilisateur de déclencher son gps pour qu’il comptabilise son nombre de km. A la fin de la journée l’appli sera en mesure d’additionner les km des différents parcours.

L’application sera composée d’un menu où l’on retrouvera les pages mobilité, 
En haut à gauche apparaitra le menu hamburger et à droite son image de profil.

Un menu sera constitué de différentes sections:
Mobility (routine du jour préférence de déplacement véhicules)
Dashboard (tableau déplacement et émission CO2 jour/semaine/mois)
Badge (points)
Profil
Community (message, partage avec d’autres utilisateurs, like)
Vehicules (paramétrages des moyens de déplacements)

Dans la page Dashboard, une première carte avec les infos de la météo en dessous un tableau reprendra les différents modes de transports sélectionnés et leur utilisation sur la semaine, enfin on pourra voir sa consommation de C02 et le nombre de Km parcouru.

Dans la page Mobility une carte permettra de sélectionner son parcours point de départ et arrivée. L’ Appli nous proposera un type d’itinéraire avec une sélection 
un tableau reprendra la journée en cours du citoyen où il pourra prédéfinir ses types de transports favoris qui seront enregistrés, et verra le rapport émission CO2.

Dans la page Badge sera indiqué les avantages ou défis que l’utilisateur aura reçu. Cela peut être des réductions chez des fournisseurs d’énergie, achat de vélos… plantation d’arbre. 3 types de badges seront disponible et plus les levels seront franchis et plus la liste sera longue avec une section défi qu’il pourra envoyer à ses amis par un message: Exemple «  une semaine sans emballage… »

Dans la page de création du Profil, il pourra rentrer une photo, ses infos personnelles (nom, prénom, adresse, date de naissance), ses types de transports préférées.

Dans la rubrique Community, il pourra rentrer en contact avec d’autres utilisateurs , liker leurs profils, partager des bons plans et leur envoyer des défis.

Dans la rubrique Vehicles il pourra modifier à sa guise ses types de déplacements.


5. Description fonctionnelle des besoins

Nous utiliserons des Api de type météo , google maps (gps), google analytics (pour le graphique).
Nous créerons un UML  pour créer une base de donnée afin de vérifier le bon fonctionnement de 
L’application. Elle sera réalisé en ASP.Net , avec un langage c# et une template type bootsraap.

6. Enveloppe budgétaire

Type d’application : application gratuit pour Android et iPhone
Temps : 6 mois pour développer
Nombre de développeurs : 3
Design : 3000 euros
Total : 40 000 euros

Sans compter : 
Utilisation des API externes : 
Google Maps (200 euros/mois)
Open Weather (200 euros/ mois)
Hébergement : (130 euros/ mois)
Configuration :
Google Play : 20 euros,
Apple : 50 euros,
Maintenance : 6000 euros par an pour la base de données ; pour Android et IOS un tarif supplémentaire. Après un an passage au système forfaitaire. 
*Prix hors TVA!

7. Partenaires
STIB
BlaBlaCar
Villo!
Billy Bike
Blue-Bikes
Swapfiets
Takewheels
Lime
Poppy
Felyx
Dott
Cambio
ZenCar
De Lijn
SNCB
TEC
Bruilingua
Wallangues
Mega

8. Concurrence

Voici 2 exemple d'applications de pure calculateur d’empreinte lors de déplacement. Comparé a notre appli ceux-ci n'ont pas de coach, ni d’accès a la météo,...

![image](https://github.com/paulinecoudert/flexiAir/assets/67103663/9dec5b07-d857-4cc9-b2d9-240eb703be9d)


10. 
Aujourd'hui sur le marché international existent plusieurs applications (eco mobile) qui ont pour but d’encourager les utilisateurs  à diminuer leur impact environnemental.
D’un côté on peut trouver très facilement les applications, par exemple « 90 jours » qui comme un coach motive l'utilisateur pour qu'il change facilement et durablement leurs habitudes, sinon « Yuka » qui calcule l’impact environnemental d’un produit.
De l’autre côté il y a des applications très similaires par exemple « Carbo » qui au premier regard pourrait être le concurrent de notre projet, car elle calcule notre impact carbone et aide à le réduire. Alors pourquoi proposer un projet similaire ?
Notre application est là pour pouvoir donner des alternatives dans les déplacements, créer des habitudes pour vivre durablement et rejoindre une communauté de personnes qui se soutiennent et se lancent des défis pour diminuer l’impact de Carbonne.















