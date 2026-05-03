# 🍽️ Carnet de Commandes — Brasserie Cannes la Bocca

## Déploiement Vercel (une seule fois)

### 1. Mettre sur GitHub
Sur github.com, dans ton repo `brasserie-commandes` :
- Clique **"uploading an existing file"**
- Dépose TOUS les fichiers de ce dossier
- Clique **"Commit changes"**

### 2. Déployer sur Vercel
- Va sur vercel.com → connecte-toi avec GitHub
- **"Add New Project"** → sélectionne `brasserie-commandes`
- **Root Directory** : `public`
- Clique **"Deploy"** ✅

### 3. Installer sur Android
- Ouvre l'URL Vercel dans Chrome
- Menu ⋮ → **"Ajouter à l'écran d'accueil"**
- L'appli apparaît comme une vraie appli !

## Structure
```
brasserie-commandes/
├── vercel.json
└── public/
    ├── index.html
    ├── manifest.json
    ├── sw.js
    ├── icon-192.png
    └── icon-512.png
```
