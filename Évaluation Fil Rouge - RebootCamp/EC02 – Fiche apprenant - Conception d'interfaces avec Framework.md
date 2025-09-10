# EC02 – Conception d'interfaces avec Framework

## Contexte général

Dans la continuité du projet **RebootCamp**, cette épreuve consiste à développer un **tableau de bord utilisateur**
permettant de suivre ses défis écologiques et sa progression.

Ce dashboard permet de :

- Visualiser les défis en cours et ceux réalisés
- Suivre la progression et les **badges obtenus**
- Consulter le **classement des écocitoyens** et comparer son score
- Naviguer entre plusieurs vues (liste de défis, filtres par catégorie, statistiques)
- Réaliser des interactions riches via un framework front-end

L’épreuve met l’accent sur la réutilisabilité des composants, l’accessibilité, et l’organisation du code.

## Livrables attendus

| Livrable                        | Détail                                                             |
|---------------------------------|--------------------------------------------------------------------|
| Code source                     | Projet front (React, Vue ou Angular), bien structuré               |
| Rapport d’analyse accessibilité | Export Wave ou Lighthouse, décrivant les améliorations possibles   |
| Rapport de structuration front  | Analyse Lighthouse sur l’organisation des composants et du routing |

## Modalités d’évaluation

- **Type d’épreuve** : Mise en situation reconstituée sur ordinateur
- **Durée** : 4h
- **Nature** : Épreuve individuelle, sans oral
- **Critères évalués** :
    - C1.3 : Responsive Web Design avec framework
    - C1.4 : Accessibilité avec framework
    - C2.2 : Structuration du front-end (composants, routing, état)

## Recommandations

- Utiliser un **framework moderne** (React, Vue ou Angular) selon les consignes
- Organiser le code en **composants réutilisables** (carte défi, carte badge, liste filtrée, etc.)
- Mettre en place un **système de routing clair** (`Dashboard`, `Mes Défis`, `Classement`, `Statistiques`)
- Gérer un **état global ou local** pour les défis et la progression
- Respecter les standards d’**accessibilité** (navigation clavier, ARIA, contrastes)
- Soigner l’UX : feedback visuel sur la progression, gestion des erreurs, cohérence graphique

## Exemples d’éléments attendus

- Une **liste de défis** avec filtrage par thématique (transport, énergie, alimentation)
- Des **cartes utilisateur** présentant progression et badges
- Un **composant de classement** affichant le top 10 des écocitoyens
- Un **système de routing** clair et fonctionnel
- Des **tests de responsivité** (Grid/Flexbox, media queries ou utilitaires CSS du framework)

## Nom de dossier attendu

- une archive ZIP nommée `EC02_NomPrenom.zip` contenant :
    - Le dossier `src` du projet front
    - Un fichier `README.md` décrivant l’architecture, le choix du framework, la structure des composants
    - Les rapports d’analyse (accessibilité, structuration)

## Rappel pédagogique

Cette épreuve permet d’évaluer la **capacité à structurer un front-end moderne** :

- Maîtrise des concepts clés d’un framework (composants, routing, état)
- Mise en œuvre de **comportements interactifs** et d’**affichages dynamiques**
- Conception d’une interface **réactive, accessible et motivante**
- Capacité à **organiser un projet scalable**

Elle fait le lien entre les fondamentaux du HTML/CSS (évalués en EC01) et les besoins métiers d’une SPA moderne autour
de la gamification et de l’écologie.
