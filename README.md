# n8n × Claude — Pack Digital

Site statique HTML prêt à déployer sur **GitHub Pages** et **Vercel**.

## 🚀 Déploiement sur Vercel

### Option 1 — Via l'interface Vercel
1. Pousse ce dossier sur un repo GitHub
2. Va sur [vercel.com](https://vercel.com) → **New Project**
3. Importe le repo → Vercel détecte automatiquement le site statique
4. Clique **Deploy** ✅

### Option 2 — Via Vercel CLI
```bash
npm i -g vercel
cd n8n-claude-pack-digital
vercel
```

## 🐙 Déploiement sur GitHub Pages

1. Crée un repo GitHub (ex: `n8n-claude-pack-digital`)
2. Pousse les fichiers :
```bash
git init
git add .
git commit -m "init"
git remote add origin https://github.com/TON_USERNAME/n8n-claude-pack-digital.git
git push -u origin main
```
3. Dans le repo → **Settings** → **Pages**
4. Source : `Deploy from a branch` → branche `main` → dossier `/ (root)`
5. Ton site sera disponible à : `https://TON_USERNAME.github.io/n8n-claude-pack-digital/`

## 📁 Structure
```
n8n-claude-pack-digital/
├── index.html      # Page principale
├── vercel.json     # Config Vercel
└── README.md
```
