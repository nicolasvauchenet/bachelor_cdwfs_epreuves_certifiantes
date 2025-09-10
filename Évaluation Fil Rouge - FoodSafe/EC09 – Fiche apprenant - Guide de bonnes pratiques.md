# EC09 – Guide de bonnes pratiques

## Contexte général

Dans le cadre du projet **FoodSafe**, cette épreuve consiste à rédiger un **guide interne de qualité logicielle**, à
destination de l’équipe de développement.

Ce guide doit formaliser un ensemble de règles et recommandations permettant de garantir un **code propre, maintenable,
sécurisé et bien documenté**, avec une attention particulière portée à la **gestion des données sensibles liées à la
santé**. Il servira de référence lors de l’onboarding, des revues de code et des sprints agiles.

L’objectif est de structurer des pratiques professionnelles réutilisables dans tous les projets collaboratifs, et
d’assurer la conformité du projet aux standards de qualité, de sécurité et de protection des données.

## Livrables attendus

| Livrable                  | Détail                                                                  |
|---------------------------|-------------------------------------------------------------------------|
| Guide de bonnes pratiques | Rédigé en markdown ou PDF, structuré, clair, exploitable par une équipe |
| Exemples de conventions   | Normes de code, Git, structure de projet, checklist de review           |
| Plan de test / couverture | Stratégie de tests avec exemples d’outils ou de mise en œuvre           |

## Modalités d’évaluation

- **Type d’épreuve** : Mise en situation reconstituée écrite
- **Durée** : 4h
- **Nature** : Épreuve individuelle, sans oral
- **Critères évalués** :
    - C8.6 : Conventions de code et documentation
    - C9.6 : Stratégie de tests
    - C14.3 : Qualité logicielle globale (approche mesurable et réaliste)

## Recommandations

- Produire un guide **concret et applicable** plutôt que théorique
- Structurer avec des titres clairs, des checklists et des exemples de bonnes/mauvaises pratiques
- Citer les **outils recommandés** : linters, formatters, gestion des secrets, analyseurs de vulnérabilités
- Adopter une **approche pragmatique** adaptée au contexte FoodSafe (sécurité, RGPD, accessibilité)
- Inclure des **exemples de code** et de configuration (Git, CI/CD, Docker)

## Exemples d’éléments attendus

- Conventions de nommage (`camelCase`, `snake_case`, `PascalCase`) et règles pour les schémas BDD
- Normes Git (`feat/`, `fix/`, `hotfix/`, `release/`) et gestion des pull requests
- Checklist de revue de code : lisibilité, duplications, performance, sécurité (XSS, injections, RGPD)
- Stratégie de tests : unitaire, intégration, E2E, avec outils proposés (Jest, PHPUnit, Cypress, etc.)
- Exigences de documentation minimale : `README.md`, schémas d’architecture, commentaires obligatoires sur modules
  critiques

## Nom de dossier attendu

- une archive ZIP nommée `EC09_NomPrenom.zip` contenant :
    - Le guide au format `.md` ou `.pdf`
    - Un fichier d’exemples ou un sous-dossier `exemples/`
    - Éventuellement un `README.md` expliquant les choix du guide

## Rappel pédagogique

Cette épreuve vise à valider la **capacité à structurer et formaliser les pratiques de qualité logicielle** :

- Clarification des règles de code et d’organisation d’un projet collaboratif
- Mise en œuvre de stratégies de **tests réalistes, mesurables et adaptés aux données sensibles**
- Valorisation de la **documentation technique** comme outil de collaboration et de conformité

Elle donne aux apprenants les outils pour **travailler efficacement en équipe** et **maintenir un haut niveau de
qualité et de sécurité**, essentiel pour un projet tel que FoodSafe.
