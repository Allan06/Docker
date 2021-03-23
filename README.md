# MINI PROJET DOCKER

Le projet source qu'on a utlisé pour le projet Docker [ici](https://github.com/fabiendv/asi-cards-game).

Groupe :

    NITEKA Lys Ciella
    DIALLO Elhadj Mamadou Foula
    PAJANY CARPIN CAOUNDIN Allan

# Travail effectué

    Mise en place des Dockerfiles por chacun des projet
        -> nodeJs/chat
        -> nodeJs/game
        -> reactJs
    Mise en place du docker-compose.yml
        -> Racine du projet

Nous avons testé le projet en lançant les différents composants à l'aide 
"docker build -t nomImage:version . ". Ils fonctionnent correctement, cependant lors de l'exécution en mode "docker-compose build", nous avons des erreurs lié à la création de l'image du serveur Spring Boot. 



Lancement du projet:

    Suivre le lancerment initial sur le site de la source du projet
    Serveur SpringBoot : -> Avoir Maven installé
                         -> Effectuer au sein du dossier /backEnd : mvn compile et un mvn clean install pour crére le fichier Jar 
                         -> Exécution du serveur SpringBoot mvn spring-boot:run
