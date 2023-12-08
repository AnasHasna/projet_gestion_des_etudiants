# README.md - Gestion des Étudiants

## Description du Projet

Ce projet a été développé pour la gestion des étudiants, avec deux espaces distincts : l'Espace Administrateur et l'Espace Enseignant. Il permet la gestion des filières, des étudiants, des statistiques, du reporting, du trombinoscope, et offre des fonctionnalités telles que la connexion à distance à SQL Server, le déploiement des applications desktop, et l'utilisation de Crystal Reports et Link to SQL.

### Architecture du Projet
La base de données doit être hébergée sur une machine "A".
Le développement de l'application se fait sur une machine "B".
Les utilisateurs n'ont besoin que de l'exécutable de l'application Windows Forms.

### Technologies Utilisées
Windows Forms (C#)
ADO.NET
Crystal Reports
Link to SQL
SQL Server

### Installation
Clonez le projet depuis le dépôt Git.
Assurez-vous d'avoir une connexion réseau pour accéder à la base de données hébergée sur la machine "A".
Compilez et exécutez l'application sur la machine "B".

### Fonctionnalités

##### Espace Administrateur:

1. Menu Filière
Ajouter, modifier, supprimer une filière.
Afficher les filières sauvegardées.
2. Menu Étudiant
Charger les données des étudiants pour un niveau donné.
Trier les étudiants par ordre croissant/décroissant.
Importer la liste des étudiants à partir d'un fichier Excel.
3. Menu Statistique
Afficher le nombre d'étudiants par filière avec le pourcentage.
4. Menu Reporting
Afficher un reporting pour tous les étudiants groupés par filière.
Gérer le reporting d'un étudiant spécifique.
5. Menu Trombinoscope
Créer un nouveau dossier contenant les photos des étudiants à partir d'un fichier Excel.
Exporter un fichier PDF contenant le trombinoscope du niveau choisi.

##### Espace Enseignant :
Accéder au trombinoscope des étudiants d'une classe.
Télécharger un fichier Excel de la liste des emails des étudiants.
Chercher un étudiant par son nom ou son code massar pour récupérer son niveau et son email.
