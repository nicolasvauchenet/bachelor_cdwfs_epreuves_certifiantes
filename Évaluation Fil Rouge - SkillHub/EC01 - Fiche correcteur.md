# Grille de correction détaillée – EC01

## Informations générales

- **Épreuve :** EC01 – Conception d’interfaces sans Framework
- **Durée :** 4h – Individuelle
- **Projet fil rouge :** SkillHub – Landing page publique
- **Technologies imposées :** HTML5, CSS3, JavaScript natif (sans framework)

---

## Critères d’évaluation et attentes

| Critère  | Intitulé officiel                      | Attentes côté correcteur                                                                                                                                           | Points de vigilance                                                                                 |
|----------|----------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------|
| **C1.1** | Responsive Web Design (sans framework) | Vérifier que la page s’adapte aux différentes résolutions (mobile, tablette, desktop). Media queries, grid/flex, viewport bien configuré.                          | Tester sur au moins 3 résolutions. Vérifier absence de scroll horizontal intempestif.               |
| **C1.2** | Accessibilité                          | Présence d’attributs ARIA, labels associés aux champs de formulaire, contraste suffisant. Navigation possible au clavier. Rapport Wave/Lighthouse exporté.         | Contrôler lisibilité du rapport. Tester navigation clavier (tab, shift+tab, entrée, espace).        |
| **C2.1** | Structuration HTML sémantique          | Utilisation cohérente des balises structurantes (`<header>`, `<main>`, `<section>`, `<nav>`, `<footer>`). Vérification du rapport Lighthouse sur la structure DOM. | Vérifier absence d’abus de `<div>`/`<span>`. Balises titres `<h1>…<h6>` hiérarchisées correctement. |

---

## Livrables à corriger

- **Code source :** HTML/CSS/JS dans un dossier `src`
- **README.md :** choix techniques, organisation du code
- **Rapports d’analyse :**
    - Accessibilité (Wave ou Lighthouse)
    - Structuration HTML (Lighthouse)

---

## Barème indicatif (sur 20 points)

| Axe évalué                | Points |
|---------------------------|--------|
| Responsive design (C1.1)  | /8     |
| Accessibilité (C1.2)      | /6     |
| Structuration HTML (C2.1) | /6     |

> **Tolérance :** ±1 point par critère pour valoriser la qualité globale (cohérence, propreté du code, effort
> manifeste).

---

## Points positifs attendus

- Respect strict de la sémantique HTML5
- Media queries efficaces et maintenables
- Navigation fluide au clavier (menu déroulant, modale d’inscription, formulaire)
- Rapport Wave/Lighthouse clair et exploitable
- README clair expliquant les choix techniques

---

## Erreurs fréquentes à surveiller

- Page figée en version desktop uniquement
- Contrastes insuffisants ou absence d’alternatives textuelles aux images
- Usage excessif de `<div>` sans rôle sémantique
- Menu ou modale inaccessibles au clavier
- Rapport d’accessibilité manquant ou trop sommaire
- Validation de formulaire absente ou bloquante

---

## Rappel pédagogique

Cette épreuve constitue le **socle des compétences front-end** :  
le correcteur doit s’assurer que l’apprenant maîtrise déjà les bases (HTML/CSS/JS natif, accessibilité, responsive).  
Les épreuves suivantes (EC02 et suivantes) viendront évaluer la montée en puissance (frameworks, API, bases de données).

---
