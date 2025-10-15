# EC06 – Rattrapage : CI/CD et versionning pour le module API

## Contexte général

Dans le cadre du projet **SkillHub**, l’épreuve de rattrapage consiste à mettre en œuvre une
**chaîne d’intégration et de déploiement continu** spécifiquement dédiée au **module API** (back-end).

L’objectif est de garantir la qualité, la traçabilité et la reproductibilité des livrables grâce à un pipeline CI/CD
bien structuré.  
L’apprenant doit configurer un dépôt Git clair, conteneuriser l’API, automatiser son déploiement sécurisé et documenter
le processus complet.

## Livrables attendus

| Livrable              | Détail                                                                   |
|-----------------------|--------------------------------------------------------------------------|
| Dépôt Git             | Organisation des branches (`main`, `dev`, `feature/...`)                 |
| Pipeline CI/CD        | Fichier de configuration (GitLab CI, GitHub Actions, Jenkins, etc.)      |
| Dockerfile            | Image conteneurisée de l’API                                             |
| Script de déploiement | Automatisation du déploiement avec gestion des variables d’environnement |
| README                | Documentation du processus complet : CI, Docker, déploiement             |

## Modalités d’évaluation

- **Type d’épreuve** : Mise en situation reconstituée sur ordinateur
- **Durée** : 4h
- **Nature** : Épreuve individuelle, sans oral
- **Critères évalués** :
    - C7.3 : Structuration du dépôt Git
    - C9.4 : Mise en place d’un pipeline CI/CD
    - C9.5 : Déploiement sécurisé via conteneurisation

## Recommandations

- Mettre en place une **stratégie Git claire** adaptée au développement collaboratif
- Versionner tout : code, scripts, configurations
- Construire un **Dockerfile optimisé** pour l’API (multistage build recommandé)
- Ajouter des étapes de **lint, tests et build** dans le pipeline
- Sécuriser les secrets (tokens, clés API, DB) via les variables d’environnement du CI
- Fournir un **fichier `.env.dist`** pour simplifier la reproduction du setup

## Exemples d’éléments attendus

- Un pipeline CI avec étapes : install → lint → test → build → deploy
- Un Dockerfile multistage générant une image optimisée pour l’API en production
- Un fichier `.env.dist` et gestion des secrets sécurisée dans le CI
- Des captures de builds et déploiements réussis (logs CI/CD)
- Un script `deploy.sh` ou équivalent automatisant la mise en production

## Nom de dossier attendu

- Une archive ZIP nommée `EC06R_NomPrenom.zip` contenant :
    - Le dépôt complet (avec `.git` si demandé)
    - Le fichier `.gitlab-ci.yml`, `.github/workflows/ci.yml` ou équivalent
    - Le `Dockerfile` et les scripts associés (`deploy.sh`, `run.sh`, etc.)
    - Un `README.md` expliquant le fonctionnement du pipeline CI/CD

## Rappel pédagogique

Cette épreuve de rattrapage valide les mêmes compétences que l’EC06 initiale :

- Structuration et suivi via **Git et branches organisées**
- Automatisation des étapes clés (tests, build, déploiement)
- Conteneurisation avec **Docker** pour homogénéiser les environnements
- Sécurisation et professionnalisation du processus CI/CD

Le scénario change (focalisation sur le module API au lieu de la plateforme complète), mais les objectifs et le niveau
restent identiques.
