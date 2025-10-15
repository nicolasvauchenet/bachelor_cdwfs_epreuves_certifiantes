# EC05 – Rattrapage : Mini-audit d’architecture éco-responsable

## Contexte général

Dans le cadre du projet **RebootCamp**, l’épreuve de rattrapage consiste à rédiger un **mini-rapport d’audit technique**
centré sur l’**hébergement durable** et la **scalabilité raisonnée** du projet.

L’objectif est de démontrer la capacité à analyser une architecture existante, identifier ses limites (performance,
coût, sécurité, impact environnemental) et proposer une **évolution éthique et soutenable**.

L’apprenant devra présenter une **proposition d’architecture simplifiée** adaptée au contexte RebootCamp : application
web communautaire à fort trafic potentiel mais à vocation écologique.

## Livrables attendus

| Livrable            | Détail                                                     |
|---------------------|------------------------------------------------------------|
| Rapport synthétique | Analyse des besoins, risques et propositions (2 à 3 pages) |
| Schéma technique    | Diagramme simple de l’architecture proposée                |
| Argumentaire        | Justification des choix cloud, RGPD et éco-responsables    |

## Modalités d’évaluation

- **Type d’épreuve** : Mise en situation reconstituée écrite
- **Durée** : 4h
- **Nature** : Épreuve individuelle, sans oral
- **Critères évalués** :
    - C9.1 : Analyse d’une infrastructure existante
    - C9.2 : Proposition d’architecture raisonnée et adaptée
    - C9.3 : Justification des choix éthiques, écologiques et budgétaires

## Recommandations

- Se concentrer sur **une problématique précise** : performance, sobriété énergétique, sécurité ou résilience
- Comparer **2 solutions d’hébergement** (par ex. OVHcloud vs Infomaniak, ou GCP vs Scaleway)
- Inclure des notions de **Green IT** : datacenters certifiés ISO 50001, mutualisation, minimisation du stockage
- Représenter visuellement l’architecture : front, API, BDD, CI/CD, monitoring
- Intégrer des **bonnes pratiques de durabilité logicielle** : compression, cache, ressources statiques, containers
  légers

## Exemples d’éléments attendus

- Audit : “L’API de RebootCamp hébergée sur une instance mutualisée OVH présente des limites de montée en charge”
- Proposition : migration vers un hébergement cloud européen “green” (ex : Infomaniak, Scaleway, Clever Cloud)
- Schéma : microservices légers + base managée + CDN + pipeline CI/CD sobre
- Éléments chiffrés : coût estimé mensuel, empreinte carbone approximative
- Recommandations : pratiques pour réduire l’empreinte (builds légers, monitoring sobre, logs optimisés)

## Nom de dossier attendu

- Une archive ZIP nommée `EC05R_NomPrenom.zip` contenant :
    - Le fichier `mini-audit.pdf` (2 à 3 pages)
    - Le schéma d’architecture (image ou PDF)
    - Les annexes éventuelles (tableaux comparatifs, estimations de coût)

## Rappel pédagogique

Cette épreuve de rattrapage évalue la
**capacité à raisonner sur une architecture technique en intégrant la durabilité** :

- Analyse et compréhension des contraintes techniques et écologiques
- Élaboration d’une **proposition d’architecture pragmatique et sobre**
- Argumentation claire et documentée sur les **enjeux de scalabilité, sécurité, coût et impact environnemental**

Elle prolonge la philosophie de RebootCamp en invitant les apprenants à concevoir une infrastructure
**performante mais responsable**, conforme à la démarche de sobriété numérique.
