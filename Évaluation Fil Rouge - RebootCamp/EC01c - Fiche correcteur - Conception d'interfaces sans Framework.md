# Grille de correction détaillée – EC01

## Informations générales

- **Épreuve :** EC01 – Conception d’interfaces sans Framework
- **Durée :** 4h – Individuelle
- **Projet fil rouge :** RebootCamp – Landing page publique (écogestes, défis, inscription)
- **Nature :** Épreuve écrite et pratique (HTML/CSS/JS natif)

---

## Critères d’évaluation et attentes

| Critère  | Intitulé officiel                    | Attentes côté correcteur                                                                                               | Points de vigilance                                                                   |
|----------|--------------------------------------|------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------|
| **C1.1** | Responsive Web Design sans framework | Page responsive réalisée en HTML5/CSS3 natif. Media queries cohérentes, rendu correct sur desktop, tablette et mobile. | Vérifier cohérence visuelle et absence de dépendance à un framework CSS.              |
| **C1.2** | Accessibilité                        | Utilisation d’attributs ARIA, contrastes respectés, navigation clavier opérationnelle. Rapport Wave/Lighthouse fourni. | Attention aux faux-positifs : vérifier manuellement navigation clavier et contrastes. |
| **C2.1** | Structuration HTML sémantique        | Structure DOM claire avec balises adaptées (`<header>`, `<main>`, `<section>`, `<footer>`). Rapport Lighthouse joint.  | Vérifier lisibilité de la hiérarchie des balises et absence d’abus de `<div>`.        |

---

## Livrables à corriger

- **Code source** : HTML5, CSS3, JavaScript natif
- **Rapport accessibilité** : export Wave/Lighthouse, commentaire des axes d’amélioration
- **Rapport structuration HTML** : analyse Lighthouse et validation de la sémantique

---

## Barème indicatif (sur 20 points)

| Axe évalué                           | Points |
|--------------------------------------|--------|
| Responsive Web Design (C1.1)         | /7     |
| Accessibilité (C1.2)                 | /7     |
| Structuration HTML sémantique (C2.1) | /6     |

> **Tolérance :** ±2 points selon fluidité visuelle, clarté du code et pertinence des rapports fournis.

---

## Points positifs attendus

- Page claire, motivante et esthétique, valorisant la thématique écologique
- Menu de navigation accessible (clavier + ARIA)
- Modale d’inscription fonctionnelle en JS natif, avec gestion du focus et fermeture clavier
- Compteur dynamique affichant l’impact écologique (ex. kg de CO₂ évités)
- Section "Nos Défis" illustrée avec icônes vectorielles optimisées
- Rapport d’accessibilité pertinent, avec recommandations appliquées

---

## Erreurs fréquentes à surveiller

- Page non responsive (coupures ou scroll horizontal sur mobile)
- Accessibilité négligée : contrastes faibles, absence d’ARIA, modale inaccessible au clavier
- Rapport Wave/Lighthouse non fourni ou inexploitable
- Structure HTML mal pensée (divitis, absence de balises structurantes)
- Interaction JavaScript trop complexe ou non fonctionnelle
- Assets lourds ou non optimisés (images non compressées, pas d’`alt`)

---

## Rappel pédagogique

Cette épreuve doit confirmer que l’apprenant maîtrise :

- Les **bases de l’intégration front-end** sans dépendance externe
- Les enjeux d’**accessibilité numérique** (normes WCAG, navigation inclusive)
- La structuration correcte d’une **page HTML sémantique**
- La mise en place d’**interactions simples** et motivantes (modales, compteurs, menus)

Elle constitue le **socle technique** pour les futures épreuves : structuration front-end avec framework (EC02),
back-end et API (EC03–EC04), puis DevOps (EC06).  
