# Projet ExoJDBC

Ce projet démontre l'utilisation de JDBC pour interagir avec une base de données MySQL. Le programme se connecte à une base de données, insère des données sur des sites, et exécute des requêtes SQL pour afficher les résultats dans la console.

## Fonctionnalités

- Connexion à une base de données MySQL.
- Création d'une table `site` si elle n'existe pas.
- Insertion de données représentant des sites.
- Affichage de la liste des sites enregistrés dans la base de données.
- Exécution de requêtes SQL personnalisées saisies par l'utilisateur.

## Structure du projet

Le projet contient les classes suivantes :

- **Site** : Représente un site avec ses propriétés (id, nom).
- **Test** : Contient la méthode `main` pour exécuter le programme et gère les opérations de base de données (insertion, affichage des données).

## Prérequis

- Java
- MySQL installé et en cours d'exécution.
- Le driver JDBC pour MySQL doit être ajouté au classpath du projet (par exemple, `mysql-connector-java.jar`).

## Installation et configuration

1. Téléchargez ou clonez ce dépôt.

2. **Base de données :**

   Créez une base de données MySQL nommée `db` :

   ```sql
   CREATE DATABASE db;
   
![image](https://github.com/user-attachments/assets/a66b2e8a-8587-412b-bdeb-081a4f306932)

  Figure 1:Création d’un projet JAVA

  ![image](https://github.com/user-attachments/assets/c8ef3640-b46a-43c5-a727-5421aeda8897)

  Figure 2 : le nom du projet est "demo"

  ![image](https://github.com/user-attachments/assets/a82a1817-9884-4654-b029-8ab8e27df777)

  Figure 3 :Intégrer le Driver de MySQL

  ![image](https://github.com/user-attachments/assets/63c6a36b-0365-4325-8179-07bed1a2fd30)

  Figure 4:la base de données db sous MySQL

  ![image](https://github.com/user-attachments/assets/1e7c1077-369e-4dd0-b92f-a432466343a2)

  Figure 5:la table Site dans la base de données db sous MySQL

  ![image](https://github.com/user-attachments/assets/501fbd3d-f65f-4e2c-882b-b8708a6e4eb6)

  Figure 6:la classe Site dans le package beans.

  ![image](https://github.com/user-attachments/assets/acc17d60-e607-405e-a298-16f6aeed6534)
  ![image](https://github.com/user-attachments/assets/d8104cd1-9850-46d1-ad8c-0cd65a422c94)
  ![image](https://github.com/user-attachments/assets/e68e2745-73a0-4a91-bcac-30fdb722ba81)

  Figure 7:création du fonction save (Site) permettant d’insérer un site dans la table Site dans la base de données db.

  ![image](https://github.com/user-attachments/assets/86aecf90-9c73-42d1-a3f1-fd19b813f0d7)

  Figure 8:Données insérées

  ![image](https://github.com/user-attachments/assets/25a25b19-fccf-4d3d-bcd9-f75baa3c3ae7)
  ![image](https://github.com/user-attachments/assets/6ede8983-88bc-44ae-911e-6c05e92fda7d)

  Figure 9:méthode load() permettant l'raffichage les différents sites.

  ![image](https://github.com/user-attachments/assets/51f41023-cc03-49fb-943e-d9986be974bf)

  Figure 10:Test de load() dans la methode main

  
![image](https://github.com/user-attachments/assets/e8bf8c7d-7324-4992-b503-8db80e9ab3cd)


Figure 11:Récupération des données

https://github.com/user-attachments/assets/f10959fa-fbe2-45db-85c5-fcb8eaf122d8

















