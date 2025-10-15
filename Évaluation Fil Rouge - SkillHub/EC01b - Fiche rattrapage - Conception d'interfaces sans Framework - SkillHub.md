# EC01 – Rattrapage : Conception d’une page d’atelier sans Framework

## Contexte général

Dans le cadre du projet fil rouge **SkillHub**, l’épreuve de rattrapage consiste à concevoir une
**page publique de présentation d’un atelier** (ex. : *“Découverte de JavaScript”*).

Cette page doit permettre de :

- Mettre en valeur le contenu et les objectifs de l’atelier
- Donner envie à l’utilisateur de s’inscrire
- Offrir une navigation accessible et responsive

Il s’agit d’une épreuve **individuelle**, réalisée **sans framework**, en HTML5/CSS3 et JavaScript natif.

## Livrables attendus

| Livrable                        | Détail                                                           |
|---------------------------------|------------------------------------------------------------------|
| Code source                     | HTML5, CSS3, JavaScript natif                                    |
| Rapport d’analyse accessibilité | Export Wave ou Lighthouse, décrivant les améliorations possibles |
| Rapport de structuration HTML   | Analyse Lighthouse sur la sémantique et la structure du DOM      |

## Modalités d’évaluation

- **Type d’épreuve** : Mise en situation reconstituée sur ordinateur
- **Durée** : 4h
- **Nature** : Épreuve individuelle, sans oral
- **Critères évalués** :
    - C1.1 : Responsive Web Design sans framework (HTML/CSS)
    - C1.2 : Accessibilité (ARIA, contrastes, navigation clavier)
    - C2.1 : Structuration HTML sémantique

## Recommandations

- Respecter la **sémantique HTML5** (`<article>`, `<aside>`, `<figure>`, `<footer>`…)
- Soigner l’**accessibilité** : aria-labels, contrastes, navigation clavier
- Penser **responsive design** : media queries, grid/flexbox
- Utiliser **JavaScript natif uniquement** : pas de librairie externe
- Vérifier la compatibilité sur plusieurs résolutions

## Exemples d’éléments attendus

- Une **section de présentation** avec visuel (image optimisée ou icône SVG)
- Un **programme détaillé** de l’atelier, structuré en `<section>`
- Un **formulaire d’inscription** avec validation côté client
- Une **modale de confirmation d’inscription** gérée au clavier et accessible
- Un **menu secondaire** (ex. : “Programme / Formateur / Inscription”) accessible et responsive

## Nom de dossier attendu

- Une archive ZIP nommée `EC01R_NomPrenom.zip` contenant :
    - Le dossier `src` avec le code source
    - Un fichier `README.md` décrivant l’architecture et les choix techniques
    - Les rapports d’analyse (accessibilité, structuration HTML)

## Rappel pédagogique

Cette épreuve de rattrapage vise à valider les mêmes compétences que l’EC01 initiale :

- Maîtrise des **fondamentaux de l’intégration web** sans framework
- Capacité à produire une **page responsive, sémantique et accessible**
- Mise en œuvre d’**interactions simples** en JavaScript natif

La thématique change (page d’atelier plutôt que landing page générale), mais le niveau d’exigence reste identique.
