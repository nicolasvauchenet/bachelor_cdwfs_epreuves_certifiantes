# EC02 – Conception d'interfaces avec Framework

## Contexte général

Dans la continuité du projet **SkillHub**, cette épreuve consiste à développer un **tableau de bord utilisateur** pour
les profils "apprenant" ou "formateur".

Ce dashboard permet de :

- Visualiser les ateliers suivis ou créés
- Gérer les inscriptions à des événements
- Naviguer entre plusieurs vues (listes, filtres…)
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
- Organiser son code avec des **composants réutilisables**
- Mettre en place un **système de routing** clair
- Prévoir un **état global ou local** bien géré
- Respecter les standards d’**accessibilité** (ARIA, navigation clavier)
- Soigner l’UX : gestion des erreurs, navigation fluide, cohérence visuelle

## Exemples d’éléments attendus

- Une **liste d’ateliers** avec pagination ou filtrage dynamique
- Des **cartes d’atelier** avec statut, date, description
- Un **composant de gestion d’inscription**
- Un système de **routing** (ex : `Dashboard`, `Mes Ateliers`, `Créer un Atelier`)
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
- Conception d’une interface **réactive et accessible**
- Capacité à **organiser un projet scalable**

Elle fait le lien entre les fondamentaux du HTML/CSS (évalués en EC01) et les besoins métiers d’une SPA moderne.
