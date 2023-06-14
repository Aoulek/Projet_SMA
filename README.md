# Projet_SMA
nous avons mis en place un système multi-agents pour résoudre le problème d'allocation de restaurants pour un groupe de N personnes. Nous avons présenté plusieurs comportements possibles pour les agents, notamment la délibération où chaque agent demande à P autres agents avant de faire un choix. Nous avons utilisé la méthodologie AUML pour la conception de notre système et la plateforme JADE pour son implémentation.
L'utilisation d'un système multi-agents a permis de résoudre le problème d'allocation de manière efficace et autonome, en répartissant les tâches entre les différents agents et en prenant en compte les interactions entre eux. Notre système offre une grande flexibilité en permettant la modification des critères de choix et des comportements des agents pour s'adapter à différentes situations.
Enfin, ce projet nous a permis de mieux comprendre les avantages et les défis de la conception et de l'implémentation de systèmes multi-agents, ainsi que les outils et les méthodologies disponibles pour leur développement.

Conception : 
•	Diagramme de cas d’utilisation:
 ![image](https://github.com/Aoulek/Projet_SMA/assets/101673062/46e4cc2f-96f9-414f-9424-52fe5477b96b)

Dans ce diagramme de cas d’utilisation on a Les trois acteurs : client, Restaurant et Réservation héritent de l’acteur Agent
L’agent Client possède la possibilité de : 
-Rechercher et consulter un restaurant
-Réserver une table
L’agent Restaurant possède la possibilité de : 
- Accepter une réservation
-Refuser une réservation
L’agent Réservation possède la possibilité de : 
- Cree une réservation
-Consulter une réservation
•	Diagramme de séquence:
![image](https://github.com/Aoulek/Projet_SMA/assets/101673062/1a53f71e-6268-4163-90fc-8a401ee2acdf)


•	Diagramme de classe:

![image](https://github.com/Aoulek/Projet_SMA/assets/101673062/3565b3eb-985d-4964-a558-0ffd644cd263)



II.	L’implémentation et l’exécution en utilisant JADE

•	Structure du projet

![image](https://github.com/Aoulek/Projet_SMA/assets/101673062/1193c920-437e-4cd5-bbac-bcb46e00514e)

 

•	Le dossier images :
Contient les images utilisées dans le projet
•	Le dossier sma :
Contient les trois containers : Client, Réservation, Restaurant et le main Container
•	Le dossier sma.agent :
Contient les trois agents de notre système Client, Réservation et Restaurant
•	Le dossier sma.behavouirs :
le dossier "behaviors" dans ce projet contient les implémentations de comportements pour les agents : Réservation et Restaurant
 
•	L’execution du main Container
![image](https://github.com/Aoulek/Projet_SMA/assets/101673062/f5b044b7-80ed-4ae3-844a-14b2816b7b20)

 
•	L’affichage de main Container
 ![image](https://github.com/Aoulek/Projet_SMA/assets/101673062/f895fa27-cc0a-4506-a406-0387a7405c96)

Main Container qui contient les trois agents par défaut ams, df et rma
•	L’execution du Client Container
 ![image](https://github.com/Aoulek/Projet_SMA/assets/101673062/288e0cf6-414a-4c3a-843a-d9bb91de61df)

•	L’affichage de Client Container
 ![image](https://github.com/Aoulek/Projet_SMA/assets/101673062/a4caf6f9-cb56-4b1a-bb9a-33992c8703c1)

•	L’execution du Reservation Container
 ![image](https://github.com/Aoulek/Projet_SMA/assets/101673062/cfa1496a-185f-4bea-8a54-72d4dd7c2fbf)

•	L’affichage de Reservation Container
 ![image](https://github.com/Aoulek/Projet_SMA/assets/101673062/be3dcc1d-fa83-4c11-9d94-fb9d58766127)

•	L’execution du Restaurant Container
 ![image](https://github.com/Aoulek/Projet_SMA/assets/101673062/7b26e036-3422-4b30-8647-c3685c0a2e44)

•	L’affichage de Reservation Container
 ![image](https://github.com/Aoulek/Projet_SMA/assets/101673062/72b835e3-d769-4683-9c8b-a678be43b3aa)

•	L’affichage des trois executions
 
![image](https://github.com/Aoulek/Projet_SMA/assets/101673062/e129693a-6243-4317-9eab-3de5a708a9c3)

•	Résultat

 ![image](https://github.com/Aoulek/Projet_SMA/assets/101673062/0941db74-147d-4a25-9c21-8b8bf3839d8e)

•	Ajouter agent de restaurant
 ![image](https://github.com/Aoulek/Projet_SMA/assets/101673062/2b442a45-d704-4401-8b06-512eab8394f5)

•	Publication de service dans DF
 ![image](https://github.com/Aoulek/Projet_SMA/assets/101673062/47f33473-9904-4cbc-b876-00c4d89da14d)

•	resultat d’ajouter un restaurant
 ![image](https://github.com/Aoulek/Projet_SMA/assets/101673062/034afb0a-d7d0-41e2-865e-7bd1b3c4490b)

•	l’ajout de deux autres restaurants
 ![image](https://github.com/Aoulek/Projet_SMA/assets/101673062/2e80347e-e0f0-4c68-86fb-a93f34d7785f)



•	demande de réservation de restaurant basma et communication avec l'agent réservation
![image](https://github.com/Aoulek/Projet_SMA/assets/101673062/6d460120-9da2-4a2b-b840-a4dad17597fe)
![image](https://github.com/Aoulek/Projet_SMA/assets/101673062/81fb340e-c543-4bfe-a985-082ef3f5cd5b)
![image](https://github.com/Aoulek/Projet_SMA/assets/101673062/015bd8d8-75f1-4ff2-bf5b-3f71de53f9ff)



