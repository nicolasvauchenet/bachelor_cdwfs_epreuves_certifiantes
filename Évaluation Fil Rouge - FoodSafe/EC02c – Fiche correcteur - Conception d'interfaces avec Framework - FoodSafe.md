# Grille de correction détaillée – EC02

## Informations générales

- **Épreuve :** EC02 – Conception d’interfaces avec Framework
- **Durée :** 4h – Individuelle
- **Projet fil rouge :** FoodSafe – Tableau de bord utilisateur (patients / utilisateurs)
- **Technologies imposées :** React, Vue ou Angular (au choix selon consignes)

---

## Critères d’évaluation et attentes

| Critère  | Intitulé officiel                    | Attentes côté correcteur                                                                                                                                                                                    | Points de vigilance                                                                                                                           |
|----------|--------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------|
| **C1.3** | Responsive Web Design avec framework | Vérifier que les vues (profil, produits, historique) sont adaptatives. Utilisation correcte des utilitaires CSS du framework ou de media queries.                                                           | Tester l’affichage sur desktop, tablette et mobile. Pas de mise en page figée.                                                                |
| **C1.4** | Accessibilité (framework)            | Navigation clavier fluide, usage d’ARIA dans les composants interactifs, contrastes respectés. Rapport Wave/Lighthouse fourni.                                                                              | Vérifier focus states sur formulaires et cartes produit. Composants accessibles pour la sélection des intolérances.                           |
| **C2.2** | Structuration front-end              | Organisation du projet en composants réutilisables. Routing clair (`Dashboard`, `Mon Profil`, `Historique`, `Produits Compatibles`). Gestion d’état maîtrisée (local ou global). Rapport Lighthouse fourni. | Vérifier lisibilité de l’arborescence (`/components`, `/views`, `/router`, `/store`). Éviter le code « spaghetti » ou un seul gros composant. |

---

## Livrables à corriger

- **Code source** : projet front complet (`src/`)
- **README.md** : choix du framework, justification de l’architecture, organisation des composants
- **Rapports d’analyse** :
    - Accessibilité (Wave ou Lighthouse)
    - Structuration front (Lighthouse)

---

## Barème indicatif (sur 20 points)

| Axe évalué                 | Points |
|----------------------------|--------|
| Responsive design (C1.3)   | /6     |
| Accessibilité (C1.4)       | /6     |
| Structuration front (C2.2) | /8     |

> **Tolérance :** ±1 point par critère selon la qualité globale, la propreté du code et l’effort manifeste.

---

## Points positifs attendus

- Composants bien découpés (ex. formulaire allergies, carte produit, liste de résultats)
- Routing simple et lisible (navigation claire entre sections)
- Gestion d’état robuste (stockage préférences utilisateurs, résultats de recherche)
- Cartes produits avec codes couleurs cohérents (vert/orange/rouge)
- Rapport d’accessibilité exploitable (Wave/Lighthouse)
- README explicatif et utile

---

## Erreurs fréquentes à surveiller

- Application mono-composant (pas de découpage logique)
- Responsive défaillant : tableau ou cartes illisibles en mobile
- Accessibilité négligée (formulaire non accessible, contraste insuffisant, focus oublié)
- Routing confus ou inexistant (navigation simulée mais pas réelle)
- README trop minimal ou absent
- Rapports Wave/Lighthouse manquants ou inexploitables

---

## Rappel pédagogique

Cette épreuve doit valider que l’apprenant est capable de :

- Construire une **SPA (Single Page Application)** simple, lisible et maintenable
- Réutiliser des composants pour améliorer la robustesse et la scalabilité du front
- Produire une interface **responsive, accessible et adaptée à un usage médical**
- Documenter correctement son projet pour faciliter l’évaluation et la reprise

Elle prépare directement l’EC03, où l’accent sera mis sur le **back-end et les bases de données**.
