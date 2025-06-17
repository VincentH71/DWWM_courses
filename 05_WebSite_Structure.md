# Structure d'un site Web

## 📁 Structure typique d’un projet Web

```plaintext
my-web-project/
├── public/                 # Fichiers statiques accessibles directement (HTML, images, favicon)
│   ├── index.html          # Point d’entrée HTML principal
│   ├── favicon.ico         # Icône du site
│   └── assets/             # Images, polices, fichiers statiques divers
├── src/                    # Code source (JavaScript, CSS, composants, etc.)
│   ├── css/                # Styles (CSS, SCSS)
│   ├── js/                 # Scripts JavaScript (ou TS)
│   ├── components/         # Composants UI (React, Vue, Angular, etc.)
│   └── assets/             # Ressources spécifiques au code source (images, fonts)
├── tests/                  # Tests unitaires ou fonctionnels
├── .gitignore              # Fichiers/dossiers à exclure du dépôt Git
├── package.json            # Dépendances et scripts (pour projets Node.js)
├── README.md               # Documentation du projet
└── webpack.config.js       # Configuration de build (ou autre outil comme Vite, Parcel)
```

---

## 🔑 Principes clés pour structurer un projet web

* **Séparer le code source (`src/`) des fichiers statiques** (`public/`)
  Cela facilite le build, la gestion des assets, et clarifie ce qui sera servi au client.

* **Organiser par type / fonctionnalité**
  Par exemple, mettre les composants UI dans un dossier dédié pour faciliter la réutilisation et la maintenance.

* **Ajouter un dossier pour les tests**
  Permet d’isoler les tests et de s’assurer que la base de code est stable.

* **Utiliser un fichier README clair**
  Pour expliquer l’objectif, l’installation, l’utilisation, et la contribution au projet.

* **Gestion des dépendances et scripts** (avec `package.json`)
  Pour automatiser les builds, tests, et déploiements.

---

## 🛠️ Exemple simple pour un projet HTML/CSS/JS pur

```plaintext
my-simple-site/
├── index.html
├── css/
│   └── style.css
├── js/
│   └── main.js
├── images/
│   └── logo.png
└── README.md
|__ .gitignore 
```

| Fichier         | Rôle / Description                                                |
| --------------- | ----------------------------------------------------------------- |
| `robots.txt`    | Indique aux moteurs de recherche quelles pages indexer ou ignorer |
| `favicon.ico`   | Icône affichée dans l’onglet du navigateur                        |
| `sitemap.xml`   | Plan du site pour aider les moteurs de recherche                  |
| `README.md`     | Documentation du projet                                           |
| `.gitignore`    | Fichiers/dossiers à exclure du suivi Git                          |
| `.env`          | Variables d’environnement (souvent dans projets backend/frontend) |
| `package.json`  | Liste les dépendances et scripts (projets Node.js)                |
| `LICENSE`       | Licence du projet (ex: MIT, GPL)                                  |
| `CNAME`         | Pour les projets GitHub Pages, indique le domaine personnalisé    |
| `humans.txt`    | Infos sur les créateurs du site (moins courant)                   |
| `Dockerfile`    | Instructions pour créer une image Docker                          |
| `.editorconfig` | Standardise le formatage du code entre éditeurs                   |

