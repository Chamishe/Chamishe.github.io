# 🚀 Publier sur GitHub Pages

## 1️⃣ Créer un _repository_ à partir du template

1. Cliquez sur **Use this template** (en haut à droite)
2. Choisissez **Create a new repository**
3. Nommez le : `<votre-username>.github.io`
   - ⚠️ Remplacez `votre-username` par votre nom d'utilisateur GitHub
4. Cochez **Public**
5. Cliquez sur **Create repository**

## 2️⃣ Cloner et modifier les fichiers

```bash
git clone git@github.com:votre-username/votre-username.github.io.git

# Modifier les fichiers (index.html, page.html, style.css, script.js)

git add .
git commit -m "Initial commit: site personnel"

# Publier
git push
```

## 3️⃣ Activer GitHub Pages

1. **Settings** > **Pages**
2. Sous **Source**, sélectionnez **Deploy from a branch**
3. Sous **Branch**, sélectionnez **main** puis **/ (root)**
4. Cliquez sur **Save**

## 4️⃣ Accéder à votre site

Quelques minutes plus tard, votre site sera disponible à l'adresse :
```
https://votre-username.github.io
```

**Testez localement** : Ouvrez `index.html` dans votre navigateur avant de publier

# 📁 Structure du projet

```
votre-username.github.io/
├── index.html       # Page d'accueil
├── style.css        # Styles du site
├── script.js        # Interactions JavaScript
├── pages/           # Dossier pour pages supplémentaires
│   └── about.html   # Exemple de page supplémentaire
│   └── style.css    # Style de la page supplémentaire
└── README.md        # Ce fichier
```

# 📚 Aller plus loin

- [Documentation GitHub Pages](https://docs.github.com/en/pages)
- [Personnaliser un site Jekyll](https://jekyllrb.com/docs/)
