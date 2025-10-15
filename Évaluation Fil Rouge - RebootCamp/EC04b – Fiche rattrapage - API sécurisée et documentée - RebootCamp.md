# EC04 – Rattrapage : Mini-API “Défis et Classement”

## Contexte général

Dans le cadre du projet **RebootCamp**, l’épreuve de rattrapage consiste à concevoir une **mini-API sécurisée**
permettant de gérer les **défis écologiques** et le **classement des écocitoyens**.

L’objectif est de démontrer la capacité à concevoir une API REST simple mais robuste, avec une authentification
sécurisée, une documentation claire et des tests automatisés sur les endpoints principaux.

Cette API doit refléter les standards professionnels : lisibilité du code, gestion des statuts HTTP, séparation des
responsabilités et clarté de la documentation.

## Livrables attendus

| Livrable          | Détail                                                         |
|-------------------|----------------------------------------------------------------|
| Code source       | Endpoints sécurisés, structure claire (contrôleurs, services)  |
| Documentation API | Fichier Swagger/OpenAPI ou équivalent                          |
| Tests unitaires   | Couverture minimale sur les routes principales                 |
| README            | Instructions de test, exemples de requêtes, gestion des tokens |

## Modalités d’évaluation

- **Type d’épreuve** : Mise en situation reconstituée sur ordinateur
- **Durée** : 4h
- **Nature** : Épreuve individuelle, sans oral
- **Critères évalués** :
    - C8.3 : Conception d’une API REST sécurisée (auth, JWT, middleware)
    - C8.4 : Documentation complète et conforme aux standards
    - C8.5 : Tests unitaires sur les endpoints critiques

## Recommandations

- Implémenter un **système d’authentification JWT** simple et fonctionnel
- Organiser les routes autour des **ressources clés** :
    - `/challenges` → Liste et validation des défis
    - `/leaderboard` → Classement général
- Séparer les **couches logiques** : routes, contrôleurs, services, middlewares
- Fournir une **documentation Swagger/OpenAPI** lisible et testable
- Ajouter des **tests automatisés** pour au moins deux endpoints
- Utiliser des **statuts HTTP pertinents** et des messages d’erreur explicites

## Exemples d’éléments attendus

- `GET /challenges` → Retourne la liste des défis disponibles
- `POST /challenges/:id/complete` → Marque un défi comme réalisé (JWT requis)
- `GET /leaderboard` → Retourne le top 5 des écocitoyens classés par score
- `GET /users/me` → Retourne les infos de l’utilisateur connecté (JWT)
- Un fichier `openapi.yaml` décrivant les endpoints, paramètres et réponses

## Nom de dossier attendu

- Une archive ZIP nommée `EC04R_NomPrenom.zip` contenant :
    - Le dossier `src` du projet (API)
    - Le fichier `README.md` avec les commandes de test et d’exécution
    - Le fichier `openapi.yaml` ou équivalent
    - Les rapports de tests automatisés

## Rappel pédagogique

Cette épreuve de rattrapage évalue la **maîtrise des bases d’une API moderne** :

- Sécurisation des endpoints et gestion des rôles utilisateurs
- Structuration claire du code (architecture REST maintenable)
- Production d’une **documentation professionnelle** (Swagger/OpenAPI)
- Mise en œuvre de **tests automatisés ciblés** sur les fonctionnalités essentielles

Elle conserve l’esprit du projet RebootCamp en mettant en avant des valeurs de
**fiabilité, transparence et collaboration**, tout en permettant de valider les compétences fondamentales en back-end
sécurisé.
