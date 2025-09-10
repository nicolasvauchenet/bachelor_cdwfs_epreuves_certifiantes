# EC01 – Conception d'interfaces sans Framework

## Contexte général

Dans le cadre du projet fil rouge **RebootCamp**, cette première épreuve consiste à réaliser **la landing page publique
**
de l’application.

Cette page vise à :

- Présenter les enjeux écologiques et la mission de RebootCamp
- Mettre en avant les défis proposés (transport, alimentation, énergie…)
- Inciter les utilisateurs à s’inscrire et rejoindre la communauté
- Offrir une navigation claire, motivante, accessible et responsive

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
- Soigner l’**accessibilité** dès la conception : navigation clavier, contrastes, attributs ARIA
- Penser **responsive design** : viewport, media queries, flexbox ou grid
- Utiliser **JavaScript natif uniquement** : pas de jQuery, pas de framework
- Tester la page sur plusieurs navigateurs et résolutions

## Exemples d’éléments attendus

- Un **menu de navigation** accessible avec clavier et ARIA
- Une **modale d’inscription** (JS natif, gestion du focus, fermeture clavier)
- Un **compteur dynamique** affichant les kg de CO₂ économisés par la communauté
- Une section "Nos Défis" avec **icônes vectorielles** ou images optimisées
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
- Capacité à **produire un livrable autonome, motivant et accessible**

Elle constitue le **socle de compétences** sur lequel les épreuves suivantes viendront se greffer (framework JS, API,
base de données, DevOps…).
