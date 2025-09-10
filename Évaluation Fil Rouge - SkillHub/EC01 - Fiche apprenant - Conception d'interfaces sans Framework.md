# EC01 – Conception d'interfaces sans Framework

## Contexte général

Dans le cadre du projet fil rouge **SkillHub**, cette première épreuve consiste à réaliser **la landing page publique**
de la plateforme.

Cette page vise à :

- Présenter la plateforme et ses valeurs
- Inciter les utilisateurs (formateurs ou apprenants) à s’inscrire
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

- Respecter la **sémantique HTML5** : utiliser des balises structurantes (`<header>`, `<section>`, `<nav>`, etc.)
- Soigner l’**accessibilité** dès le départ : navigation clavier, contrastes, attributs ARIA
- Penser **responsive design** : viewport, media queries, flexbox ou grid
- Utiliser **JavaScript natif uniquement** : pas de jQuery, pas de framework
- Tester sur plusieurs navigateurs et résolutions

## Exemples d’éléments attendus

- Un **menu déroulant** accessible (nav clavier, aria-expanded…)
- Une **modale d’inscription** (JS natif, focus géré, clavier)
- Un formulaire avec **validation côté client**
- Une section "Nos valeurs" avec des **icônes vectorielles ou images optimisées**
- Des **media queries** efficaces pour desktop, tablette, mobile

## Nom de dossier attendu

- une archive ZIP nommée `EC01_NomPrenom.zip` contenant :
    - Le dossier `src` avec le code source
    - Un fichier `README.md` décrivant l’architecture et les choix techniques
    - Les rapports d’analyse (accessibilité, structuration HTML)

## Rappel pédagogique

Cette première épreuve vise à évaluer les **fondamentaux de l’intégration web** :

- Respect des standards HTML5/CSS3
- Compréhension des enjeux d’**accessibilité** et de **structure sémantique**
- Mise en place d’**interactions simples sans dépendance externe**
- Capacité à **produire un livrable autonome et accessible**

Elle est conçue comme un **socle de compétences**, sur lequel les épreuves suivantes viendront se greffer (framework JS,
API, base de données…).
