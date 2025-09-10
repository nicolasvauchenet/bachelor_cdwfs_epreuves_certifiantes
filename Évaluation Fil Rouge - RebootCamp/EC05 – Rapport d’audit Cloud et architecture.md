# EC05 – Rapport d’audit Cloud et architecture

## Contexte général

Dans le cadre du projet **RebootCamp**, cette épreuve consiste à rédiger un **rapport d’audit technique** sur les
solutions d’hébergement et d’architecture logicielle à envisager pour l’application.

L’apprenant devra proposer une ou plusieurs solutions adaptées aux contraintes spécifiques du projet : scalabilité du
système de défis, performance du classement, sécurité des données utilisateurs, conformité RGPD, mais aussi sobriété
numérique et éco-conception.

Ce travail comprend une analyse des besoins, une comparaison des solutions existantes (cloud, on-premises, hébergeurs
green IT), et une proposition argumentée d’architecture technique.

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

- S’appuyer sur une **grille d’analyse claire** : performance, coût, flexibilité, sécurité, impact environnemental
- Penser à la **résilience** de l’infrastructure (scalabilité horizontale, redondance)
- Intégrer les **enjeux RGPD et Green IT** (sobriété énergétique, datacenters éco-responsables)
- Proposer un **schéma visuel** de l’architecture (Lucidchart, draw.io, etc.)
- Illustrer avec des **cas d’usage concrets** de RebootCamp (classement en temps réel, API publique, gamification)

## Exemples d’éléments attendus

- Comparatif entre AWS, GCP, Azure, OVHcloud, Infomaniak Green Hosting ou hébergement on-premises
- Proposition d’une architecture en microservices (API défis, API classement, API badges) ou monolithe justifiée
- Recommandation de technologies : PaaS, FaaS, load balancer, bases managées, monitoring sobre
- Identification des **risques potentiels** (coûts cachés, vendor lock-in, surdimensionnement)
- Estimation des **coûts mensuels**, avec pistes d’optimisation (scaling automatique, mutualisation)

## Nom de dossier attendu

- une archive ZIP nommée `EC05_NomPrenom.zip` contenant :
    - Le fichier `rapport-audit.pdf`
    - Le schéma d’architecture (PDF ou image)
    - Les sources ou outils utilisés en annexe éventuelle

## Rappel pédagogique

Cette épreuve évalue la **capacité d’analyse technique globale d’un projet web moderne** :

- Compréhension des besoins métier et des contraintes techniques propres à RebootCamp
- Capacité à comparer des **solutions cloud ou hybrides**, en intégrant les enjeux écologiques
- Maitrise des **principes d’architecture logicielle et infrastructurelle**
- Réflexion stratégique sur le **coût, la sécurité, la performance et la sobriété énergétique**

Elle prépare l’apprenant à des situations concrètes de **choix techniques, éthiques et budgétaires** dans un contexte
professionnel sensible aux enjeux de durabilité.
