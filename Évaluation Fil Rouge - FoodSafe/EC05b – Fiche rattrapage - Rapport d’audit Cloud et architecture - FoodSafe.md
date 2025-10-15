# EC05 – Rattrapage : Rapport d’audit Cloud et architecture (module de recherche et données sensibles)

## Contexte général

Dans le cadre du projet **FoodSafe**, l’épreuve de rattrapage consiste à rédiger un **rapport d’audit technique**
focalisé sur le **moteur de recherche et la gestion des données sensibles** (profils alimentaires et historiques de
recherche).

L’objectif est de proposer une **architecture cloud ou hybride** garantissant la **confidentialité**, la **performance**
et la **scalabilité** de ces fonctionnalités critiques, tout en respectant les contraintes de conformité (RGPD,
hébergement certifié santé, sécurité applicative).

L’apprenant doit comparer plusieurs solutions d’infrastructure, justifier ses choix techniques et présenter un schéma
d’architecture cohérent avec les enjeux du projet.

## Livrables attendus

| Livrable         | Détail                                                                 |
|------------------|------------------------------------------------------------------------|
| Rapport d’audit  | Analyse des besoins, comparatif des solutions, architecture proposée   |
| Schéma technique | Diagramme de l’architecture cible (microservices, cloud hybride, etc.) |
| Justification    | Argumentaire lié au choix cloud / budget / sécurité / performance      |

## Modalités d’évaluation

- **Type d’épreuve** : Mise en situation reconstituée écrite
- **Durée** : 4h
- **Nature** : Épreuve individuelle, sans oral
- **Critères évalués** :
    - C9.1 : Analyse des besoins infrastructure
    - C9.2 : Proposition d’architecture adaptée
    - C9.3 : Justification éthique, sécuritaire et budgétaire

## Recommandations

- Construire une **grille d’analyse** intégrant : sécurité, performance, coût, scalabilité, conformité
- Évaluer plusieurs modèles : **microservices**, **monolithe sécurisé**, ou **architecture serverless**
- Identifier les besoins de **séparation des données sensibles** et les zones de confiance
- Intégrer des solutions de **chiffrement, journalisation et monitoring** adaptées à la santé
- Proposer un **schéma clair** illustrant les flux de données et les interactions (API, BDD, services externes)
- Justifier les arbitrages budgétaires et techniques en lien avec les priorités du projet

## Exemples d’éléments attendus

- Comparatif entre AWS (HDS), GCP, Azure et OVHcloud sur les aspects conformité santé et RGPD
- Proposition d’une architecture mixte : API publique hébergée sur PaaS + BDD sensible isolée sur service managé HDS
- Recommandation d’outils de sécurité : **Key Management Service (KMS)**, **Vault**, **IAM granulaire**,
  **SSL/TLS mutuel**
- Analyse du coût de stockage et de montée en charge du moteur de recherche produit
- Évaluation de la résilience du système : sauvegarde, réplication, reprise après incident

## Nom de dossier attendu

- Une archive ZIP nommée `EC05R_NomPrenom.zip` contenant :
    - Le fichier `rapport-audit.pdf`
    - Le schéma d’architecture (PDF ou image)
    - Les sources ou outils utilisés en annexe éventuelle

## Rappel pédagogique

Cette épreuve de rattrapage valide les mêmes compétences que l’EC05 initiale :

- Capacité à **analyser et concevoir une architecture sécurisée et scalable**
- Comparaison argumentée de **solutions cloud et hybrides** adaptées à la donnée sensible
- Réflexion stratégique sur les **coûts, la conformité et la sécurité**
- Capacité à modéliser les **flux techniques** à travers un schéma clair et justifié

Le scénario change (audit centré sur le **moteur de recherche et la donnée sensible** plutôt que sur l’ensemble de la
plateforme), mais les objectifs et le niveau d’exigence restent identiques.
