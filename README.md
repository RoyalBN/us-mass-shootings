# Titre du Projet

U.S Mass Shootings: 1966-2017

## Description du contexte

Notre étude porte sur les différentes attaques terroristes ou autres qui se sont produites aux Etats-Unis entre 1966 et 2017.

## Les données

Notre fichier .csv principal "MassShootingsDataset.csv" contient exactement 398 données en tout. 
On a : le titre, la localisation, la date, un resume, le nombre de morts, le nombre de blessés, le nombre total de victimes (blessés + morts), les problemes mentales du/des terroriste(s) ou criminel, la race, le sexe et les coordonnees geographiques des attaques (latitude et longitude).

Chacune de ces colonnes est enregistrer dans une variable (Voir ci-dessous):

  Shootings   = Variable qui lit le fichier "MassShootingsDataset.csv" principal

  title       = Récupère le titre
  location    = Récupère la localisation
  date        = Récupère la date
  fatalities  = Indique le nombre de morts 
  injured     = Indique le nombre de blessés
  victims     = Indique le nombre total de victimes (blessés + morts)
  mental      = Indique les problemes mentales du/des terroriste(s) ou criminel(s)
  race        = Indique la race du/des auteur(s)
  gender      = Indique le sexe du/des auteur(s)
  longitude   = Indique la longitude géographique
  latitude    = Indique la latitude géographique

  annee           = Extrait et récupère uniquement l'année de la date ("%m/%d/%Y" devient "%Y")
  annee_date      = Convertit "annee" au format numeric à l'aide de "as.numeric(annee)"
  us              = Contient la carte des Etats-Unis d'Amérique
  americas.limits = Variable qui lit le fichier "map.csv" qui contient toutes les limites de la carte 


## Pré-processing des données

Nous ne disposons pas de pré-traitement avec un script en Python dans notre projet. 

## Installation des packages R

install.packages("tidyverse")
install.packages("ggmap")
install.packages("maps")
install.packages("mapdata")
install.packages("mapproj")
install.packages("rworldmap")


## Le script

Pour utiliser le Notebook correctement, il faut récupérer les deux fichiers suivants: "MassShootingsDataset.csv" et "map.csv". Ensuite, il faut s'assurer que les libraries suivantes sont
utilisées: "tidyverse","ggplot2","ggmap","maps","mapdata","mapproj","rworldmap". Il faudra peut-être 
effectuées les mises à jour des paquets avant d'installer ces nouveaux paquets.

Enfin, lancer juste les différentes "cases" dans L'ORDRE en appuyant sur le bouton Play.




