# EC02 – Rattrapage : Conception d’un module “Scanner & Historique” avec Framework

## Contexte général

Dans le cadre du projet **FoodSafe**, l’épreuve de rattrapage consiste à développer une
**interface utilisateur interactive** centrée sur le **module de scan et d’historique de produits alimentaires**.

Ce module fait partie du tableau de bord utilisateur et permet de :

- Simuler la **recherche ou le scan d’un produit** (via saisie ou code fictif)
- Afficher le **niveau de risque allergène** selon le profil de l’utilisateur
- Consulter l’**historique des scans récents**
- Gérer la navigation entre les vues : `Scanner`, `Résultats`, `Historique`

L’épreuve met l’accent sur la réutilisabilité des composants, l’accessibilité, la gestion de l’état et la cohérence UX.

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
- Structurer le projet avec des **composants réutilisables** (`ScanForm`, `ProductCard`, `HistoryList`…)
- Gérer l’**état global ou local** pour stocker les scans et les résultats
- Mettre en place un **routing clair** entre les vues principales (`/scan`, `/results`, `/history`)
- Assurer une **accessibilité complète** : focus, navigation clavier, contrastes
- Soigner la **cohérence visuelle** : retours d’erreurs, codes couleurs, messages utilisateur

## Exemples d’éléments attendus

- Un **formulaire de scan simulé** (saisie manuelle ou code produit fictif)
- Une **liste d’historique** des produits scannés avec tri ou pagination
- Des **cartes produit** colorées selon le niveau de compatibilité (vert/orange/rouge)
- Un **message d’erreur clair** si le produit n’est pas trouvé
- Un **composant de navigation** (tabs ou sidebar) entre les sections

## Nom de dossier attendu

- Une archive ZIP nommée `EC02R_NomPrenom.zip` contenant :
    - Le dossier `src` du projet front
    - Un fichier `README.md` décrivant l’architecture, le choix du framework et la structure des composants
    - Les rapports d’analyse (accessibilité, structuration)

## Rappel pédagogique

Cette épreuve de rattrapage vise à valider les mêmes compétences que l’EC02 initiale :

- Maîtrise d’un **framework front moderne** (composants, état, routing)
- Capacité à produire une interface **interactive, responsive et accessible**
- Organisation du code et des vues de manière **scalable et réutilisable**

Le scénario change (module “Scanner & Historique” au lieu du tableau de bord complet), mais le niveau d’exigence et les
objectifs pédagogiques restent identiques.
