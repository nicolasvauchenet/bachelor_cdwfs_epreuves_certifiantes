# Matrice complète de couverture des critères – EC01 à EC10 (V2)

**Bachelor Développeur Web Full Stack**

**Remarque :** Cette matrice couvre tous les critères RNCP attendus dans les EC, en précisant pour chacun : le
livrable / la modalité, où le trouver et un commentaire.

---

## EC01 – Conception d'interfaces sans Framework

| Critère                 | Livrable / Modalité | Où le trouver / forme attendue       | Commentaire                              |
|-------------------------|---------------------|--------------------------------------|------------------------------------------|
| C1.1 RWD sans framework | Code                | HTML5/CSS3, media queries            | Vérifier rendu sur plusieurs résolutions |
| C1.2 Accessibilité      | Code + Doc          | ARIA, contrastes, navigation clavier | Captures et commentaires possibles       |
| C2.1 Structuration HTML | Code                | Arborescence des balises, sémantique | Vérifié sur le code source               |

---

## EC02 – Conception d'interfaces avec Framework

| Critère                        | Livrable / Modalité | Où le trouver / forme attendue       | Commentaire                          |
|--------------------------------|---------------------|--------------------------------------|--------------------------------------|
| C1.3 RWD avec framework        | Code                | Composants responsive avec React/Vue | Tester sur plusieurs tailles d’écran |
| C1.4 Accessibilité (framework) | Code + Doc          | Attributs ARIA dans composants       | Rendu accessible vérifié             |
| C2.2 Structuration front       | Code                | Organisation des composants, routing | README explicatif recommandé         |

---

## EC03 – Développement back-end avec BDD relationnelle + NoSQL

| Critère                            | Livrable / Modalité | Où le trouver / forme attendue        | Commentaire                      |
|------------------------------------|---------------------|---------------------------------------|----------------------------------|
| C7.1 Environnement installé        | Code / VM           | Dockerfile, `.env`, captures terminal | Vérification installation        |
| C7.2 Utilisation terminal          | Code + Doc          | Scripts et commandes dans README      | Script `setup.sh` apprécié       |
| C8.1 POO & MVC                     | Code                | Structure projet                      | Vérifier noms, arborescence      |
| C8.2 Clarté / maintenance          | Code + Doc          | README + commentaires code            | Conventions respectées           |
| C9 Optimisation & sécurité serveur | Code + Doc          | Headers HTTP, configs serveur         | `.htaccess`, `nginx.conf`…       |
| C10 BDD relationnelle              | Code + dump SQL     | Migrations, schéma SQL                | Vérifier cohérence données       |
| C11 BDD NoSQL                      | Code + dump         | Collections JSON, scripts mongo       | Vérifier cohérence données       |
| C12 Justification des choix        | README              | Section arbitrages techniques         | SQL + NoSQL, schéma choisi       |
| C13 Sauvegarde / restauration      | README + Scripts    | `backup.sh`, `restore.sh`             | Explication processus sauvegarde |

---

## EC04 – API sécurisée et documentée

| Critère                  | Livrable / Modalité | Où le trouver / forme attendue  | Commentaire               |
|--------------------------|---------------------|---------------------------------|---------------------------|
| C8.3 API REST sécurisée  | Code                | JWT, middlewares, tests         | Tokenisation, permissions |
| C8.4 Documentation API   | Doc                 | Swagger/OpenAPI, exemples       | Dans `/docs` ou README    |
| C8.5 Tests unitaires API | Code + rapports     | Tests automatisés des endpoints | Résultats visibles        |

---

## EC05 – Rapport d’audit Cloud et architecture

| Critère                        | Livrable / Modalité | Où le trouver / forme attendue | Commentaire                |
|--------------------------------|---------------------|--------------------------------|----------------------------|
| C9.1 Analyse besoins infra     | Rapport             | Comparatif solutions           | Justification choix        |
| C9.2 Propositions architecture | Rapport             | Schéma + explication           | Inclure budget et sécurité |
| C9.3 Justification éthique     | Rapport             | Note sur green IT, impacts     | Cohérence projet-client    |

---

## EC06 – CI/CD et versionning

| Critère                   | Livrable / Modalité | Où le trouver / forme attendue   | Commentaire               |
|---------------------------|---------------------|----------------------------------|---------------------------|
| C7.3 Gestion Git          | Dépôt Git           | Branches (`main`, `dev`, `feat`) | Historique lisible        |
| C9.4 Pipeline CI/CD       | Code + pipeline     | `.gitlab-ci.yml`, GitHub Actions | Testé sur dépôt           |
| C9.5 Déploiement sécurisé | Doc + code          | Scripts déploiement sécurisé     | Variables d’env protégées |

---

## EC07 – Étude d’avant-projet (évolution / V2)

| Critère                     | Livrable / Modalité | Où le trouver / forme attendue | Commentaire                           |
|-----------------------------|---------------------|--------------------------------|---------------------------------------|
| C14.1 Analyse critique V1   | Rapport             | Diagnostic technique           | Points faibles et axes d’amélioration |
| C14.2 Cahier des charges V2 | Rapport             | Fonctions, contraintes         | Inclure continuité de service         |

---

## EC08 – Compte rendu d’activité + Soutenance

| Critère                     | Livrable / Modalité | Où le trouver / forme attendue       | Commentaire             |
|-----------------------------|---------------------|--------------------------------------|-------------------------|
| C15.1 Communication orale   | Soutenance          | Présentation claire et structurée    | Évaluer fond et forme   |
| C15.2 Travail en équipe     | Rapport + oral      | Répartition des tâches, coordination | Méthodologie agile ?    |
| C16.1 Capacité d’argumenter | Oral                | Réponses aux questions               | Justification cohérente |

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

## 📝 Notes générales

- Tous les critères RNCP sont couverts dans les EC.
- Les modalités (écrit, oral, livrable) sont explicitées pour chaque critère.
- Cette matrice peut être annexée aux sujets pour guider candidats et jurés.
- Elle garantit la traçabilité et la conformité avec les attendus officiels.
