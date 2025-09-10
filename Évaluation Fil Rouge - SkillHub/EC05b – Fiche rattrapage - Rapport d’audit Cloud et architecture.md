# EC05 – Rattrapage : Rapport d’audit Cloud et architecture (module de messagerie)

## Contexte général

Dans le cadre du projet **SkillHub**, l’épreuve de rattrapage consiste à rédiger un **rapport d’audit technique** ciblé
sur un **module spécifique de la plateforme** : la **messagerie interne** entre apprenants et formateurs.

L’objectif est d’évaluer les solutions d’hébergement et d’architecture adaptées à ce module, en tenant compte des
contraintes spécifiques : **temps réel**, **sécurité des données échangées**, **scalabilité** (nombre d’utilisateurs
simultanés), et **optimisation des coûts**.

L’apprenant devra proposer une ou plusieurs solutions techniques adaptées, comparer différentes approches (cloud,
on-premises, hybrides) et fournir une justification argumentée.

## Livrables attendus

| Livrable         | Détail                                                               |
|------------------|----------------------------------------------------------------------|
| Rapport d’audit  | Analyse des besoins, comparatif des solutions, architecture proposée |
| Schéma technique | Diagramme de l’architecture cible (monolithe, microservices, etc.)   |
| Justification    | Argumentaire lié au choix cloud / budget / sécurité / performance    |

## Modalités d’évaluation

- **Type d’épreuve** : Mise en situation reconstituée écrite
- **Durée** : 4h
- **Nature** : Épreuve individuelle, sans oral
- **Critères évalués** :
    - C9.1 : Analyse des besoins infrastructure
    - C9.2 : Proposition d’architecture adaptée
    - C9.3 : Justification éthique, sécuritaire et budgétaire

## Recommandations

- Construire une **grille d’analyse** prenant en compte performance, sécurité, coûts, et conformité RGPD
- Évaluer la pertinence de solutions comme : **WebSockets managés**, **Pub/Sub**, **bases temps réel**
- Étudier les **modes de déploiement** : microservice isolé, fonction serverless, extension d’un monolithe
- Proposer un **schéma clair** de l’architecture cible
- Discuter des **risques et contraintes** (latence, vendor lock-in, dépendances technologiques)

## Exemples d’éléments attendus

- Comparatif entre **Firebase, AWS AppSync, Azure SignalR Service, OVHcloud WebSocket**, ou hébergement interne
- Proposition d’une architecture orientée **microservice temps réel** ou intégrée dans un backend existant
- Recommandations sur la **gestion des sessions et des messages persistants**
- Identification des **risques de charge élevée** (pics de connexions simultanées)
- Estimation de **coûts mensuels** et arbitrages possibles (serverless vs serveurs dédiés)

## Nom de dossier attendu

- Une archive ZIP nommée `EC05R_NomPrenom.zip` contenant :
    - Le fichier `rapport-audit.pdf`
    - Le schéma d’architecture (PDF ou image)
    - Les sources ou outils utilisés en annexe éventuelle

## Rappel pédagogique

Cette épreuve de rattrapage valide les mêmes compétences que l’EC05 initiale :

- Capacité à analyser des **besoins techniques et métiers**
- Comparer des **solutions cloud, hybrides ou on-premises**
- Maîtriser les **principes d’architecture et de scalabilité**
- Argumenter ses choix en tenant compte de la **sécurité, du coût et de la performance**

Le scénario change (focalisation sur le module de messagerie plutôt que l’ensemble de la plateforme), mais le niveau et
les objectifs restent identiques.
