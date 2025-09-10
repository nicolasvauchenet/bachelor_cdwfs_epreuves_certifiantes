# Grille de correction détaillée – EC01

## Informations générales

- **Épreuve :** EC01 – Conception d’interfaces sans Framework
- **Durée :** 4h – Individuelle
- **Projet fil rouge :** FoodSafe – Landing page publique
- **Technologies imposées :** HTML5, CSS3, JavaScript natif (sans framework)

---

## Critères d’évaluation et attentes

| Critère  | Intitulé officiel                    | Attentes côté correcteur                                                                                                                               | Points de vigilance                                                                                        |
|----------|--------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------|
| **C1.1** | Responsive Web Design sans framework | La page s’adapte aux différentes résolutions (desktop, tablette, mobile) via media queries, flexbox ou grid.                                           | Tester sur plusieurs tailles d’écran. Vérifier absence de scroll horizontal intempestif.                   |
| **C1.2** | Accessibilité                        | Navigation clavier fluide, contrastes suffisants, labels associés aux champs de formulaire, attributs ARIA pertinents. Rapport Wave/Lighthouse fourni. | Vérifier mise en avant des allergènes (pictogrammes lisibles, alternative textuelle).                      |
| **C2.1** | Structuration HTML sémantique        | Utilisation correcte des balises structurantes (`<header>`, `<section>`, `<main>`, `<nav>`, `<footer>`). Rapport Lighthouse sur la sémantique du DOM.  | Attention à l’abus de `<div>`/`<span>`. Vérifier hiérarchie des titres (`<h1>` unique, niveaux cohérents). |

---

## Livrables à corriger

- **Code source** : HTML5, CSS3, JS natif
- **README.md** : description de l’architecture, choix techniques
- **Rapports d’analyse** :
    - Accessibilité (Wave ou Lighthouse)
    - Structuration HTML (Lighthouse)

---

## Barème indicatif (sur 20 points)

| Axe évalué                | Points |
|---------------------------|--------|
| Responsive design (C1.1)  | /8     |
| Accessibilité (C1.2)      | /6     |
| Structuration HTML (C2.1) | /6     |

> **Tolérance :** ±1 point par critère selon la qualité générale du code, l’effort manifeste et la cohérence des choix.

---

## Points positifs attendus

- Respect strict de la sémantique HTML5
- Mise en avant pédagogique des allergènes (icônes, pictogrammes accessibles)
- Rapport Wave/Lighthouse clair et exploitable
- Navigation clavier fluide (menu, modale, formulaire)
- Media queries bien gérées (desktop, tablette, mobile)
- README clair et technique (architecture, choix justifiés)

---

## Erreurs fréquentes à surveiller

- Landing page figée en version desktop uniquement
- Accessibilité superficielle (contraste ou ARIA oubliés, navigation clavier impossible)
- Abus de `<div>` sans rôle sémantique
- Menu ou modale non accessibles au clavier
- Validation de formulaire absente ou incomplète
- Rapport d’accessibilité manquant ou vide

---

## Rappel pédagogique

Cette épreuve constitue le **socle des compétences front-end** dans le cadre de FoodSafe.  
Elle doit confirmer que l’apprenant sait :

- Intégrer une interface web **responsive et accessible** sans framework
- Produire une **structure sémantique claire** en HTML5
- Mettre en place des **interactions simples en JS natif**
- Documenter son travail et fournir des rapports exploitables

Elle prépare le terrain pour l’EC02, où l’évaluation portera sur la structuration d’un front-end moderne avec framework.
