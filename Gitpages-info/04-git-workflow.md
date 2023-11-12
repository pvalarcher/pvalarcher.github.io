

### **Workflow Git Basique**

1. **Configuration Initiale**
   - Configurer Git avec votre nom et email :
     ```bash
     git config --global user.name "Votre Nom"
     git config --global user.email "votre.email@example.com"
     ```

2. **Créer un Nouveau Dépôt (Local)**
   - Dans votre dossier de projet :
     ```bash
     git init
     ```

3. **Ajouter des Fichiers au Dépôt**
   - Ajouter un fichier spécifique :
     ```bash
     git add <nom-du-fichier>
     ```
   - Ajouter tous les fichiers modifiés :
     ```bash
     git add .
     ```

4. **Faire un Commit**
   - Enregistrer vos modifications dans le dépôt :
     ```bash
     git commit -m "Message expliquant ce commit"
     ```

5. **Connexion à un Dépôt Distant (GitHub, GitLab, Bitbucket, etc.)**
   - Si vous n'avez pas encore de dépôt distant :
     ```bash
     git remote add origin <url-du-dépôt-distant>
     ```
   - L'URL peut être trouvée sur la plateforme hébergeant votre dépôt distant.

6. **Envoyer les Changements sur le Serveur Distant**
   - Lors du premier push, utilisez :
     ```bash
     git push -u origin master
     ```
   - Pour les pushs suivants, vous pouvez simplement utiliser :
     ```bash
     git push
     ```

7. **Mise à jour de Votre Dépôt Local**
   - Pour obtenir les dernières mises à jour du serveur :
     ```bash
     git pull
     ```

8. **Travail avec des Branches**
   - Créer une nouvelle branche et basculer dessus :
     ```bash
     git checkout -b <nom-de-la-branche>
     ```
   - Basculer entre les branches existantes :
     ```bash
     git checkout <nom-de-la-branche>
     ```
   - Fusionner une branche dans votre branche actuelle :
     ```bash
     git merge <nom-de-la-branche>
     ```

9. **Gérer les Conflits**
   - Les conflits surviennent lors de la fusion de branches. Git vous indiquera quels fichiers sont en conflit.
   - Ouvrez ces fichiers et modifiez-les pour résoudre les conflits, puis :
     ```bash
     git add <fichier-résolu>
     git commit
     ```

10. **Utiliser des Tags pour les Versions de Release**
    - Créer un tag :
      ```bash
      git tag <nom-du-tag>
      ```
    - Envoyer les tags sur le dépôt distant :
      ```bash
      git push origin --tags
      ```

### **Bonnes Pratiques**

- **Commit Fréquemment :** Faites des commits petits et significatifs. Chaque commit doit représenter une unité logique de changement.
- **Messages de Commit Clairs :** Chaque message de commit doit clairement décrire ce que le commit fait et pourquoi.
- **Tester Avant de Commit :** Testez votre code localement avant de faire un commit.
- **Pull Régulièrement :** Faites des `git pull` régulièrement pour rester à jour avec le dépôt distant.
- **Utiliser des Branches :** Utilisez des branches pour les nouvelles fonctionnalités, les corrections de bugs, etc., pour garder le développement organisé et éviter les perturbations dans la branche principale (généralement `master` ou `main`).

### **Collaboration et Révision de Code**

Dans une équipe, vous collaborerez souvent via des Pull Requests (PR) ou Merge Requests (MR) :

- **Créer une Pull/Merge Request :** Après avoir poussé votre branche vers le dépôt distant, créez une PR/MR via l'interface web de votre plateforme de gestion de code source.
- **Révision de Code :** Les autres membres de l'équipe peuvent examiner, commenter et suggérer des modifications à votre code.
- **Fusionner dans la Branche Principale :** Une fois approuvée, la PR/MR peut être fusionnée dans la branche principale.

Ce workflow est