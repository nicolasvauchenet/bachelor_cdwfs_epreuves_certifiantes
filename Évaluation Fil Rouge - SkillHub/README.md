# Thématique Fil Rouge pour les Épreuves Certifiantes

**Bachelor Développeur Web Full Stack**

## Thématique Générale – Projet Fil Rouge

**Nom du projet : SkillHub**

**Pitch :**  
Dans le cadre de leur formation, les apprenants participeront à la création progressive de *SkillHub*, une plateforme
web collaborative destinée à mettre en relation des apprenants en reconversion et des formateurs indépendants. Le projet
comprend :

- Un espace public de présentation et d’inscription
- Un espace privé pour les utilisateurs (formateurs et apprenants)
- Un système de gestion des ateliers proposés, des inscriptions et des échanges
- Une API sécurisée
- Un hébergement Cloud avec automatisation des déploiements
- Des documents qualité, de la veille technologique et un suivi projet rigoureux

Chaque Épreuve Certifiante (EC) est ancrée dans cette trame, garantissant la cohérence pédagogique et l’ancrage
professionnel du parcours.

---

## Bloc 1 – Front-End : Interfaces Adaptatives et Interactives

### **EC1 – Conception d'interfaces sans Framework**

**Type :** Mise en situation reconstituée sur ordinateur – *Épreuve individuelle – 4h00*

**Syllabus :**  
Les apprenants conçoivent la landing page publique de *SkillHub*. Cette page a pour objectif de présenter la plateforme,
les valeurs du projet, et d’inciter à l’inscription.

- Structure sémantique en HTML5
- Mise en forme en CSS3 (respect des standards UX/UI et responsive design sans framework)
- Interactions simples via JavaScript natif (menu déroulant, modale d’inscription, validation de formulaire)
- Respect des normes d’accessibilité (attributs ARIA, navigation clavier, contrastes)

---

### **EC2 – Conception d'interfaces avec Framework**

**Type :** Mise en situation reconstituée sur ordinateur – *Épreuve individuelle – 4h00*

**Syllabus :**  
Réalisation d’un tableau de bord utilisateur (apprenant ou formateur) permettant :

- Affichage dynamique des ateliers suivis ou créés
- Gestion des inscriptions
- Composants réutilisables (cards, listes, filtres)
- Utilisation d’un framework moderne (React, Vue, Angular)
- Gestion du routing, des états et des formulaires

---

## Bloc 2 – Back-End : Développement d’Applications et d’API

### **EC3 – Développement back-end avec BDD**

**Type :** Mise en situation reconstituée sur ordinateur – *Épreuve individuelle – 4h00*

**Syllabus :**  
Développement du back-end du module de gestion des utilisateurs de *SkillHub*, avec **intégration obligatoire d'une base
relationnelle ET d'une base NoSQL**, afin d’évaluer les critères CR10, CR11 et CR12.  
Pour rendre l'épreuve faisable dans le temps imparti, une **codebase partielle sera fournie** :

- Authentification déjà en place
- Environnement de développement configuré (Docker, docker-compose)
- Modèles, jeux de données initiaux (PostgreSQL et MongoDB)
- Documentation fonctionnelle ou diagramme de contexte

Les apprenants devront mettre en œuvre des opérations ciblées sur les deux bases et justifier leurs choix techniques.

---

### **EC4 – API sécurisée et documentée**

**Type :** Mise en situation reconstituée sur ordinateur – *Épreuve individuelle – 4h00*

**Syllabus :**  
Développement de l’API publique de la plateforme :

- Conception REST ou GraphQL selon le besoin
- Endpoints sécurisés (authentification JWT, middleware d’autorisation)
- Requêtes asynchrones (AJAX/Fetch)
- Rédaction d’une documentation Swagger/OpenAPI
- Tests unitaires sur les endpoints critiques

---

## Bloc 3 – Cloud, DevOps et Architecture

### **EC5 – Rapport d’audit Cloud et architecture**

**Type :** Mise en situation reconstituée écrite – *Épreuve individuelle – 4h00*

**Syllabus :**  
Audit technique de l’infrastructure possible pour *SkillHub*. L’apprenant rédige un rapport dans lequel il :

- Analyse les besoins en scalabilité, sécurité, performance
- Compare les solutions Cloud (AWS, GCP, Azure, OVHcloud) ou on-premises
- Propose une architecture (monolithique, microservices, serverless…)
- Justifie ses choix techniques en lien avec les objectifs métiers

---

### **EC6 – CI/CD et versionning**

**Type :** Mise en situation reconstituée sur ordinateur – *Épreuve individuelle – 4h00*

**Syllabus :**  
Mise en place d’un processus d’intégration et de déploiement continu :

- Configuration d’un dépôt Git structuré (main, dev, feature)
- Mise en place d’un pipeline CI/CD (GitHub Actions, GitLab CI, Jenkins…)
- Automatisation des tests, du linting et du déploiement (sur Docker par exemple)
- Conteneurisation de l’application avec Docker
- Gestion des variables d’environnement, sécurité des déploiements

---

## Bloc 4 – Gestion de Projet, Qualité et Veille

### **EC7 – Étude d’avant-projet**

**Type :** Mise en situation reconstituée écrite – *Épreuve individuelle – 4h00*

**Syllabus :**  
Plutôt que de rédiger une étude initiale fictive en fin de parcours, cette EC portera sur l’**évolution stratégique du
projet** *SkillHub* :

- Transition vers une V2 (changement de public, refonte UX, ajout de contraintes réglementaires, etc.)
- Analyse des retours utilisateurs et des limites de la version initiale
- Repositionnement fonctionnel (objectifs, périmètre, priorisation MoSCoW)
- Élaboration d’un cahier des charges complémentaire
- Proposition de solutions techniques ou organisationnelles

---

### **EC8 – Compte rendu d’activité (Projet fil rouge) + Soutenance**

**Type :** Mise en situation professionnelle reconstituée – *Collectif (1 à 3 jours)*  
**Oral individuel :** 20 minutes

**Syllabus :**  
Projet collectif sur la base du MVP de *SkillHub*. Chaque groupe développe une version partielle ou complète de la
plateforme.

- Répartition des rôles (scrum master, dev front, dev back…)
- Livrables : code source, documentation, rapport d’activité
- Soutenance orale individuelle : explication du rôle, des choix, des contributions

---

### **EC9 – Guide de bonnes pratiques**

**Type :** Mise en situation reconstituée écrite – *Épreuve individuelle – 4h00*

**Syllabus :**  
Rédaction d’un guide interne de qualité logicielle :

- Recommandations pour les revues de code (outils, critères, fréquence)
- Normes de nommage, conventions Git, architecture modulaire
- Stratégie de tests (unitaires, d’intégration)
- Documentation technique minimale à produire dans l’équipe

---

### **EC10 – Rapport de veille technologique multilingue**

**Type :** Épreuve écrite et orale en anglais – *Épreuve individuelle – 2h00 + 20 minutes*

**Syllabus :**  
Rédaction d’un rapport de veille technologique en lien avec une problématique rencontrée lors du projet *SkillHub* :

- Sujet libre : framework, sécurité web, DevOps, accessibilité, etc.
- Recherche multilingue (français / anglais)
- Analyse comparative, synthèse des solutions proposées
- Soutenance orale en anglais

---

## Spécificités supplémentaires intégrées

- **Rattrapage** : chaque EC est indépendante et rejouable à format équivalent
- **Fraude / Prévisibilité** : chaque épreuve comportera un ou plusieurs éléments révélés uniquement le jour J pour
  éviter la triche (ex. : contraintes techniques, données spécifiques, scénario évolutif)
- **Ordre des EC** : respect de l’ordre imposé par le calendrier, avec ajustements pédagogiques (EC07 repositionnée
  comme extension stratégique)

---

## Conclusion

Ce fil rouge permet :

- Une montée en compétence progressive et concrète
- Une forte cohérence pédagogique entre les EC
- Une immersion dans un projet réaliste, complet et professionnalisant
- Une évaluation précise des compétences techniques et transversales
- Une adaptabilité aux contraintes organisationnelles et aux réalités professionnelles

Chaque épreuve reflète une situation métier authentique, en lien direct avec les blocs de compétences du référentiel
RNCP.
