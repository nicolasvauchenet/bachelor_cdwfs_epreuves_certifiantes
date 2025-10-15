# EC06 – Rattrapage : CI/CD et versionning du module “Alertes et conformité”

## Contexte général

Dans le cadre du projet **FoodSafe**, l’épreuve de rattrapage consiste à mettre en place une
**chaîne d’intégration et de déploiement continu (CI/CD)** spécifique au **module d’alertes et de conformité**.

Ce module a un rôle essentiel dans la fiabilité du système : il gère la réception, la validation et la diffusion des
alertes liées aux produits dangereux ou non conformes.  
L’objectif est d’automatiser les étapes de **test, build et déploiement**, tout en assurant la
**sécurité et la traçabilité** des livrables.

L’apprenant doit structurer le dépôt Git, configurer un pipeline CI/CD, conteneuriser le service et gérer les
déploiements sécurisés sur un environnement cloud ou serveur.

## Livrables attendus

| Livrable              | Détail                                                                   |
|-----------------------|--------------------------------------------------------------------------|
| Dépôt Git             | Organisation des branches (`main`, `dev`, `feature/...`)                 |
| Pipeline CI/CD        | Fichier de configuration (GitLab CI, GitHub Actions, Jenkins, etc.)      |
| Dockerfile            | Image conteneurisée du module d’alertes                                  |
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

- Adopter une **stratégie Git rigoureuse** (Git Flow ou Trunk-Based) pour les modules indépendants
- Conteneuriser le module avec un **Dockerfile multi-stage** optimisé
- Automatiser les étapes de **lint, test, build et déploiement** dans le pipeline
- Sécuriser les variables d’environnement (clés JWT, secrets BDD, tokens API) via le gestionnaire du CI
- Fournir un fichier `.env.dist` clair et documenté
- Documenter le pipeline : étapes, conditions, environnement cible, rollback

## Exemples d’éléments attendus

- Un fichier `.github/workflows/ci.yml` avec étapes `install → test → build → deploy`
- Un `Dockerfile` produisant une image légère, prête pour la production
- Un script `deploy.sh` capable de déployer sur un serveur cloud sécurisé
- Une gestion automatisée des **secrets et tokens** via GitHub Actions ou GitLab
- Des logs ou captures attestant de la réussite du pipeline complet

## Nom de dossier attendu

- Une archive ZIP nommée `EC06R_NomPrenom.zip` contenant :
    - Le dépôt complet (avec `.git` si demandé)
    - Le fichier de configuration CI/CD (`.gitlab-ci.yml`, `.github/workflows/ci.yml` ou équivalent)
    - Le `Dockerfile` et les scripts associés (`deploy.sh`, `run.sh`, etc.)
    - Un `README.md` expliquant la structure et le fonctionnement de la CI/CD

## Rappel pédagogique

Cette épreuve de rattrapage valide les mêmes compétences que l’EC06 initiale :

- Maîtrise du **versionning, de la conteneurisation et de la livraison continue**
- Automatisation des étapes de contrôle qualité et de déploiement
- Sécurisation et documentation des environnements de déploiement

Le scénario change (pipeline dédié au **module d’alertes et conformité** plutôt qu’à l’application globale), mais les
compétences techniques, les pratiques DevOps et le niveau d’exigence restent identiques.
