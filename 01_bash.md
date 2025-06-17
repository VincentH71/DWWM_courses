# Commandes BASH

## Navigation dans le système de fichiers

| Commande | Description                             |
| -------- | --------------------------------------- |
| `pwd`    | Affiche le chemin du répertoire courant |
| `ls`     | Liste les fichiers d’un répertoire      |
| `cd`     | Change de répertoire                    |
| `tree`   | Affiche l’arborescence des fichiers     |

---

### 📁 **Gestion des fichiers et répertoires**

| Commande         | Description                                    |
| ---------------- | ---------------------------------------------- |
| `touch fichier`  | Crée un fichier vide                           |
| `mkdir dossier`  | Crée un répertoire                             |
| `cp source dest` | Copie un fichier ou dossier                    |
| `mv source dest` | Déplace ou renomme un fichier/dossier          |
| `rm fichier`     | Supprime un fichier                            |
| `rm -r dossier`  | Supprime un dossier et son contenu             |
| `find`           | Recherche de fichiers selon divers critères    |
| `locate`         | Recherche rapide de fichiers (base de données) |

---

### 📄 **Affichage du contenu des fichiers**

| Commande       | Description                       |
| -------------- | --------------------------------- |
| `cat fichier`  | Affiche le contenu d’un fichier   |
| `less fichier` | Affiche page par page (navigable) |
| `more fichier` | Comme `less`, mais plus simple    |
| `head -n 10`   | Affiche les 10 premières lignes   |
| `tail -n 10`   | Affiche les 10 dernières lignes   |

---

### 🧰 **Manipulation de texte**

| Commande                   | Description                            |
| -------------------------- | -------------------------------------- |
| `grep "mot" fichier`       | Recherche un motif dans un fichier     |
| `sed 's/a/b/' fichier`     | Remplace `a` par `b` (éditeur de flux) |
| `awk '{print $1}' fichier` | Affiche la première colonne            |
| `cut -d":" -f1 fichier`    | Coupe un fichier par délimiteur        |
| `sort`                     | Trie les lignes                        |
| `uniq`                     | Supprime les doublons consécutifs      |

---

### 🔧 **Gestion des processus**

| Commande       | Description                         |
| -------------- | ----------------------------------- |
| `ps`           | Liste les processus actifs          |
| `top` / `htop` | Affiche les processus en temps réel |
| `kill PID`     | Termine un processus par son PID    |
| `jobs`         | Affiche les tâches en arrière-plan  |
| `fg` / `bg`    | Met en avant-plan ou arrière-plan   |

---

### 🔄 **Redirections et pipes**

| Symbole | Description                                 |                                                |
| ------- | ------------------------------------------- | ---------------------------------------------- |
| `>`     | Redirige la sortie vers un fichier (écrase) |                                                |
| `>>`    | Redirige la sortie vers un fichier (ajoute) |                                                |
| `<`     | Lit depuis un fichier                       |                                                |
| \`      | \`                                          | Envoie la sortie d’une commande dans une autre |

---

### 📦 **Réseau et internet**

| Commande        | Description                             |
| --------------- | --------------------------------------- |
| `ping adresse`  | Vérifie la connectivité réseau          |
| `curl URL`      | Télécharge ou interroge des données web |
| `wget URL`      | Télécharge un fichier depuis une URL    |
| `ssh user@host` | Connexion à un serveur distant via SSH  |

---

### ⚙️ **Autres utiles**

| Commande       | Description                            |
| -------------- | -------------------------------------- |
| `man commande` | Affiche le manuel d’une commande       |
| `history`      | Historique des commandes               |
| `alias`        | Crée un raccourci pour une commande    |
| `chmod`        | Modifie les permissions                |
| `chown`        | Change le propriétaire                 |
| `df -h`        | Affiche l’espace disque                |
| `du -sh`       | Affiche la taille d’un dossier/fichier |