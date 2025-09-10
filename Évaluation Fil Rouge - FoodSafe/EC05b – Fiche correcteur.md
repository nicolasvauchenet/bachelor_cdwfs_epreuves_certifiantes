# Grille de correction détaillée – EC05

## Informations générales

- **Épreuve :** EC05 – Rapport d’audit Cloud et architecture
- **Durée :** 4h – Individuelle
- **Projet fil rouge :** FoodSafe – Audit technique pour hébergement et architecture logicielle
- **Nature :** Épreuve écrite (rapport + schéma technique)

---

## Critères d’évaluation et attentes

| Critère  | Intitulé officiel                         | Attentes côté correcteur                                                                                                                       | Points de vigilance                                                               |
|----------|-------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------|
| **C9.1** | Analyse des besoins infra                 | Rapport identifie clairement les besoins spécifiques : gestion des données sensibles (santé), conformité RGPD, scalabilité, sécurité, coûts.   | Vérifier que les besoins sont contextualisés à FoodSafe et non génériques.        |
| **C9.2** | Proposition d’architecture                | Schéma technique fourni, choix d’architecture justifiés (monolithe, microservices, serverless). Description claire et adaptée aux contraintes. | Cohérence avec les besoins exprimés. Vérifier lisibilité et pertinence du schéma. |
| **C9.3** | Justification éthique / sécurité / budget | Argumentaire autour des enjeux Green IT, sécurité des données médicales, certification (HDS, RGPD), dépendance fournisseur et coûts estimés.   | Rapport qui ignore RGPD, chiffrement ou aspects santé = critère incomplet.        |

---

## Livrables à corriger

- **Rapport d’audit (PDF)** : analyse des besoins, comparatif des solutions, proposition argumentée
- **Schéma technique** : architecture cible claire et lisible
- **Annexes éventuelles** : calculs de coût, sources documentaires, références réglementaires

---

## Barème indicatif (sur 20 points)

| Axe évalué                            | Points |
|---------------------------------------|--------|
| Analyse des besoins (C9.1)            | /6     |
| Proposition d’architecture (C9.2)     | /8     |
| Justification éthique / budget (C9.3) | /6     |

> **Tolérance :** ±2 points selon la qualité de la structuration, la précision de l’argumentaire et la cohérence
> globale.

---

## Points positifs attendus

- Rapport structuré et argumenté (intro → analyse besoins → comparatif → proposition → conclusion)
- Comparatif clair entre plusieurs solutions (AWS, GCP, Azure, OVH, on-premises)
- Schéma d’architecture lisible et en lien direct avec FoodSafe (API, moteur de recherche, bases, front)
- Analyse de la conformité RGPD, chiffrement des données sensibles, localisation des serveurs
- Justification Green IT (optimisation ressources, réduction empreinte carbone)
- Estimation budgétaire réaliste avec options d’optimisation

---

## Erreurs fréquentes à surveiller

- Rapport trop théorique, sans lien avec FoodSafe
- Comparatif incomplet (un seul fournisseur étudié)
- Schéma absent, illisible ou sans valeur ajoutée
- Aspects RGPD / certification santé ignorés
- Budget absent ou estimations irréalistes
- Architecture proposée non adaptée aux besoins (ex. microservices pour un MVP trop simple)

---

## Rappel pédagogique

Cette épreuve doit confirmer que l’apprenant sait :

- Identifier et analyser les **besoins techniques spécifiques à un projet santé** (sécurité, RGPD, données sensibles)
- Comparer objectivement plusieurs solutions cloud ou hybrides
- Proposer une **architecture adaptée, argumentée et illustrée** par un schéma
- Intégrer des enjeux de **sécurité, budget et éthique** dans sa réflexion

Elle prépare l’apprenant à endosser une posture de **consultant technique ou architecte logiciel**, capable d’éclairer
des décisions stratégiques dans des contextes sensibles.
