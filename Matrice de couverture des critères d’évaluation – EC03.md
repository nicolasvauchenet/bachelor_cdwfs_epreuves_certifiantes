# Matrice de couverture des critères d’évaluation – EC03 (V2)

**Épreuve :** Conception et développement back-end avec BDD relationnelle et NoSQL  
**Durée :** 4h00  
**Type :** Mise en situation reconstituée sur ordinateur – Épreuve individuelle  
**Livrables attendus :**

- Code source (projet complet dans un dépôt Git)
- Base(s) de données (fichiers dump ou accessibles via la VM / conteneur)
- README d’installation et d’explication
- Document(s) justificatif(s) (si demandé explicitement)

---

| Critère                                                                  | Livrable                   | Où le trouver / forme attendue                                                                                           | Commentaire                                                                               |
|--------------------------------------------------------------------------|----------------------------|--------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------|
| **C7.1** <br> Exactitude de l’installation de l’environnement            | VM / Conteneur / Dépôt Git | Fichiers de configuration : `Dockerfile`, `docker-compose.yml`, README d’installation décrivant les étapes               | Une capture d’écran du terminal montrant l’application en fonctionnement peut être jointe |
| **C7.2** <br> Utilisation adaptée du terminal pour gérer l’environnement | Documentation + Captures   | Fichier `setup.md` ou section du README documentant les commandes exécutées, avec captures éventuelles                   | Peut être complété par un script `setup.sh` pour rejouabilité                             |
| **C8.1** <br> Mise en œuvre d’une base relationnelle                     | Code + Base de données     | Scripts SQL ou migrations dans `/migrations`, connexion dans le code (`.env`, `config/`)                                 | Données de test disponibles dans `/seeds` ou dump SQL                                     |
| **C8.2** <br> Mise en œuvre d’une base NoSQL                             | Code + Base de données     | Scripts d’initialisation NoSQL (`mongoimport`), fichiers JSON, connexion dans le code                                    | Données de test disponibles dans `/seeds` ou dump NoSQL                                   |
| **C8.3** <br> Sécurité des données                                       | Code + README              | Sections du code gérant les validations et protections (ex: middleware, sanitation), mentionnées dans le README          | Exemples de contrôles dans le code et justification dans le README                        |
| **C12** <br> Argumentation des choix techniques                          | README / Rapport           | Section « Choix techniques » expliquant les arbitrages : pourquoi SQL + NoSQL, schéma choisi, organisation du code, etc. | Peut être une simple section de quelques paragraphes dans le README                       |

---

### Notes :

- Cette matrice permet d’assurer que tous les critères RNCP visés sont observables dans les livrables.
- Tous les livrables attendus doivent être listés dans l’énoncé et clairement demandés aux candidats.
- Les correcteurs doivent se référer à cette matrice pour cocher les critères un à un.

---

## Proposition de livrables obligatoires :

- **Dépôt Git avec historique de commits**
- **Fichiers de configuration** (`.env`, `docker-compose.yml`, etc.)
- **Bases de données relationnelle et NoSQL** (dans des fichiers dump et/ou initialisées dans la VM)
- **README complet**, incluant :
    - instructions d’installation
    - commandes terminal utilisées
    - choix techniques et arbitrages justifiés
    - sections expliquant la sécurité mise en œuvre
- **(Optionnel)** Captures d’écran terminal ou application en fonctionnement
