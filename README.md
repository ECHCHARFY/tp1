# Projet TP1

Ce projet configure un environnement de développement avec Nginx, PostgreSQL et pgAdmin en utilisant Docker et Docker Compose. Le service Nginx sert une page HTML statique, tandis que PostgreSQL et pgAdmin permettent la gestion de la base de données.

## Prérequis

- Docker
- Docker Compose

## Structure du projet
![image](https://github.com/user-attachments/assets/b1fee81e-95db-45d8-a180-5819f532ccc3)

## Configuration des services

### Nginx

- Sert une page HTML statique `mypage.html`.
- Utilise un fichier de configuration personnalisé `default.conf` pour définir `mypage.html` comme page principale.

### PostgreSQL

- Conteneur PostgreSQL avec une base de données initiale `projetTp1`.
- Script SQL `bd.sql` pour initialiser la base de données avec une table de test.

### pgAdmin

- Interface graphique pour gérer PostgreSQL.
- Accessible via `http://localhost:5050` avec les identifiants :
  - Email: `admin@admin.com`
  - Mot de passe: `admin`

## Instructions d'installation

1. Clonez ce dépôt sur votre machine locale :

   git clone https://github.com/votre-utilisateur/projet_Tp1.git
   cd projet_Tp1
