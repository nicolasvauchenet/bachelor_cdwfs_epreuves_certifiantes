# Grille de correction détaillée – EC05

## Informations générales

- **Épreuve :** EC05 – Rapport d’audit Cloud et architecture
- **Durée :** 4h – Individuelle
- **Projet fil rouge :** RebootCamp – Audit technique d’hébergement et d’architecture
- **Nature :** Épreuve écrite (rapport + schéma)

---

## Critères d’évaluation et attentes

| Critère  | Intitulé officiel                                | Attentes côté correcteur                                                                                          | Points de vigilance                                                                         |
|----------|--------------------------------------------------|-------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------|
| **C9.1** | Analyse des besoins infrastructure               | Identification claire des besoins : scalabilité, disponibilité, sécurité, RGPD, sobriété numérique.               | Vérifier que l’analyse est contextualisée (défis, classements en temps réel, API publique). |
| **C9.2** | Proposition d’architecture adaptée               | Schéma précis (monolithe, microservices, serverless…) accompagné d’explications techniques et organisationnelles. | Cohérence entre la proposition et les besoins exprimés, réalisme technique.                 |
| **C9.3** | Justification éthique, sécuritaire et budgétaire | Comparatif clair (cloud public/privé, green IT, on-premises), coûts estimés, prise en compte RGPD et Green IT.    | Risque d’oubli de l’aspect sobriété énergétique, ou de justification trop superficielle.    |

---

## Livrables à corriger

- **Rapport d’audit** : analyse détaillée des besoins et comparaison des solutions
- **Schéma technique** : diagramme d’architecture proposé, lisible et cohérent
- **Justification** : argumentaire intégrant coûts, sécurité, éthique et durabilité

---

## Barème indicatif (sur 20 points)

| Axe évalué                          | Points |
|-------------------------------------|--------|
| Analyse des besoins (C9.1)          | /7     |
| Proposition d’architecture (C9.2)   | /7     |
| Justification éthique/budget (C9.3) | /6     |

> **Tolérance :** ±2 points selon le degré de maturité technique et la clarté du rapport.

---

## Points positifs attendus

- Comparatif structuré : AWS, GCP, Azure, OVH, Infomaniak, on-premises
- Analyse contextualisée des besoins :
    - Scalabilité horizontale pour le classement en temps réel
    - Performance pour l’API publique
    - Sécurité et RGPD (données personnelles)
- Schéma d’architecture clair (services, bases, API Gateway, load balancer)
- Intégration des enjeux Green IT : hébergeurs éco-responsables, optimisation énergétique
- Estimation des coûts mensuels avec pistes d’optimisation (scaling, mutualisation)
- Argumentaire solide : choix technologiques justifiés par les besoins réels de RebootCamp

---

## Erreurs fréquentes à surveiller

- Rapport trop générique, sans lien avec les cas d’usage RebootCamp
- Schéma d’architecture absent, incomplet ou illisible
- Comparaison trop superficielle (ex : simple liste d’hébergeurs sans analyse)
- Pas de prise en compte de la conformité RGPD ou de la sécurité des données
- Oubli de l’aspect sobriété numérique (Green IT, consommation énergétique)
- Estimation des coûts absente ou non réaliste

---

## Rappel pédagogique

Cette épreuve valide la capacité de l’apprenant à :

- Comprendre et analyser des **besoins métiers et techniques complexes**
- Comparer objectivement des **solutions d’infrastructure** (cloud, hybride, green IT)
- Proposer une **architecture logicielle cohérente** avec les objectifs et contraintes
- Intégrer les enjeux de **sécurité, RGPD, coûts et éco-conception**

Elle place l’apprenant dans une situation réaliste de **choix techniques stratégiques**, où la durabilité et la
performance doivent être conciliées.  
