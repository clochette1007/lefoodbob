# 🍕 Lefoodbob Site

Site web pour Lefoodbob - Votre destination culinaire

## Déploiement sur Vercel via GitHub

### Prérequis
- Compte GitHub
- Compte Vercel

### Instructions de déploiement

1. **Initialiser Git et pousser sur GitHub :**
   ```bash
   git init
   git add .
   git commit -m "Initial commit: Lefoodbob site"
   git branch -M main
   git remote add origin https://github.com/VOTRE_USERNAME/lefoodbob-site.git
   git push -u origin main
   ```

2. **Connecter à Vercel :**
   - Allez sur [vercel.com](https://vercel.com)
   - Connectez-vous avec votre compte GitHub
   - Cliquez sur "New Project"
   - Sélectionnez votre repository GitHub
   - Cliquez sur "Deploy"

### Structure du projet
```
lefoodbob-site/
├── index.html          # Page principale
├── README.md          # Ce fichier
└── .gitignore         # Fichiers à ignorer par Git
```

### Développement local
Ouvrez simplement `index.html` dans votre navigateur pour voir le site.

### Technologies utilisées
- HTML5
- CSS3 (avec Flexbox et Grid)
- JavaScript vanilla 