# EC04 – Rattrapage : API sécurisée “Alertes et signalements” et documentée

## Contexte général

Dans le cadre du projet **FoodSafe**, l’épreuve de rattrapage consiste à développer une **API sécurisée** dédiée à la
**gestion des alertes et signalements alimentaires**.

Cette API permet aux utilisateurs de :

- Signaler un produit problématique (ex. : erreur d’étiquetage, réaction allergique, composition incohérente)
- Consulter la liste des alertes publiques validées par les modérateurs
- Rechercher des produits associés à des alertes spécifiques
- Gérer ses signalements personnels en tant qu’utilisateur authentifié

L’objectif est de produire une **API robuste, documentée et testée**, respectant les bonnes pratiques de sécurité et de
structuration.  
L’architecture peut être **REST** ou **GraphQL**, selon le choix argumenté de l’apprenant.

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

- Implémenter une **authentification JWT** claire et documentée
- Organiser l’API autour de ressources cohérentes (`/alerts`, `/products`, `/users`)
- Séparer les rôles et droits d’accès (ex. utilisateur / modérateur)
- Fournir une **documentation Swagger/OpenAPI** complète et exploitable
- Tester les scénarios critiques : création d’alerte, récupération, suppression, autorisation
- Gérer les erreurs avec des **codes HTTP standardisés** et des messages explicites

## Exemples d’éléments attendus

- `POST /alerts` : création d’une alerte, protégée par JWT
- `GET /alerts/public` : récupération des alertes validées (publique)
- `GET /alerts/mine` : récupération des signalements de l’utilisateur connecté
- `DELETE /alerts/:id` : suppression d’une alerte (autorisation requise)
- Un fichier `openapi.yaml` décrivant toutes les routes et leurs paramètres
- Des tests unitaires affichant une couverture élevée sur les endpoints sensibles

## Nom de dossier attendu

- Une archive ZIP nommée `EC04R_NomPrenom.zip` contenant :
    - Le dossier `src` du projet (API)
    - Le fichier `README.md` avec exemples de requêtes et scripts de lancement
    - La documentation Swagger/OpenAPI
    - Les rapports de tests automatisés

## Rappel pédagogique

Cette épreuve de rattrapage valide les mêmes compétences que l’EC04 initiale :

- Développement d’une **API sécurisée, claire et maintenable**
- Production d’une **documentation technique complète et normalisée**
- Mise en œuvre de **tests automatisés** pour assurer la fiabilité des endpoints

Le scénario change (API centrée sur les **alertes et signalements** plutôt que sur la recherche et les favoris), mais le
niveau d’exigence et les objectifs pédagogiques restent identiques.
