

### **Guide d'utilisation des Pages GitHub**

**Introduction**

GitHub Pages est un service de GitHub permettant de publier des sites web directement à partir d'un dépôt GitHub. C'est un outil idéal pour héberger des pages personnelles, des portfolios, des projets de documentation, et même des blogs.

**Prérequis**

- Un compte GitHub. Si vous n'en avez pas, vous pouvez en créer un sur [github.com](https://github.com/).
- Une connaissance de base de Git et GitHub.
- (Optionnel) Des connaissances en HTML/CSS pour personnaliser votre site.

**Étape 1 : Créer un dépôt pour votre site**

1. Connectez-vous à votre compte GitHub.
2. Cliquez sur le symbole "+" dans le coin supérieur droit et sélectionnez "New repository".
3. Nommez votre dépôt `<votre-nom-dutilisateur>.github.io`. Remplacez `<votre-nom-dutilisateur>` par votre nom d'utilisateur GitHub.
4. (Optionnel) Ajoutez une description, choisissez si le dépôt sera public ou privé, et initialisez-le avec un fichier README.
5. Cliquez sur "Create repository".
6. Générer un ```token``` : une sorte de mot de pass temporaire
	a. Aller dans "Settings"
	b. Aller dans "Developper Settings" : tout en bas
	c. Aller dans "Personnal access tokens" puis "Tokens (classic)"
	d. Generate new token
		1. Donner lui un nom
		2. Choisissez une date d'expiration (fin du semestre ou fin d'année)
		3. Cocher **repo**
		4. Puis "Generate token"
		5. **ATTENTION** : copier cette chaine de caractere dans un fichier que vous appelerez ```token_github-2024.txt``` sur votre ordinateur (vous pouvez vous envoyez ce fichier par mail pour sauvegarde). Ce sera le mot de passe que vous devrez utilisez quand on utilisera Git depuis le terminal.

**Étape 2 : Ajouter du contenu à votre site**

- Vous pouvez créer un fichier `index.html` comme page d'accueil de votre site.
- Ajoutez du contenu HTML/CSS à `index.html`. Vous pouvez également utiliser un générateur de site statique comme Jekyll pour vous aider.
- Une fois que vous avez ajouté du contenu, utilisez Git pour le pousser sur votre dépôt GitHub.

**Étape 3 : Activer GitHub Pages**

1. Allez dans votre dépôt sur GitHub.
2. Cliquez sur "Settings" (Paramètres).
3. Faites défiler vers le bas jusqu'à la section "GitHub Pages".
4. Sous "Source", sélectionnez la branche sur laquelle vous avez poussé votre site (généralement `main`).
5. Cliquez sur "Save".

**Étape 4 : Accéder à votre site**

- Après avoir activé GitHub Pages, votre site sera accessible à l'URL `https://<votre-nom-dutilisateur>.github.io`.
- Chaque fois que vous pousserez de nouveaux changements sur la branche sélectionnée, votre site sera automatiquement mis à jour.



