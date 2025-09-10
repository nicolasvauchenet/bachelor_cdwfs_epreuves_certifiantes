# EC09 – Rattrapage : Guide de bonnes pratiques (revues de code et documentation)

## Contexte général

Dans le cadre du projet **SkillHub**, l’épreuve de rattrapage consiste à rédiger un **guide interne de qualité
logicielle** centré sur deux axes prioritaires :

1. Les **revues de code** (checklists, critères, organisation des revues)
2. La **documentation technique minimale** à fournir dans le projet (README, schémas, commentaires, API docs)

Ce guide doit être exploitable directement par l’équipe de développement et servir de référence dans les prochains
sprints.  
Il doit être concret, structuré et illustré d’exemples clairs.

## Livrables attendus

| Livrable                  | Détail                                                                |
|---------------------------|-----------------------------------------------------------------------|
| Guide de bonnes pratiques | Rédigé en markdown ou PDF, structuré, clair, exploitable par l’équipe |
| Checklists                | Modèles de checklist de revue de code, critères de validation         |
| Documentation type        | Exemples de fichiers/documentation minimale attendue dans un projet   |

## Modalités d’évaluation

- **Type d’épreuve** : Mise en situation reconstituée écrite
- **Durée** : 4h
- **Nature** : Épreuve individuelle, sans oral
- **Critères évalués** :
    - C8.6 : Conventions de code et documentation
    - C9.6 : Stratégie de tests intégrée aux revues de code
    - C14.3 : Qualité logicielle globale (approche mesurable et réaliste)

## Recommandations

- Structurer le guide par **sections thématiques** (naming, Git, revue, doc, tests)
- Fournir des **checklists prêtes à l’emploi** (ex. : “avant merge, vérifier que…”)
- Inclure des **exemples concrets** de documentation : README modèle, commentaires de code, schéma UML ou Markdown
- Mentionner les **outils de support** (linters, CI/CD, générateurs de doc)
- Garder une approche **pragmatique et adaptée à SkillHub**

## Exemples d’éléments attendus

- Checklist de revue de code (lisibilité, duplication, sécurité, testabilité)
- Modèle de `README.md` standardisé (installation, usage, scripts, tests)
- Exigences minimales pour la documentation API (Swagger, OpenAPI)
- Exemple de **commentaires clairs** (bonne pratique vs mauvaise pratique)
- Rappel des conventions Git (`feat/`, `fix/`, `refactor/`) appliquées aux PR

## Nom de dossier attendu

- Une archive ZIP nommée `EC09R_NomPrenom.zip` contenant :
    - Le guide au format `.md` ou `.pdf`
    - Un dossier `checklists/` avec les modèles prêts à l’emploi
    - Un dossier `doc-exemples/` avec README, schéma, ou exemples de commentaires

## Rappel pédagogique

Cette épreuve de rattrapage valide les mêmes compétences que l’EC09 initiale :

- Capacité à **formaliser et structurer les pratiques de qualité logicielle**
- Production d’outils concrets pour améliorer la **collaboration et la relecture de code**
- Mise en valeur de la **documentation technique** comme levier d’efficacité en équipe

Le scénario change (focus sur **revues de code et documentation minimale** plutôt que guide général), mais le niveau et
les objectifs restent identiques.
