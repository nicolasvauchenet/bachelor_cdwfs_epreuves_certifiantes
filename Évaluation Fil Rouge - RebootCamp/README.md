# Thématique Fil Rouge pour les Épreuves Certifiantes

**Bachelor Développeur Web Full Stack**

## Thématique Générale – Projet Fil Rouge

**Nom du projet : RebootCamp**

**Pitch :**  
Dans le cadre de leur formation, les apprenants participent à la création de *RebootCamp*, une application web ludique
et participative qui aide les citoyens à adopter des écogestes au quotidien. L’utilisateur peut choisir des défis
écologiques selon son profil (transport, alimentation, énergie…), suivre sa progression, gagner des badges, et comparer
ses résultats avec d’autres. Le projet comprend :

- Une landing page motivante avec des statistiques écologiques
- Un espace membre avec suivi de défis et progression
- Un système de classement, gamification et badges
- Une API ouverte pour intégrer les données à d’autres services (mairies, écoles…)
- Une architecture cloud évolutive et une chaîne CI/CD
- Des livrables qualité et de la veille sur l’éco-conception web

Chaque Épreuve Certifiante (EC) est ancrée dans cette trame, garantissant la cohérence pédagogique et l’ancrage
professionnel du parcours.

---

## Bloc 1 – Front-End : Interfaces Adaptatives et Interactives

### EC1 – Conception d'interfaces sans Framework

**Type :** Mise en situation reconstituée sur ordinateur – *Épreuve individuelle – 4h00*

**Syllabus :**  
Création de la page d’accueil de *RebootCamp* :

- Présentation des enjeux écologiques et des défis proposés
- Structure HTML5 respectant les normes d’accessibilité
- Mise en page responsive en CSS3, sans framework
- Comportements interactifs simples en JavaScript : modale d’inscription, compteur de kg CO₂ évités, etc.

---

### EC2 – Conception d'interfaces avec Framework

**Type :** Mise en situation reconstituée sur ordinateur – *Épreuve individuelle – 4h00*

**Syllabus :**  
Développement du tableau de bord utilisateur :

- Affichage des défis en cours, progression, badges obtenus
- Système de filtres et de classement (top 10 des écocitoyens)
- Utilisation d’un framework (React, Vue, Angular)
- Routing, state management, composants réutilisables

---

## Bloc 2 – Back-End : Développement d’Applications et d’API

### EC3 – Développement back-end avec BDD

**Type :** Mise en situation reconstituée sur ordinateur – *Épreuve individuelle – 4h00*

**Syllabus :**  
Développement du back-end pour la gestion des comptes utilisateurs et des défis :

- Architecture MVC avec POO
- Stockage des profils utilisateurs, des défis, des scores et badges
- Base de données relationnelle **et** NoSQL obligatoires (ex : PostgreSQL + MongoDB)
- Gestion des rôles : utilisateur, modérateur, animateur
- Sécurité, validation des données et anonymisation possible
- Une codebase partielle (authentification de base, structure MVC, environnement Docker) peut être fournie pour
  permettre la concentration sur la logique métier

---

### EC4 – API sécurisée et documentée

**Type :** Mise en situation reconstituée sur ordinateur – *Épreuve individuelle – 4h00*

**Syllabus :**  
Conception de l’API publique *RebootCamp* :

- Endpoints REST ou GraphQL : défis disponibles, progression, badges
- Authentification JWT
- Documentation Swagger ou OpenAPI
- Tests automatisés des endpoints
- Intégration simple avec une future appli mobile ou widget d’école

---

## Bloc 3 – Cloud, DevOps et Architecture

### EC5 – Rapport d’audit Cloud et architecture

**Type :** Mise en situation reconstituée écrite – *Épreuve individuelle – 4h00*

**Syllabus :**  
Audit pour déployer *RebootCamp* dans une démarche d’éco-conception :

- Analyse des besoins de disponibilité, performance et sobriété énergétique
- Comparaison entre cloud public, privé, et hébergement green IT (ex : Infomaniak Green Hosting)
- Proposition d’une architecture adaptée (monolithique, microservices…)
- Justification budgétaire, sécuritaire et éthique

---

### EC6 – CI/CD et versionning

**Type :** Mise en situation reconstituée sur ordinateur – *Épreuve individuelle – 4h00*

**Syllabus :**  
Mise en place de la chaîne DevOps du projet :

- Structuration du dépôt Git (branche main/dev/feat)
- Pipelines automatisés pour tests, builds, déploiements (GitLab CI, GitHub Actions…)
- Conteneurisation avec Docker (back et front)
- Déploiement sur un cloud éco-responsable ou simulateur local
- Sécurisation des tokens, logs, et secrets d’environnement

---

## Bloc 4 – Gestion de Projet, Qualité et Veille

### EC7 – Étude d’avant-projet (portant sur une évolution du projet)

**Type :** Mise en situation reconstituée écrite – *Épreuve individuelle – 4h00*

**Syllabus :**  
L’étude porte sur **une évolution ou refonte de la V1 du projet RebootCamp**, à partir d’un retour d’expérience
utilisateur, d’un besoin d’extension à de nouveaux publics (collèges, entreprises), ou d’un pivot stratégique.

- Analyse critique de la V1
- Définition des nouveaux objectifs fonctionnels
- Élaboration d’un cahier des charges fonctionnel pour la version V2
- Contraintes de compatibilité, refonte partielle, intégration continue

---

### EC8 – Compte rendu d’activité (Projet fil rouge) + Soutenance

**Type :** Mise en situation professionnelle reconstituée – *Collectif (1 à 3 jours)*  
**Oral individuel :** 20 minutes

**Syllabus :**  
MVP de *RebootCamp* développé par une équipe projet :

- Suivi des utilisateurs et des défis
- Visualisation de l’impact environnemental individuel et collectif
- Documentation de l’organisation (Trello, Git, wiki…)
- Soutenance individuelle : contribution personnelle, difficultés rencontrées, solutions

---

### EC9 – Guide de bonnes pratiques

**Type :** Mise en situation reconstituée écrite – *Épreuve individuelle – 4h00*

**Syllabus :**  
Rédaction du guide qualité de *RebootCamp* :

- Règles de revue de code, clean code, documentation
- Bonnes pratiques d’éco-conception (lazy loading, compression, dark mode…)
- Normes de sécurité (XSS, CORS, validation serveur)
- Tests unitaires, couverture de code, mise à jour continue

---

### EC10 – Rapport de veille technologique multilingue

**Type :** Épreuve écrite et orale en anglais – *Épreuve individuelle – 2h00 + 20 minutes*

**Syllabus :**  
Veille autour des enjeux numériques durables et du green coding :

- Technologies sobres (Svelte, Astro, Preact…)
- Outils d’analyse d’impact numérique (EcoIndex, Lighthouse…)
- Bibliothèques open source d’UI accessibles
- Présentation en anglais des tendances actuelles, avec synthèse critique

---

## Conclusion

Le projet *RebootCamp* offre :

- Une approche pédagogique motivante autour de l’écologie et de la gamification
- Une montée en compétences front/back/API/cloud réaliste
- Une cohérence forte entre technique, gestion projet et démarche éthique
- Une ouverture sur les enjeux sociétaux et les pratiques numériques durables

Chaque EC est indépendante, rejouable au même format, et contient des éléments non triviaux révélés au dernier moment
pour garantir l’authenticité de la production.
