# Thématique Fil Rouge pour les Épreuves Certifiantes

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

Chaque Épreuve Certifiante (EC) est ancrée dans cette trame, garantissant la cohérence pédagogique, la réutilisabilité
technique et l’ancrage professionnel du parcours. Chaque EC reste néanmoins **indépendante et rejouable** à format
équivalent. Des **éléments non triviaux, révélés au dernier moment**, seront introduits pour limiter la fraude et
garantir l’authenticité des productions.

---

## Bloc 1 – Front-End : Interfaces Adaptatives et Interactives

### EC1 – Conception d'interfaces sans Framework

**Type :** Mise en situation reconstituée sur ordinateur – *Épreuve individuelle – 4h00*

**Syllabus :**  
Les apprenants conçoivent la landing page publique de *FoodSafe*. Elle présente la mission du projet, les dangers des
allergènes courants, et invite les utilisateurs à créer un compte.

- Structure HTML5 sémantique et accessible
- Mise en page responsive en CSS3 sans framework
- Comportements interactifs simples en JavaScript (menu, accordéon, modale de contact)
- Respect des normes d’accessibilité (ARIA, contraste, navigation clavier)

---

### EC2 – Conception d'interfaces avec Framework

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

### EC3 – Développement back-end avec BDD (relationnelle + NoSQL)

**Type :** Mise en situation reconstituée sur ordinateur – *Épreuve individuelle – 4h00*

**Syllabus :**  
Implémentation du back-end de gestion des utilisateurs et des profils d’intolérances, en mettant obligatoirement en
œuvre **une base de données relationnelle ET une base NoSQL** (CR10, CR11, CR12).

- Architecture MVC avec POO
- Authentification, rôles (admin, utilisateur)
- PostgreSQL : comptes, rôles, préférences utilisateurs
- MongoDB : fiches produit, tags, historiques de recherches
- Validation et sécurisation des données
- Une codebase partielle pourra être fournie : environnement Docker, auth de base, jeux de données partiels

---

### EC4 – API sécurisée et documentée

**Type :** Mise en situation reconstituée sur ordinateur – *Épreuve individuelle – 4h00*

**Syllabus :**  
Réalisation d’une API publique pour interroger les produits compatibles avec un profil d’utilisateur :

- Endpoints REST (ou GraphQL) : recherche, ajout aux favoris, suppression, etc.
- Authentification via JWT
- Documentation Swagger/OpenAPI
- Tests unitaires sur les routes critiques
- Appel AJAX/Fetch pour vérification sans rechargement de page

---

## Bloc 3 – Cloud, DevOps et Architecture

### EC5 – Rapport d’audit Cloud et architecture

**Type :** Mise en situation reconstituée écrite – *Épreuve individuelle – 4h00*

**Syllabus :**  
Audit technique pour le déploiement de *FoodSafe* :

- Analyse des besoins : performances, sécurité des données santé, RGPD
- Choix de solutions cloud (AWS, GCP, Azure…) ou hébergement dédié
- Proposition d’architecture scalable (monolithe ou microservices)
- Évaluation des coûts, sécurité et maintenance

---

### EC6 – CI/CD et versionning

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

### EC7 – Étude d’avant-projet (portant sur une évolution du projet)

**Type :** Mise en situation reconstituée écrite – *Épreuve individuelle – 4h00*

**Syllabus :**  
Cette épreuve porte sur **l’évolution ou la refonte de la V1 du projet FoodSafe**, déjà partiellement développé au cours
des EC précédentes. Elle simule une situation réaliste dans laquelle un développeur est amené à reprendre un projet
existant pour l’adapter à de nouveaux besoins, à partir de retours utilisateurs, de contraintes techniques ou de choix
stratégiques.

- Analyse critique de la version actuelle (V1)
- Identification des nouveaux besoins fonctionnels
- Définition d’objectifs pour une version V2 du projet
- Élaboration d’un cahier des charges fonctionnel pour l’évolution
- Prise en compte des contraintes de continuité de service, compatibilité, refonte partielle ou migration

---

### EC8 – Compte rendu d’activité (Projet fil rouge) + Soutenance

**Type :** Mise en situation professionnelle reconstituée – *Collectif (1 à 3 jours)*  
**Oral individuel :** 20 minutes

**Syllabus :**  
Développement du MVP de *FoodSafe* :

- Identification des priorités (recherche produit + alertes)
- Livrables collectifs : code, doc, schémas d’archi
- Rétrospective d’équipe (méthodo agile ou hybride)
- Soutenance individuelle : justification des choix techniques et organisationnels

---

### EC9 – Guide de bonnes pratiques

**Type :** Mise en situation reconstituée écrite – *Épreuve individuelle – 4h00*

**Syllabus :**  
Rédaction d’un guide qualité pour maintenir le code et la documentation du projet :

- Standards de nommage, conventions Git, revues de code
- Bonnes pratiques de sécurité (notamment sur les données sensibles)
- Guidelines de tests automatisés
- Documentation technique des modules critiques

---

### EC10 – Rapport de veille technologique multilingue

**Type :** Épreuve écrite et orale en anglais – *Épreuve individuelle – 2h00 + 20 minutes*

**Syllabus :**  
Rapport de veille autour de thématiques liées à *FoodSafe* :

- Frameworks front/back pour apps santé
- Sécurité des APIs manipulant des données sensibles
- Accessibilité numérique pour les apps médicales
- Présentation orale en anglais avec synthèse claire

---

## Conclusion

Ce fil rouge permet :

- Une montée en compétence cohérente et progressive
- Une immersion dans un projet numérique d’utilité publique
- Une transversalité entre techniques back, front, DevOps et gestion projet
- Une évaluation fidèle aux attendus du RNCP et à la réalité du terrain

Chaque épreuve reste autonome, contextualisée, et rejouable. Des contraintes spécifiques, révélées en dernière minute,
permettent d’assurer l’authenticité des productions.
