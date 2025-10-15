# EC07 – Rattrapage : Étude d’avant-projet “Extension mobile et interopérabilité”

## Contexte général

Dans le cadre de l’évolution du projet **FoodSafe**, l’épreuve de rattrapage consiste à réaliser une
**étude d’avant-projet** centrée sur l’**extension mobile et l’interopérabilité** du système avec des services externes.

L’objectif est de concevoir la **V2 mobile et connectée** de FoodSafe : une application complémentaire permettant aux
utilisateurs de scanner les produits en situation réelle (supermarché, restaurant, pharmacie) et de synchroniser leurs
données avec la plateforme web.

L’apprenant doit analyser la V1, identifier les limites actuelles et proposer une
**feuille de route technique et fonctionnelle** réaliste intégrant les enjeux de **sécurité, conformité RGPD**, et
**expérience utilisateur multiplateforme**.

## Livrables attendus

| Livrable               | Détail                                                                   |
|------------------------|--------------------------------------------------------------------------|
| Rapport d’avant-projet | Analyse critique de la V1, diagnostic, axes d’évolution, recommandations |
| Cahier des charges V2  | Objectifs, périmètre, fonctionnalités, contraintes techniques et UX      |

## Modalités d’évaluation

- **Type d’épreuve** : Mise en situation reconstituée écrite
- **Durée** : 4h
- **Nature** : Épreuve individuelle, sans oral
- **Critères évalués** :
    - C14.1 : Analyse critique de la version existante
    - C14.2 : Élaboration d’un cahier des charges complet

## Recommandations

- Identifier les besoins des **utilisateurs mobiles** (vitesse, clarté, accessibilité offline)
- Proposer des fonctionnalités spécifiques à la mobilité (scan, notifications, géolocalisation, historique local)
- Étudier l’**interopérabilité avec des API tierces** (ex. bases de données produits, pharmacies, services santé
  publique)
- Intégrer les contraintes de **sécurité et de conformité** : RGPD, stockage local, gestion des tokens, chiffrement
- Définir une **feuille de route technique** incluant le choix du framework mobile (ex : React Native, Flutter, PWA)
- Recommander des outils de suivi, tests et publication sur stores

## Exemples d’éléments attendus

- Diagnostic des **limites de la V1 web** pour un usage mobile (latence, responsive, accessibilité, UX)
- Proposition d’une **architecture hybride** Web + Mobile avec synchronisation sécurisée
- Cahier des charges listant les nouvelles fonctionnalités (scan, historique local, notifications d’alerte)
- Intégration possible avec une API d’open data produits (ex : OpenFoodFacts)
- Recommandations d’outillage : CI/CD mobile, monitoring, gestion des clés et certificats

## Nom de dossier attendu

- Une archive ZIP nommée `EC07R_NomPrenom.zip` contenant :
    - Le fichier `rapport-etude-mobile.pdf`
    - Le fichier `cahier-des-charges-v2.pdf` (ou `.md`)
    - Les annexes éventuelles (benchmarks, schémas d’architecture, personas, wireframes…)

## Rappel pédagogique

Cette épreuve de rattrapage valide les mêmes compétences que l’EC07 initiale :

- Capacité à **analyser une version existante** et identifier ses limites
- Rédaction d’un **cahier des charges complet et argumenté**
- Intégration des **enjeux de sécurité, conformité et expérience utilisateur**
- Projection réaliste vers une **évolution stratégique** et techniquement cohérente

Le scénario change (évolution vers une **application mobile connectée** et interopérable au lieu d’une refonte globale),
mais le niveau d’exigence et les objectifs pédagogiques restent identiques.
