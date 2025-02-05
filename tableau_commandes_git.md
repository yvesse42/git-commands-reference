### **Gestion des branches**

| **Commande** | **Description** |
| --- | --- |
| `git branch` | Liste toutes les branches locales. |
| `git branch -a` | Liste toutes les branches (locales et distantes). |
| `git branch -r` | Liste uniquement les branches distantes. |
| `git branch <branch-name>` | Crée une nouvelle branche locale. |
| `git branch -d <branch-name>` | Supprime une branche locale (uniquement si elle est complètement fusionnée). |
| `git branch -D <branch-name>` | Supprime de force une branche locale (même si elle n'est pas fusionnée). |
| `git branch -m <old-branch> <new-branch>` | Renomme une branche locale. |

---

### **Changement et navigation**

| **Commande** | **Description** |
| --- | --- |
| `git checkout <branch-name>` | Bascule vers la branche locale spécifiée. |
| `git checkout -b <branch-name>` | Crée une nouvelle branche et bascule dessus en une seule commande. |

---

### **Intégration et mises à jour**

| **Commande** | **Description** |
| --- | --- |
| `git merge <branch-name>` | Fusionne la branche spécifiée dans la branche actuelle. |
| `git rebase <branch-name>` | Rebase la branche actuelle sur la branche spécifiée. |
| `git pull` | Récupère les mises à jour du dépôt distant et les fusionne dans la branche actuelle. |
| `git pull origin <branch-name>` | Récupère et fusionne une branche distante spécifique dans la branche actuelle. |
| `git cherry-pick <commit-hash>` | Applique un commit d'une branche à la branche actuelle. |

---

### **Opérations sur les branches distantes**

| **Commande** | **Description** |
| --- | --- |
| `git push origin <branch-name>` | Pousse une branche locale vers le dépôt distant. |
| `git push origin --delete <branch-name>` | Supprime une branche distante. |
| `git push` | Pousse les modifications locales vers le dépôt distant pour la branche actuelle. |
| `git push -u origin <branch-name>` | Pousse une branche et configure une branche de suivi avec le dépôt distant. |

---

### **Récupération des mises à jour**

| **Commande** | **Description** |
| --- | --- |
| `git fetch` | Récupère les mises à jour du dépôt distant sans modifier le répertoire de travail. |
| `git fetch --all` | Récupère les mises à jour pour toutes les branches distantes. |
| `git remote show origin` | Affiche les détails du dépôt distant, y compris les branches. |

---

### **Historique et journaux**

| **Commande** | **Description** |
| --- | --- |
| `git log <branch-name>` | Affiche l'historique des commits d'une branche spécifique. |
| `git log --oneline --graph --decorate` | Affiche un historique compact des commits avec une représentation graphique des branches. |
