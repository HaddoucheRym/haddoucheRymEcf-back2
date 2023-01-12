# haddoucheRymEcf-back2

## Description
Localib est une application de gestion de locations de véhicules et de locataires.

## A propos
Vous trouverez dans ce dépôt 2 dossiers à la racine:
- le dossier frontLocalib qui contient la partie front-end : React js
- le dossier backLocalib qui contient la partie back-end: Spring boot

## Prérequis
- [docker](https://www.docker.com/products/docker-desktop)
- [docker-compose](https://docs.docker.com/compose/install/)
- IDE
### La partie back-end
- Java 11+
- Un IDE Java ([Eclipse](https://www.eclipse.org/downloads/), [IntelliJ](https://www.jetbrains.com/fr-fr/idea/))

### La partie front-end
- JavaScript
- IDE javaScript ([VsCode](https://code.visualstudio.com/download))

## Instalation
### Build le projet à l'aide de gradle
- Dans votre IDE, lancer la commande suivante pour se placer dans le dossier backLocalib :\
``` cd backLocalib```  
- Lancer la commande suivante pour le building\
```./gradlew clean build``` 
- Pour chargez le projet gradle, taper la commande suivante: \
``` docker-compose build```

### Conteneuriser l'application à l'aide de Docker Compose
Il faut se placer dans le dossier racine et lancer la commande suivante pour executer l'application avec docker:
 ```docker-compose up```


