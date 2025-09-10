# EC03 – Développement back-end avec BDD relationnelle + NoSQL

## Contexte général

Dans le cadre du projet **SkillHub**, cette épreuve consiste à développer une partie du back-end dédiée à la **gestion
des utilisateurs**, en manipulant à la fois une base **relationnelle** et une base **NoSQL**.

Le socle technique est fourni : authentification en place, environnement Docker, bases de données initialisées (
PostgreSQL + MongoDB), et une documentation fonctionnelle. L’objectif est de mettre en œuvre des opérations ciblées sur
ces deux types de bases.

L’évaluation porte autant sur l’écriture de code que sur la capacité à justifier les choix techniques.

## Livrables attendus

| Livrable              | Détail                                                             |
|-----------------------|--------------------------------------------------------------------|
| Code source           | Développement en POO / MVC avec BDD relationnelle ET NoSQL         |
| Dump SQL et JSON      | Extraits de données (PostgreSQL et MongoDB)                        |
| Scripts de sauvegarde | `backup.sh`, `restore.sh` pour les deux bases                      |
| README                | Justification des choix techniques, commandes terminal, arbitrages |

## Modalités d’évaluation

- **Type d’épreuve** : Mise en situation reconstituée sur ordinateur
- **Durée** : 4h
- **Nature** : Épreuve individuelle, sans oral
- **Critères évalués** :
    - C7.1 : Configuration environnement de dev (Docker, terminal)
    - C8.1 : Programmation orientée objet, architecture MVC
    - C9 : Sécurisation, optimisation du serveur
    - C10 : Utilisation de base de données relationnelle (PostgreSQL)
    - C11 : Utilisation de base de données NoSQL (MongoDB)
    - C12 : Justification des choix BDD (SQL vs NoSQL)
    - C13 : Mise en place de la sauvegarde et restauration

## Recommandations

- Penser dès le début à la **séparation des responsabilités** (MVC)
- Respecter les bonnes pratiques de **sécurité serveur** (headers, env, accès BDD)
- Utiliser **des migrations** ou scripts pour la base SQL
- Fournir des **dumps cohérents** et testables
- Documenter les **choix techniques** dans le README
- Scripter des commandes simples pour lancer, tester, sauvegarder

## Exemples d’éléments attendus

- Une entité `User` persistée dans PostgreSQL avec migrations
- Une collection `Sessions` ou `Logs` dans MongoDB
- Une route protégée (JWT) listant les données combinées
- Un fichier `.env` clair, des logs, un `docker-compose.yml` fonctionnel
- Des captures de terminal montrant les commandes utilisées

## Nom de dossier attendu

- une archive ZIP nommée `EC03_NomPrenom.zip` contenant :
    - Le dossier `src` du projet
    - Le fichier `README.md` avec explications techniques
    - Le dump SQL (`/data/skillhub.sql`) et le dump Mongo (`/data/mongo.json`)
    - Les scripts `backup.sh` et `restore.sh`

## Rappel pédagogique

Cette épreuve permet d’évaluer la **capacité à manipuler des architectures back-end réalistes**, en incluant :

- La **programmation orientée objet** et l’usage d’un framework MVC
- L’exploitation de **deux types de bases de données complémentaires**
- La maîtrise de l’**environnement de développement** (Docker, terminal)
- La capacité à **justifier techniquement des arbitrages**

Elle introduit une logique métier complète, et prépare à la structuration d’API sécurisées (EC04).
