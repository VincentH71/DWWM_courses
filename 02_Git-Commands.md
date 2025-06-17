# Commandes Git

### 🔧 **Configuration initiale**

| Commande                                             | Description                       |
| ---------------------------------------------------- | --------------------------------- |
| `git config --global user.name "Nom"`                | Définit ton nom d'utilisateur Git |
| `git config --global user.email "email@example.com"` | Définit ton email                 |
| `git config --list`                                  | Affiche la configuration actuelle |

---

### 📁 **Initialisation et clonage**

| Commande        | Description                                     |
| --------------- | ----------------------------------------------- |
| `git init`      | Initialise un dépôt Git dans le dossier courant |
| `git clone URL` | Clone un dépôt distant localement               |

---

### 📄 **Ajout et enregistrement des modifications**

| Commande                   | Description                                         |
| -------------------------- | --------------------------------------------------- |
| `git status`               | Affiche les fichiers modifiés, en attente de commit |
| `git add fichier`          | Ajoute un fichier au prochain commit                |
| `git add .`                | Ajoute tous les fichiers modifiés                   |
| `git commit -m "message"`  | Enregistre les modifications avec un message        |
| `git commit -am "message"` | Ajoute *et* commit (modifications déjà suivies)     |

---

### 📜 **Historique**

| Commande            | Description                               |
| ------------------- | ----------------------------------------- |
| `git log`           | Affiche l’historique des commits          |
| `git log --oneline` | Affiche un historique simplifié           |
| `git diff`          | Montre les différences entre les versions |

---

### 🔁 **Branches**

| Commande                      | Description                                   |
| ----------------------------- | --------------------------------------------- |
| `git branch`                  | Liste les branches locales                    |
| `git branch nom-branche`      | Crée une nouvelle branche                     |
| `git checkout nom-branche`    | Bascule vers une autre branche                |
| `git checkout -b nom-branche` | Crée et change de branche                     |
| `git merge nom-branche`       | Fusionne une branche dans la branche courante |

---

### 🔄 **Mise à jour et synchronisation**

| Commande                    | Description                                             |
| --------------------------- | ------------------------------------------------------- |
| `git pull`                  | Récupère et fusionne les modifications du dépôt distant |
| `git push`                  | Envoie les commits vers le dépôt distant                |
| `git push -u origin branch` | Pousse une branche et crée le suivi                     |

---

### 🗑️ **Annulation et nettoyage**

| Commande              | Description                                      |
| --------------------- | ------------------------------------------------ |
| `git restore fichier` | Annule les changements non ajoutés (`git 2.23+`) |
| `git reset fichier`   | Retire un fichier du staging area                |
| `git reset --hard`    | Annule tous les changements non commités         |
| `git clean -fd`       | Supprime les fichiers/dossiers non suivis        |
