# Matrice complète de couverture des critères – EC01 à EC10 (V3)

**Bachelor Développeur Web Full Stack**

**Remarque :** Cette matrice couvre tous les critères RNCP attendus dans les EC, en précisant pour chacun : le
livrable / la modalité, où le trouver et un commentaire.

---

## EC01 – Conception d'interfaces sans Framework

| Critère                 | Livrable / Modalité            | Où le trouver / forme attendue       | Commentaire                                      |
|-------------------------|--------------------------------|--------------------------------------|--------------------------------------------------|
| C1.1 RWD sans framework | Code                           | HTML5/CSS3, media queries            | Vérifier rendu sur plusieurs résolutions         |
| C1.2 Accessibilité      | Code + Rapport Wave/Lighthouse | ARIA, contrastes, navigation clavier | Exporter le rapport d'analyse Wave ou Lighthouse |
| C2.1 Structuration HTML | Code + Rapport Lighthouse      | Arborescence des balises, sémantique | Exporter le rapport d'analyse Lighthouse         |

---

## EC02 – Conception d'interfaces avec Framework

| Critère                        | Livrable / Modalité            | Où le trouver / forme attendue       | Commentaire                                      |
|--------------------------------|--------------------------------|--------------------------------------|--------------------------------------------------|
| C1.3 RWD avec framework        | Code                           | Composants responsive avec React/Vue | Tester sur plusieurs tailles d’écran             |
| C1.4 Accessibilité (framework) | Code + Rapport Wave/Lighthouse | Attributs ARIA dans composants       | Exporter le rapport d'analyse Wave ou Lighthouse |
| C2.2 Structuration front       | Code + Rapport Lighthouse      | Organisation des composants, routing | Exporter le rapport d'analyse Lighthouse         |

---

## EC03 – Développement back-end avec BDD relationnelle + NoSQL

| Critère                            | Livrable / Modalité | Où le trouver / forme attendue                       | Commentaire                                        |
|------------------------------------|---------------------|------------------------------------------------------|----------------------------------------------------|
| C7.1 Environnement installé        | Code / VM           | Dockerfile/Docker Compose, `.env`, captures terminal | Vérification de l'installation                     |
| C7.2 Utilisation terminal          | Code + Doc          | Scripts et commandes dans le README                  | Script `setup.sh` apprécié, README complet         |
| C8.1 POO & MVC                     | Code                | Structure du projet                                  | Vérifier les conventions de noms et l'arborescence |
| C8.2 Clarté / maintenance          | Code + Doc          | README + commentaires dans le code                   | Conventions (ES6, PSR) respectées                  |
| C9 Optimisation & sécurité serveur | Code + Doc          | Headers HTTP, configs serveur                        | Fichiers `.htaccess`, `nginx.conf`…                |
| C10 BDD relationnelle              | Code + dump SQL     | Migrations, schéma SQL                               | Vérifier la cohérence des données                  |
| C11 BDD NoSQL                      | Code + dump         | Collections JSON, scripts mongoDB                    | Vérifier la cohérence des données                  |
| C12 Justification des choix        | README              | Argumentaire : arbitrages techniques                 | SQL + NoSQL, type de schéma choisi, relations      |
| C13 Sauvegarde / restauration      | README + Scripts    | `backup.sh`, `restore.sh`                            | Processus de sauvegarde                            |

---

## EC04 – API sécurisée et documentée

| Critère                  | Livrable / Modalité | Où le trouver / forme attendue  | Commentaire                                         |
|--------------------------|---------------------|---------------------------------|-----------------------------------------------------|
| C8.3 API REST sécurisée  | Code                | JWT, middlewares, tests         | Tokenisation, permissions, ressources uniques       |
| C8.4 Documentation API   | Documentation       | Swagger/OpenAPI, exemples       | Dans `/docs` ou README                              |
| C8.5 Tests unitaires API | Code + rapports     | Tests automatisés des endpoints | Résultats visibles : couverture, réussite des tests |

---

## EC05 – Rapport d’audit Cloud et architecture

| Critère                        | Livrable / Modalité | Où le trouver / forme attendue          | Commentaire                |
|--------------------------------|---------------------|-----------------------------------------|----------------------------|
| C9.1 Analyse besoins infra     | Rapport             | Argumentaire : Comparatif des solutions | Justification choix        |
| C9.2 Propositions architecture | Rapport             | Schéma + explication                    | Inclure budget et sécurité |
| C9.3 Justification éthique     | Rapport             | Argumentaire : green IT, impacts        | Cohérence projet-client    |

---

## EC06 – CI/CD et versionning

| Critère                   | Livrable / Modalité | Où le trouver / forme attendue          | Commentaire                            |
|---------------------------|---------------------|-----------------------------------------|----------------------------------------|
| C7.3 Gestion Git          | Dépôt Git           | Branches (`main`, `integration`, `dev`) | Historique lisible                     |
| C9.4 Pipeline CI/CD       | Code + pipeline     | Gitlab CI, GitHub Actions, etc…         | Testé sur le dépôt, captures de builds |
| C9.5 Déploiement sécurisé | Doc + code          | Scripts de déploiement sécurisé         | Variables d’env protégées              |

---

## EC07 – Étude d’avant-projet (évolution / V2)

| Critère                     | Livrable / Modalité | Où le trouver / forme attendue        | Commentaire                           |
|-----------------------------|---------------------|---------------------------------------|---------------------------------------|
| C14.1 Analyse critique V1   | Rapport             | Argumentaire : Diagnostic technique   | Points faibles et axes d’amélioration |
| C14.2 Cahier des charges V2 | Rapport             | Argumentaire : Fonctions, contraintes | Inclure continuité de service         |

---

## EC08 – Compte rendu d’activité + Soutenance

| Critère                     | Livrable / Modalité | Où le trouver / forme attendue       | Commentaire                                   |
|-----------------------------|---------------------|--------------------------------------|-----------------------------------------------|
| C15.1 Communication orale   | Soutenance          | Présentation claire et structurée    | Évaluer fond et forme                         |
| C15.2 Travail en équipe     | Rapport + oral      | Répartition des tâches, coordination | Méthodologie agile, traditionnelle, hybride ? |
| C16.1 Capacité d’argumenter | Oral                | Réponses aux questions               | Justification cohérente                       |

---

## EC09 – Guide de bonnes pratiques

| Critère                   | Livrable / Modalité | Où le trouver / forme attendue   | Commentaire                  |
|---------------------------|---------------------|----------------------------------|------------------------------|
| C8.6 Normes de code / doc | Guide               | Conventions, naming, revues      | Guide clair et applicable    |
| C9.6 Stratégie de tests   | Guide               | Types de tests, outils           | Couverture minimale précisée |
| C14.3 Qualité logicielle  | Guide               | Critères qualité / améliorations | Mesurable et réaliste        |

---

## EC10 – Rapport de veille technologique multilingue

| Critère                        | Livrable / Modalité | Où le trouver / forme attendue | Commentaire                  |
|--------------------------------|---------------------|--------------------------------|------------------------------|
| C17.1 Recherche documentaire   | Rapport             | Sources fiables, analyse       | Bibliographie incluse        |
| C17.2 Communication en anglais | Oral                | Présentation 5-10min           | Prononciation, vocabulaire   |
| C17.3 Synthèse des tendances   | Rapport + oral      | Analyse comparative            | Avec recommandation critique |

---

## Notes générales

- Tous les critères RNCP sont couverts dans les EC.
- Les modalités (écrit, oral, livrable) sont explicitées pour chaque critère.
- Cette matrice peut être annexée aux sujets pour guider candidats et jurés.
- Elle garantit la traçabilité et la conformité avec les attendus officiels.
