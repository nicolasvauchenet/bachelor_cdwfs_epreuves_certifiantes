# EC04 – Rattrapage : API sécurisée “Gestion des inscriptions” et documentée

## Contexte général

Dans le cadre du projet **SkillHub**, l’épreuve de rattrapage consiste à développer une **API sécurisée** dédiée à la *
*gestion des inscriptions aux ateliers**.

Cette API doit permettre :

- D’inscrire un apprenant à un atelier
- De lister les inscriptions d’un utilisateur connecté
- De gérer l’annulation d’une inscription

L’API doit respecter les standards actuels de conception, de sécurité et de documentation, et être fournie avec des *
*tests unitaires automatisés**.

L’architecture (REST ou GraphQL) est laissée au choix de l’apprenant, à condition d’être clairement justifiée.

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

- Mettre en place une **authentification JWT** claire et documentée
- Organiser l’API autour de ressources cohérentes (ex. : `/registrations`, `/workshops/:id/registrations`)
- Gérer les erreurs de manière explicite (codes HTTP standardisés, messages clairs)
- Produire une **documentation Swagger/OpenAPI** exhaustive et utilisable par un développeur externe
- Rédiger des **tests unitaires automatisés** sur les routes critiques (ex. : inscription et annulation)

## Exemples d’éléments attendus

- Un endpoint `POST /registrations` permettant à un utilisateur de s’inscrire à un atelier
- Un endpoint `GET /registrations/me` listant ses inscriptions
- Un endpoint `DELETE /registrations/:id` pour annuler une inscription
- Des statuts HTTP clairs (`200`, `201`, `400`, `401`, `403`, `404`)
- Un fichier `openapi.yaml` décrivant toutes les routes et leurs paramètres
- Des tests affichant un taux de couverture élevé sur les endpoints critiques

## Nom de dossier attendu

- Une archive ZIP nommée `EC04R_NomPrenom.zip` contenant :
    - Le dossier `src` du projet (API)
    - Le fichier `README.md` avec exemples de requêtes, scripts de lancement
    - La documentation Swagger/OpenAPI
    - Les rapports de tests automatisés

## Rappel pédagogique

Cette épreuve de rattrapage vise à valider les mêmes compétences que l’EC04 initiale :

- Développement d’une **API sécurisée et robuste**
- Structuration claire et maintenable du code back-end
- Production d’une **documentation technique complète et exploitable**
- Mise en œuvre de **tests unitaires** garantissant la fiabilité des endpoints

Le scénario change (gestion des inscriptions au lieu de gestion générale des utilisateurs et ateliers), mais le niveau
et les objectifs restent identiques.
