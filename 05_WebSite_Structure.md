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
```
