# EC02 – Rattrapage : Mini-dashboard “Mes Défis Écologiques”

## Contexte général

Dans le cadre du projet **RebootCamp**, l’épreuve de rattrapage consiste à développer un **mini-dashboard utilisateur**
centré sur la **gestion et le suivi des défis écologiques personnels**.

L’objectif est de démontrer la maîtrise d’un **framework front-end moderne** (React, Vue ou Angular) à travers la
conception d’une interface dynamique, accessible et réactive.  
L’application doit permettre d’afficher les défis actifs, de marquer un défi comme terminé, et de visualiser la
progression de l’utilisateur.

Cette version allégée du dashboard principal doit rester cohérente avec l’univers graphique et la mission de RebootCamp.

## Livrables attendus

| Livrable                        | Détail                                                             |
|---------------------------------|--------------------------------------------------------------------|
| Code source                     | Projet front (React, Vue ou Angular) structuré et fonctionnel      |
| Rapport d’analyse accessibilité | Export Wave ou Lighthouse avec synthèse critique                   |
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

- Créer une **structure claire de composants** (`Dashboard`, `ChallengeList`, `ProgressBar`, `Header`)
- Mettre en place une **gestion d’état** (locale ou globale) pour les défis
- Permettre d’interagir avec les défis (valider un défi, afficher un score, filtrer par catégorie)
- Respecter les **règles d’accessibilité** (focus clavier, contrastes, ARIA, rôles explicites)
- Soigner le **design responsive** (Grid, Flexbox, media queries, CSS utilitaires du framework)
- Fournir un **README** clair expliquant les choix techniques et la logique des composants

## Exemples d’éléments attendus

- Un **composant liste de défis** avec boutons d’action (commencer / terminer)
- Un **composant barre de progression** calculant le taux d’accomplissement
- Un **affichage du score global** (ex. “35 kg de CO₂ évités”)
- Une **navigation simple** entre deux vues : `Mes Défis` et `Statistiques`
- Un **style cohérent et lisible** inspiré de la charte visuelle RebootCamp

## Nom de dossier attendu

- Une archive ZIP nommée `EC02R_NomPrenom.zip` contenant :
    - Le dossier `src` avec le code source complet
    - Un `README.md` expliquant l’organisation du projet et les choix techniques
    - Les rapports d’analyse (accessibilité, structuration)

## Rappel pédagogique

Cette épreuve de rattrapage permet de vérifier la maîtrise des **fondamentaux d’un framework front moderne** :

- Création et composition de composants dynamiques
- Gestion d’un état applicatif cohérent et réactif
- Intégration des **principes d’accessibilité et de design responsive**
- Capacité à produire une interface motivante, centrée sur la progression écologique de l’utilisateur

Le scénario diffère légèrement de l’épreuve initiale (mini-dashboard au lieu du dashboard complet), mais l’objectif
reste identique : démontrer la compréhension et la mise en œuvre des
**principes de conception d’une application front-end modulaire et durable**.
