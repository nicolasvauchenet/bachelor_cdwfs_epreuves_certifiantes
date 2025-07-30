# EC04 – API sécurisée et documentée

## Contexte général

Dans le cadre du projet **SkillHub**, cette épreuve consiste à développer une **API publique** permettant aux
utilisateurs d’interagir avec les fonctionnalités de la plateforme.

Cette API doit répondre aux standards actuels en matière de conception, de sécurité et de documentation. L’objectif est
de proposer une API robuste, bien testée et facile à maintenir, tout en garantissant la protection des données
échangées.

Les apprenants sont libres de choisir une architecture REST ou GraphQL, selon les besoins exprimés.

## Livrables attendus

| Livrable          | Détail                                                         |
|-------------------|----------------------------------------------------------------|
| Code source       | Endpoints sécurisés, architecture claire                       |
| Documentation API | Fichier Swagger/OpenAPI ou équivalent                          |
| Tests unitaires   | Couverture des endpoints critiques, rapports générés           |
| README            | Instructions de test, exemples de requêtes, gestion des tokens |

## Modalités d’évaluation

- **Type d’épreuve** : Mise en situation reconstituée sur ordinateur
- **Durée** : 4h
- **Nature** : Épreuve individuelle, sans oral
- **Critères évalués** :
    - C8.3 : Conception d’une API REST sécurisée (auth, JWT, middleware)
    - C8.4 : Documentation complète de l’API
    - C8.5 : Tests unitaires sur les endpoints critiques

## Recommandations

- Implémenter un **système d’authentification** (ex : JWT) clair et documenté
- Organiser son API autour de **ressources cohérentes** (ex : `/users`, `/workshops`)
- Séparer les responsabilités dans le code : contrôleurs, middlewares, services…
- Fournir une **documentation Swagger ou OpenAPI** utilisable sans accompagnement
- Penser à la **gestion des erreurs** (codes HTTP, messages explicites)
- Ajouter des **tests unitaires automatisés** (ex : Jest, PHPUnit, Pytest…)

## Exemples d’éléments attendus

- Un endpoint `GET /users/me` protégé par JWT
- Un endpoint `POST /workshops` avec validation de payload
- Des statuts HTTP clairs (`401`, `403`, `422`, etc.)
- Un fichier `openapi.yaml` documentant toutes les routes
- Des tests affichant un taux de couverture élevé sur les endpoints critiques

## Nom de dossier attendu

- une archive ZIP nommée `EC04_NomPrenom.zip` contenant :
    - Le dossier `src` du projet (API)
    - Le fichier `README.md` avec exemples de requêtes, scripts de lancement
    - La documentation Swagger/OpenAPI
    - Les rapports de tests automatisés

## Rappel pédagogique

Cette épreuve vise à valider la **capacité à exposer une API professionnelle** :

- Sécurisation des accès (authentification, autorisation)
- Structuration claire et maintenable
- Rédaction d’une **documentation technique complète**
- Mise en œuvre de **tests automatisés** sur les routes

Elle prépare les apprenants à l’intégration d’une API dans une application front ou mobile, dans un contexte réaliste
d’équipe.
