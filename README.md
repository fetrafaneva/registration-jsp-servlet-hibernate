# Registration JSP Servlet Hibernate

## 📌 Description du projet

**Registration JSP Servlet Hibernate** est une application web Java qui permet la **gestion de l’inscription des utilisateurs** à travers un formulaire web.  
Le projet met en œuvre les technologies **JSP**, **Servlet** et **Hibernate** en respectant l’architecture **MVC (Modèle – Vue – Contrôleur)**.

Il s’agit d’un projet pédagogique visant à illustrer l’intégration de Hibernate pour la persistance des données dans une application web Java.



## 🎯 Objectifs du projet

- Créer un formulaire d’inscription utilisateur
- Traiter les données via des Servlets
- Enregistrer les informations dans une base de données avec Hibernate
- Comprendre l’architecture MVC en Java Web
- Manipuler Hibernate ORM pour les opérations CRUD de base



## 🧩 Thème du projet

> **Développement d’une application web de gestion d’inscription des utilisateurs avec JSP, Servlet et Hibernate**



## 🛠 Technologies utilisées

- **Java**
- **JSP (JavaServer Pages)**
- **Servlet**
- **Hibernate ORM**
- **Base de données MySQL** (ou autre SGBD compatible)
- **Apache Tomcat**
- **HTML / CSS**



## 🏗 Architecture du projet

Le projet suit l’architecture **MVC** :

- **Modèle** : Entités Java mappées avec Hibernate
- **Vue** : Pages JSP pour l’interface utilisateur
- **Contrôleur** : Servlets pour la gestion des requêtes HTTP

## 📁 Structure générale du projet

      registration-jsp-servlet-hibernate
      │
      ├── src/
      │ ├── model/ # Entités Hibernate
      │ ├── dao/ # Accès aux données
      │ ├── servlet/ # Servlets (contrôleurs)
      │ └── util/ # Configuration Hibernate
      │
      ├── WebContent/
      │ ├── register.jsp # Formulaire d'inscription
      │ ├── success.jsp # Page de succès
      │ └── WEB-INF/
      │ └── web.xml
      │
      ├── hibernate.cfg.xml
      └── README.md


## ⚙️ Fonctionnalités principales

- Inscription d’un utilisateur
- Validation des données côté serveur
- Enregistrement des utilisateurs dans la base de données
- Redirection vers une page de confirmation

## 🚀 Installation et exécution

1. Cloner le projet :
   ```bash
   git clone https://github.com/fetrafaneva/registration-jsp-servlet-hibernate.git
2. Importer le projet dans Eclipse ou IntelliJ IDEA

3. Configurer la base de données dans :

hibernate.cfg.xml

4. Ajouter les librairies nécessaires :

Hibernate

JDBC Driver (MySQL)

5. Déployer le projet sur Apache Tomcat

6. Accéder à l’application :

        http://localhost:8080/registration-jsp-servlet-hibernate/
