# EC02 – Rattrapage : Conception d’un module “Mes Messages” avec Framework

## Contexte général

Dans la continuité du projet **SkillHub**, l’épreuve de rattrapage consiste à développer une **interface utilisateur de
messagerie interne** (ex. : échanges entre formateur et apprenant au sujet d’un atelier).

Ce module doit permettre de :

- Visualiser la liste des conversations
- Consulter le contenu d’un message
- Envoyer un nouveau message
- Naviguer entre différentes vues (conversations, message détaillé, nouvel envoi)

L’épreuve met l’accent sur la réutilisabilité des composants, l’accessibilité, et l’organisation du code avec un *
*framework moderne** (React, Vue ou Angular).

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
- Organiser le code en **composants réutilisables** (liste, message, formulaire d’envoi…)
- Mettre en place un **routing clair** (ex. : `/conversations`, `/message/:id`, `/nouveau`)
- Gérer l’**état global ou local** pour stocker les messages et conversations
- Soigner l’**accessibilité** (navigation clavier, aria-labels)
- Vérifier la **responsivité** sur mobile, tablette et desktop

## Exemples d’éléments attendus

- Une **liste de conversations** affichant le dernier message reçu
- Un **composant de lecture de message** (titre, auteur, contenu, date)
- Un **formulaire d’envoi de message** avec validation (côté front)
- Un **menu ou onglets de navigation** entre les vues principales
- Une **gestion responsive** (listes et détails affichés côte à côte en desktop, séparés en mobile)

## Nom de dossier attendu

- Une archive ZIP nommée `EC02R_NomPrenom.zip` contenant :
    - Le dossier `src` du projet front
    - Un fichier `README.md` décrivant l’architecture, le choix du framework et la structure des composants
    - Les rapports d’analyse (accessibilité, structuration)

## Rappel pédagogique

Cette épreuve de rattrapage permet de valider les mêmes compétences que l’EC02 initiale :

- Maîtrise des **concepts clés d’un framework moderne** (composants, routing, gestion d’état)
- Mise en œuvre d’une **interface interactive et dynamique**
- Conception d’un front-end **responsive et accessible**
- Organisation d’un projet front-end **scalable** et cohérent

Le scénario change (messagerie interne au lieu de tableau de bord), mais le niveau d’exigence reste identique.
