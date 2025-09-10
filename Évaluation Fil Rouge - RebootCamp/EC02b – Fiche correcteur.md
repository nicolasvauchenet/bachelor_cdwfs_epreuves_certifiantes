# Grille de correction détaillée – EC02

## Informations générales

- **Épreuve :** EC02 – Conception d’interfaces avec Framework
- **Durée :** 4h – Individuelle
- **Projet fil rouge :** RebootCamp – Tableau de bord utilisateur (défis, progression, badges, classement)
- **Nature :** Épreuve écrite et pratique (React, Vue ou Angular)

---

## Critères d’évaluation et attentes

| Critère  | Intitulé officiel                    | Attentes côté correcteur                                                                                         | Points de vigilance                                                                                        |
|----------|--------------------------------------|------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------|
| **C1.3** | Responsive Web Design avec framework | Interface responsive réalisée via composants du framework. Rendu correct sur desktop, tablette et mobile.        | Vérifier que l’UI reste fluide même avec des composants dynamiques (classement, filtres).                  |
| **C1.4** | Accessibilité avec framework         | Composants respectant les standards WCAG : ARIA, navigation clavier, contrastes. Rapport Wave/Lighthouse fourni. | Vérifier cohérence entre recommandations Lighthouse et implémentation effective.                           |
| **C2.2** | Structuration du front-end           | Organisation claire du projet : composants réutilisables, routing, gestion d’état (global ou local).             | Attention aux projets plats (trop peu de découpage) ou aux architectures trop lourdes pour une petite SPA. |

---

## Livrables à corriger

- **Code source** : projet front complet (React, Vue ou Angular)
- **Rapport d’accessibilité** : export Wave/Lighthouse, avec analyse des points d’amélioration
- **Rapport structuration front** : analyse Lighthouse de l’organisation, du routing et des composants

---

## Barème indicatif (sur 20 points)

| Axe évalué                          | Points |
|-------------------------------------|--------|
| Responsive Web Design (C1.3)        | /7     |
| Accessibilité avec framework (C1.4) | /7     |
| Structuration du front-end (C2.2)   | /6     |

> **Tolérance :** ±2 points selon pertinence de l’architecture, qualité du code et soin apporté à l’expérience
> utilisateur.

---

## Points positifs attendus

- Tableau de bord clair et engageant, adapté au thème écologique
- Liste de défis avec filtrage dynamique (par thématique : transport, énergie, alimentation)
- Cartes utilisateur lisibles (progression + badges obtenus)
- Classement top 10 des écocitoyens, mise à jour dynamique
- Routing clair entre les sections (`Dashboard`, `Mes Défis`, `Classement`, `Statistiques`)
- Gestion d’état cohérente (store global ou hooks/local state bien utilisés)
- Rapport accessibilité pertinent, avec corrections intégrées

---

## Erreurs fréquentes à surveiller

- Interface non responsive ou dépendance excessive à des classes utilitaires sans cohérence globale
- Accessibilité négligée (pas d’ARIA, navigation clavier impossible, contrastes faibles)
- Rapport Wave/Lighthouse non exploité ou ignoré
- Composants mal factorisés (duplication de code, absence de modularité)
- Routing mal configuré ou inexistant (SPA réduite à une seule vue)
- Mauvaise gestion de l’état (variables globales mal définies, absence de logique claire pour progression/badges)
- UX pauvre : absence de feedback visuel lors de filtres, erreurs non gérées

---

## Rappel pédagogique

Cette épreuve doit confirmer que l’apprenant maîtrise :

- Les **bases d’un framework moderne** (composants, routing, gestion d’état)
- La conception d’interfaces **dynamiques et réactives** adaptées à une SPA
- L’**intégration de l’accessibilité** dans un contexte framework (navigation clavier, ARIA, contrastes)
- L’**organisation d’un projet scalable**, favorisant la réutilisation des composants et la maintenabilité du code

Elle prolonge les acquis de l’EC01 (HTML/CSS/JS natif) et prépare aux logiques métiers plus complexes du back-end (EC03)
et de l’API (EC04).
