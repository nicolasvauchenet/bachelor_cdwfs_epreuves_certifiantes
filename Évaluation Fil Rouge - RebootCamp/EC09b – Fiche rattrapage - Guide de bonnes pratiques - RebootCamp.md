# EC09 – Rattrapage : Mini-guide de bonnes pratiques éco-conçu

## Contexte général

Dans le cadre du projet **RebootCamp**, cette épreuve de rattrapage consiste à rédiger un
**mini-guide de bonnes pratiques** destiné à assurer la **qualité, la maintenabilité et la sobriété du code** au sein de
l’équipe de développement.

Ce document doit rassembler les **règles essentielles de qualité logicielle**, les
**bonnes pratiques d’éco-conception web**, et une **approche mesurable des tests et de la documentation**.  
L’objectif est de produire un guide **concret, utilisable et illustré** — court mais professionnel.

## Livrables attendus

| Livrable                 | Détail                                                               |
|--------------------------|----------------------------------------------------------------------|
| Mini-guide (.md ou .pdf) | Document synthétique, clair et structuré (2 à 4 pages max)           |
| Exemples concrets        | Bonnes/mauvaises pratiques, conventions Git ou code                  |
| Mini-plan de test        | Tableau ou schéma simple de la stratégie de tests et outils associés |

## Modalités d’évaluation

- **Type d’épreuve** : Mise en situation reconstituée écrite
- **Durée** : 4h
- **Nature** : Épreuve individuelle
- **Critères évalués** :
    - C8.6 : Conventions et documentation
    - C9.6 : Stratégie de tests adaptée
    - C14.3 : Approche pragmatique de la qualité logicielle

## Recommandations

- Structurer le guide en **3 à 4 parties maximum** :
    1. Règles de code et conventions (noms, structure, commentaires)
    2. Bonnes pratiques Git (branches, commits, PR)
    3. Éco-conception et performance (optimisations simples et mesurables)
    4. Tests et documentation (outils, couverture, critères de qualité)
- Fournir des **exemples concrets** (extraits de code, captures, checklists)
- Intégrer des **bonnes pratiques écologiques** :
    - Limiter les dépendances lourdes
    - Réduire les requêtes et les ressources statiques
    - Utiliser des images compressées et du cache navigateur
    - Optimiser les builds et les pipelines
- Rester concis, visuel et immédiatement exploitable par une équipe technique

## Exemples d’éléments attendus

### Exemple de conventions de code

```javascript
// ✅ Bon exemple
const userScore = calculateScore(user);

// ❌ Mauvais exemple
var x = calc(user);
```

### Exemple de conventions Git

- Branches : `feat/`, `fix/`, `hotfix/`, `release/`
- Commits clairs et liés à des issues :  
  `feat(api): add endpoint for badges`

### Exemple de checklist de revue de code

- [ ] Nommage clair
- [ ] Pas de duplication
- [ ] Tests associés présents
- [ ] Respect des normes RGPD et accessibilité

### Exemple de stratégie de tests

| Type        | Outil     | Objectif                             |
|-------------|-----------|--------------------------------------|
| Unitaire    | Jest      | Vérifier la logique métier           |
| Intégration | SuperTest | Tester les routes API                |
| E2E         | Cypress   | Simuler les interactions utilisateur |

## Nom de dossier attendu

- Une archive ZIP nommée `EC09R_NomPrenom.zip` contenant :
    - Le fichier `mini-guide-bonnes-pratiques.md` (ou `.pdf`)
    - Un dossier `exemples/` avec extraits, scripts ou captures
    - (Optionnel) un `README.md` présentant la démarche adoptée

## Rappel pédagogique

Cette épreuve de rattrapage vise à évaluer la **capacité à formaliser et appliquer des règles de qualité logicielle** :

- Production d’un guide **simple, structuré et applicable**
- Mise en avant de **bonnes pratiques durables** (code, Git, CI/CD, tests)
- Intégration de principes d’**éco-conception numérique**
- Capacité à **communiquer des standards techniques** à une équipe

Elle prépare à des situations professionnelles concrètes de
**revue de code, documentation interne et amélioration continue** dans un contexte d’équipe.

