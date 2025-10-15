# EC01 – Rattrapage : Conception d’une page “Allergènes du jour” sans Framework

## Contexte général

Dans le cadre du projet fil rouge **FoodSafe**, l’épreuve de rattrapage consiste à concevoir une
**page d’information dynamique** présentant les **“Allergènes du jour”**, c’est-à-dire une liste mise à jour d’aliments
ou de produits signalés comme à risque (ex. rappels alimentaires).

Cette page doit être **pédagogique, responsive et accessible**, tout en permettant des
**interactions simples en JavaScript natif** (ex. affichage détaillé, filtres par type d’allergène, modale
d’avertissement).

Elle vise à évaluer la capacité de l’apprenant à produire une interface claire, structurée et conforme aux standards
web, sans recourir à un framework.

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

- Respecter la **sémantique HTML5** : balises structurantes (`<header>`, `<main>`, `<article>`, `<footer>`)
- Soigner l’**accessibilité** : navigation clavier, aria-labels, contraste suffisant
- Penser **responsive** : layout adaptatif avec flexbox ou grid
- Utiliser **JavaScript natif uniquement** pour les interactions
- Tester la **compatibilité multi-supports** (mobile, tablette, desktop)
- Ajouter des **icônes accessibles** pour les types d’allergènes (gluten, lactose, arachides, etc.)

## Exemples d’éléments attendus

- Une **liste d’allergènes à risque** avec filtres dynamiques (JS natif)
- Une **modale d’avertissement** ou d’explication pour un allergène sélectionné
- Un **menu d’accessibilité rapide** (contrastes, taille de texte)
- Un **footer informatif** avec lien vers les sources officielles (DGCCRF, Santé publique)
- Des **media queries** efficaces pour tous les formats d’écran

## Nom de dossier attendu

- Une archive ZIP nommée `EC01R_NomPrenom.zip` contenant :
    - Le dossier `src` avec le code source
    - Un fichier `README.md` décrivant l’architecture et les choix techniques
    - Les rapports d’analyse (accessibilité, structuration HTML)

## Rappel pédagogique

Cette épreuve de rattrapage valide les mêmes compétences que l’EC01 initiale :

- Maîtrise du **responsive design et de la sémantique HTML5**
- Capacité à créer une interface **accessible et claire**
- Utilisation de **JavaScript natif** pour des interactions simples et robustes

Le scénario change (page d’information dynamique au lieu de landing page), mais le niveau et les objectifs restent
identiques.
