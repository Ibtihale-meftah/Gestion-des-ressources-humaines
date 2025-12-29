# Gestion-des-ressources-humaines
Ce projet consiste à développer une application web de gestion des ressources humaines. Elle permet de gérer les employés, les postes et les demandes de congé de manière centralisée.  L’application offre aux employés la possibilité de consulter leur profil et de soumettre des demandes de congé.


## Fonctionnalités

- Authentification et gestion des accès
- Gestion des employés
  - Création, modification, suppression, consultation
  - Recherche et filtrage
- Gestion des services
- Gestion des postes
- Gestion des demandes de congé
  - Soumission et suivi du statut
- Tableau de bord RH

## Architecture

- Présentation (MVC)
  - Controllers, Views (Razor), ViewModels
- Métier
  - Services, règles de gestion, validations
- Données
  - Entity Framework Core, repositories (si appliqué), migrations

## Stack technique

- C#
- ASP.NET Core MVC
- Entity Framework Core
- Base de données : MySQL
- Outils : Visual Studio, Git, GitHub

## Prérequis

- .NET SDK compatible avec le projet
- MySQL , pHp Myadmin
- Visual Studio 2022 (recommandé)

## Démarrage rapide

1. Cloner le dépôt
   git clone https://github.com/ibtihale-meftah/Gestion-des-ressources-humaines.git
   cd Gestion-des-ressources-humaines

2. Configurer la base de données
   - Ouvrir appsettings.json
   - Mettre à jour la chaîne de connexion

3. Appliquer les migrations
   - Package Manager Console :
     Update-Database
   - Ou CLI :
     dotnet ef database update

4. Lancer l’application
   dotnet run
   ou depuis Visual Studio : Ctrl + F5

## Configuration

Le fichier appsettings.json contient :
- La chaîne de connexion
- Les paramètres d’environnement (Development, Production)

Conseil : utilisez appsettings.Development.json pour vos paramètres locaux.

## Structure du projet

- /Controllers
- /Models
- /Views
- /ViewModels
- /Services
- /Data
- /wwwroot
- /Migrations

La structure peut varier selon votre implémentation.

## Base de données

Entités principales :
- Employe
- Service
- Poste
- DemandeConge

Les relations sont gérées par Entity Framework Core.

## Qualité et bonnes pratiques

- Validation côté serveur
- Séparation des responsabilités (MVC + services)
- Nommage cohérent des entités et des vues
- Migrations pour versionner le schéma de base de données

## Login

![WhatsApp Image 2025-12-21 at 12 05 20 PM](https://github.com/user-attachments/assets/446bdc14-fa08-446b-b9f9-99e90f568c76) 

## Dashboard


<img width="1920" height="1020" alt="Capture d&#39;écran 2025-12-21 120537" src="https://github.com/user-attachments/assets/55dca506-7bee-4c99-9e1b-4addd1919092" />

## Comnte employé


<img width="1920" height="1020" alt="Capture d&#39;écran 2025-12-21 013401" src="https://github.com/user-attachments/assets/ebcc908a-4e5f-4168-af67-f563a40d76e5" />

## Demandes de congé


<img width="1920" height="1020" alt="Capture d&#39;écran 2025-12-21 013502" src="https://github.com/user-attachments/assets/9b4041b1-895a-47f6-ac4e-ba1fee949dcd" />


## Auteur

Ibtihale Meftah 
Étudiante en 4 éme année ingénierie, Informatique et Réseau , filière développement digital (EMSI Casa Blanca)

## Licence

Projet académique. Usage pédagogique.
