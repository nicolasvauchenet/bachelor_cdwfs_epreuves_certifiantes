# EC05 – Rapport d’audit Cloud et architecture

## Contexte général

Dans le cadre du projet **FoodSafe**, cette épreuve consiste à rédiger un **rapport d’audit technique** sur les
solutions d’hébergement et d’architecture logicielle à envisager pour l’application.

L’apprenant devra proposer une ou plusieurs solutions adaptées aux contraintes spécifiques du projet : gestion de
données sensibles (santé), scalabilité du moteur de recherche produits, performance, sécurité, conformité RGPD et
budget. Ce travail comprend une analyse des besoins, une comparaison des solutions existantes (cloud ou on-premises),
et une proposition argumentée d’architecture technique.

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

- S’appuyer sur une **grille d’analyse claire** : performance, coût, flexibilité, sécurité, conformité RGPD
- Intégrer des enjeux de **résilience et scalabilité** (par ex. montée en charge lors de pics d’utilisation)
- Évaluer les **risques liés aux données médicales** : chiffrement, anonymisation, localisation des serveurs
- Ne pas négliger les aspects **Green IT** et dépendance fournisseur (vendor lock-in)
- Proposer un **schéma visuel** de l’architecture (Lucidchart, draw.io, etc.)
- S’appuyer sur des **cas d’usage concrets** de FoodSafe (recherche produit, API partenaires en pharmacie)

## Exemples d’éléments attendus

- Comparatif entre AWS, GCP, Azure, OVHcloud ou hébergement on-premises (sécurité et certification HDS pour la santé)
- Proposition d’une architecture en **microservices** (API de compatibilité, moteur de recherche, auth) ou **monolithe**
  justifiée
- Recommandation de technologies : PaaS, FaaS, bases managées, load balancer, monitoring, outils RGPD-friendly
- Identification des **risques potentiels** (coûts cachés, complexité, dépendance fournisseur)
- Estimation de **coûts mensuels** avec recommandations d’optimisation

## Nom de dossier attendu

- une archive ZIP nommée `EC05_NomPrenom.zip` contenant :
    - Le fichier `rapport-audit.pdf`
    - Le schéma d’architecture (PDF ou image)
    - Les sources ou outils utilisés en annexe éventuelle

## Rappel pédagogique

Cette épreuve évalue la **capacité d’analyse technique globale d’un projet web moderne** :

- Compréhension des besoins métier et des contraintes de sécurité des données sensibles
- Capacité à comparer des **solutions cloud ou hybrides** en tenant compte du RGPD et de la certification santé
- Maitrise des **principes d’architecture logicielle et infrastructurelle**
- Réflexion stratégique sur le **coût, la sécurité, la performance et la scalabilité**

Elle prépare l’apprenant à des situations concrètes de **choix techniques et budgétaires** dans un contexte
professionnel sensible (applications liées à la santé).
