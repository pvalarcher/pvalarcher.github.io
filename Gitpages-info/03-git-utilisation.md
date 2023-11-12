
### **Manuel d'utilisation de Git**

**Introduction à Git**

Git est un système de contrôle de version décentralisé. Il est conçu pour gérer des projets de toutes tailles avec rapidité et efficacité. Git est utilisé pour suivre les modifications dans le code source au cours du développement de logiciels.

**Configuration initiale**

Après avoir installé Git, vous devez configurer votre identité. Ouvrez le terminal ou Git Bash et tapez :

```bash
git config --global user.name "Votre Nom"
git config --global user.email "votre.email@example.com"
```

**Créer un nouveau dépôt (repository)**

1. **Initialiser un dépôt :**
   - Naviguez dans le dossier de votre projet depuis le terminal.
   - Tapez `git init`. Cela crée un nouveau sous-dossier nommé `.git` qui contient tous les fichiers nécessaires au dépôt.

2. **Ajouter des fichiers :**
   - Ajoutez des fichiers à votre dépôt en utilisant `git add <nom-du-fichier>` ou `git add .` pour ajouter tous les fichiers.

3. **Faire un commit :**
   - Après avoir ajouté les fichiers, faites votre premier commit avec `git commit -m "Votre message de commit"`.

**Cloner un dépôt existant**

- Si vous voulez copier un dépôt existant, utilisez `git clone <url-du-dépôt>`. Par exemple : `git clone https://github.com/exemple/projet.git`.

**Travailler avec des branches**

1. **Créer une branche :**
   - Utilisez `git branch <nom-de-la-branche>` pour créer une nouvelle branche.
   - Pour basculer sur cette branche, utilisez `git checkout <nom-de-la-branche>`.

2. **Fusionner des branches :**
   - Pour fusionner une branche dans une autre, basculez d'abord sur la branche réceptrice (`git checkout master`, par exemple).
   - Puis fusionnez avec `git merge <nom-de-la-branche>`.

**Mettre à jour le dépôt**

- Pour mettre à jour votre dépôt local avec la version la plus récente du serveur, utilisez `git pull`.

**Envoyer des modifications**

- Après avoir fait des commits locaux, vous pouvez envoyer ces modifications vers le serveur avec `git push`.

**Visualiser l'historique**

- Pour voir l'historique des commits, utilisez `git log`. Vous pouvez voir une version simplifiée avec `git log --oneline`.

**Gérer les conflits**

- Les conflits surviennent lorsque deux branches ont des modifications contradictoires. Git vous avertira lorsqu'il y a des conflits. Vous devrez les résoudre manuellement avant de pouvoir compléter une fusion.
