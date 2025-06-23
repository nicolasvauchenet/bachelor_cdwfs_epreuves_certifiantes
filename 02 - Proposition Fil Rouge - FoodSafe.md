# Proposition de Thématique Fil Rouge pour les Épreuves Certifiantes

**Bachelor Développeur Web Full Stack**

## Thématique Générale – Projet Fil Rouge

**Nom du projet : FoodSafe**

**Pitch :**  
Dans le cadre de leur formation, les apprenants participeront à la création progressive de *FoodSafe*, une application
web destinée à aider les personnes souffrant d’allergies ou d’intolérances alimentaires à vérifier la compatibilité des
produits qu’elles consomment. Le projet comprend :

- Un espace public d’information et de sensibilisation
- Un espace personnel pour renseigner ses intolérances et consulter des produits
- Un moteur de recherche intelligent de produits alimentaires compatibles
- Une API sécurisée pouvant être utilisée par des applis partenaires ou des bornes en pharmacie
- Une infrastructure cloud avec déploiement automatisé
- Des livrables qualité, de la veille techno et une gestion projet collaborative

Chaque Épreuve Certifiante (EC) est ancrée dans cette trame, garantissant la cohérence pédagogique et l’ancrage
professionnel du parcours.

---

## Bloc 1 – Front-End : Interfaces Adaptatives et Interactives

### **EC1 – Conception d'interfaces sans Framework**

**Type :** Mise en situation reconstituée sur ordinateur – *Épreuve individuelle – 4h00*

**Syllabus :**  
Les apprenants conçoivent la landing page publique de *FoodSafe*. Elle présente la mission du projet, les dangers des
allergènes courants, et invite les utilisateurs à créer un compte.

- Structure HTML5 sémantique et accessible
- Mise en page responsive en CSS3 sans framework
- Comportements interactifs simples en JavaScript (menu, accordéon, modale de contact)
- Respect des normes d’accessibilité (ARIA, contraste, navigation clavier)

---

### **EC2 – Conception d'interfaces avec Framework**

**Type :** Mise en situation reconstituée sur ordinateur – *Épreuve individuelle – 4h00*

**Syllabus :**  
Création du tableau de bord utilisateur avec les fonctionnalités suivantes :

- Gestion de son profil alimentaire (intolérances, régimes)
- Historique de recherche de produits
- Résultats de compatibilité sous forme de cards avec codes couleurs
- Développement avec React, Vue ou Angular
- Routing, gestion d’état local, composants réutilisables

---

## Bloc 2 – Back-End : Développement d’Applications et d’API

### **EC3 – Développement back-end avec BDD**

**Type :** Mise en situation reconstituée sur ordinateur – *Épreuve individuelle – 4h00*

**Syllabus :**  
Implémentation du back-end de gestion des utilisateurs et des profils d’intolérances :

- Architecture MVC avec POO
- Base de données relationnelle (PostgreSQL) ou NoSQL (MongoDB) selon profil
- Authentification, rôles (admin, utilisateur)
- Stockage et gestion des profils allergènes (gluten, lactose, etc.)
- Validation des données et sécurisation des entrées

---

### **EC4 – API sécurisée et documentée**

**Type :** Mise en situation reconstituée sur ordinateur – *Épreuve individuelle – 4h00*

**Syllabus :**  
Réalisation d’une API publique pour interroger les produits compatibles avec un profil d’utilisateur :

- Endpoints REST (ou GraphQL) : recherche, ajout aux favoris, suppression, etc.
- Authentification via JWT
- Documentation Swagger/OpenAPI
- Tests unitaires sur les routes critiques (produits, allergènes)
- Appel AJAX/Fetch pour vérification sans rechargement de page

---

## Bloc 3 – Cloud, DevOps et Architecture

### **EC5 – Rapport d’audit Cloud et architecture**

**Type :** Mise en situation reconstituée écrite – *Épreuve individuelle – 4h00*

**Syllabus :**  
Audit technique pour le déploiement de *FoodSafe* :

- Analyse des besoins : performances, sécurité des données santé, RGPD
- Choix de solutions cloud (AWS, GCP, Azure…) ou hébergement dédié
- Proposition d’architecture scalable (monolithe ou microservices)
- Évaluation des coûts, sécurité et maintenance

---

### **EC6 – CI/CD et versionning**

**Type :** Mise en situation reconstituée sur ordinateur – *Épreuve individuelle – 4h00*

**Syllabus :**  
Mise en place d’un processus DevOps :

- Dépôt Git structuré avec stratégie de branches
- Pipelines CI/CD (build, test, lint, deploy)
- Conteneurisation avec Docker
- Déploiement automatique du back + front sur un serveur (ou container cloud)
- Variables d’environnement sécurisées

---

## Bloc 4 – Gestion de Projet, Qualité et Veille

### **EC7 – Étude d’avant-projet**

**Type :** Mise en situation reconstituée écrite – *Épreuve individuelle – 4h00*

**Syllabus :**  
Étude initiale du projet *FoodSafe* :

- Identification des utilisateurs cibles (adultes/allergiques, parents, pros de santé…)
- Définition des besoins fonctionnels et techniques
- Faisabilité technique, contraintes réglementaires (RGPD)
- Cahier des charges fonctionnel structuré

---

### **EC8 – Compte rendu d’activité (Projet fil rouge) + Soutenance**

**Type :** Mise en situation professionnelle reconstituée – *Collectif (1 à 3 jours)*  
**Oral individuel :** 20 minutes

**Syllabus :**  
Développement du MVP de *FoodSafe* :

- Identification des priorités (recherche produit + alertes)
- Livrables collectifs : code, doc, schémas d’archi
- Rétrospective d’équipe (méthodo agile ou hybride)
- Soutenance individuelle : justification des choix techniques et organisationnels

---

### **EC9 – Guide de bonnes pratiques**

**Type :** Mise en situation reconstituée écrite – *Épreuve individuelle – 4h00*

**Syllabus :**  
Rédaction d’un guide qualité pour maintenir le code et la documentation du projet :

- Standards de nommage, conventions Git, revues de code
- Bonnes pratiques de sécurité (notamment sur les données sensibles)
- Guidelines de tests automatisés
- Documentation technique des modules critiques

---

### **EC10 – Rapport de veille technologique multilingue**

**Type :** Épreuve écrite et orale en anglais – *Épreuve individuelle – 2h00 + 20 minutes*

**Syllabus :**  
Rapport de veille autour de thématiques liées à *FoodSafe* :

- Frameworks front/back les plus adaptés à une app santé
- Tendances sur la sécurité des APIs manipulant des données médicales
- Accessibilité numérique pour les applications de santé publique
- Présentation orale en anglais avec synthèse claire des résultats

---

## Conclusion

Ce fil rouge permet :

- Une montée en compétence cohérente, avec un fort ancrage métier (santé, RGPD, accessibilité)
- Une immersion dans un projet numérique d’utilité publique
- Une transversalité technique entre front, back, API, cloud, sécurité et gestion documentaire
- Un développement complet dans un cadre professionnalisant, réaliste et valorisant pour les apprenants

Chaque EC évalue des compétences directement mobilisables dans le monde professionnel et ancrées dans des enjeux
sociétaux actuels.
