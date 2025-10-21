# TP Hibernate - Gestion de Salles et Machines

## Description
Ce projet est un TP de formation sur **Hibernate et JPA**.  
Il permet de gérer des **Salles** et des **Machines** en utilisant Hibernate pour la persistance des données dans une base **MySQL**.  

Le projet comprend :
- Des entités `Salle` et `Machine`
- Des services pour effectuer les opérations CRUD (`SalleService`, `MachineService`)
- Une classe `Test` pour tester les fonctionnalités

---

## Technologies utilisées
- Java 25
- Maven
- Hibernate 5.6.15.Final
- MySQL 8.0.33
- Jakarta Persistence API 2.2.3

---

## Prérequis
- Java JDK installé
- Maven installé
- Base de données MySQL (WAMP/XAMPP ou MySQL natif)
- Git (pour versionner le projet)

---

## Installation
1. Cloner le dépôt :
```bash
git clone https://github.com/hassaneGuedad/tp_Hibernate.git
Importer le projet dans IntelliJ IDEA ou un autre IDE compatible Maven.

Configurer la base de données MySQL dans hibernate.cfg.xml :

xml
Copier le code
<property name="hibernate.connection.url">jdbc:mysql://localhost:3306/nom_de_la_base</property>
<property name="hibernate.connection.username">root</property>
<property name="hibernate.connection.password"></property>
Installer les dépendances Maven :


---
mvn clean install
Exécution
Lancer la classe Test.java pour vérifier les opérations CRUD.

Fonctionnalités
Créer, lire, mettre à jour et supprimer des Salles

Créer, lire, mettre à jour et supprimer des Machines

Lier les machines à des salles (relation @ManyToOne)

Rechercher les machines entre deux dates avec une NamedQuery

Auteur
Hassane Guedad
Étudiant MIAGE, EMSI Marrakech
