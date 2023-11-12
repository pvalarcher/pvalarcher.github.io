
### **Manuel d'Installation de Git**

**Pour macOS :**

1. **Installer Git avec Homebrew (méthode recommandée) :**
   - Si vous n'avez pas Homebrew, installez-le en ouvrant le Terminal et en exécutant :
     ```
     /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
     ```
   - Une fois Homebrew installé, installez Git en exécutant :
     ```
     brew install git
     ```

2. **Installer Git directement (alternative) :**
   - Visitez le site [Git SCM](https://git-scm.com/download/mac).
   - Téléchargez le dernier package d'installation de Git pour macOS.
   - Ouvrez le package téléchargé et suivez les instructions pour installer Git.

3. **Vérifier l'installation :**
   - Ouvrez le Terminal et tapez `git --version` pour vérifier que Git est bien installé.

**Pour Windows :**

1. **Télécharger le programme d'installation :**
   - Rendez-vous sur [Git SCM](https://git-scm.com/download/win).
   - Le téléchargement devrait commencer automatiquement. Si ce n'est pas le cas, cliquez sur le lien pour télécharger manuellement.

2. **Exécuter le programme d'installation :**
   - Ouvrez le fichier `.exe` téléchargé.
   - Suivez les instructions à l'écran. Vous pouvez laisser la plupart des options par défaut, mais faites attention aux options suivantes :
     - **Choisir l'éditeur par défaut utilisé par Git** : Sélectionnez l'éditeur de votre choix.
     - **Ajuster votre PATH** : Choisissez l'option recommandée pour vous permettre d'utiliser Git depuis la ligne de commande.
     - **Choisir les options SSL/TLS et autres composants** : Laissez les options par défaut.
     - **Configurer la fin de ligne** : Laissez l'option recommandée.
     - **Choisir l'émulateur de terminal pour les commandes Git** : Laissez l'option par défaut (MinTTY).
     - **Configurations supplémentaires** : Laissez les options par défaut.

3. **Vérifier l'installation :**
   - Une fois l'installation terminée, ouvrez le Command Prompt (CMD) ou Git Bash (installé avec Git).
   - Tapez `git --version` pour confirmer que Git a été installé correctement.

---

**Note Importante :** Après avoir installé Git, il est recommandé de configurer votre identité Git (nom et email). Ouvrez le Terminal ou Git Bash et tapez :

```bash
git config --global user.name "Votre Nom"
git config --global user.email "votre.email@example.com"
```

Remplacez "Votre Nom" et "votre.email@example.com" par vos informations personnelles. Cette étape est importante pour s'assurer que vos futurs commits seront correctement attribués à vous.
