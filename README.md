# Landing Page Consuel

Landing page professionnelle pour le CONSUEL (Comité National pour la Sécurité des Usagers de l'Électricité).

## 🌐 Accès en ligne (GitHub Pages)

| Page | URL |
|------|-----|
| 🏠 Landing page | https://marcpiriouconsuel.github.io/landing-page-test/ |
| 🏐 Jeu de balle au prisonnier | https://marcpiriouconsuel.github.io/landing-page-test/game.html |

> Le déploiement s'effectue automatiquement à chaque push sur `main` via GitHub Actions.

## 📋 Description

Page web présentant la société Consuel et ses activités dans le domaine de la certification et du contrôle des installations électriques en France.

## ✨ Caractéristiques

- Design épuré et professionnel
- Charte graphique aux couleurs de Consuel (#00A2DE, #66AFE9, #003247)
- Accessibilité WCAG 2.1 AA
- Responsive (mobile, tablette, desktop)
- Animations fluides et navigation intuitive

## 🚀 Utilisation

Ouvrez simplement `index.html` dans votre navigateur web.

Ou utilisez un serveur local :

```bash
# Python 3
python3 -m http.server 8000

# Node.js (avec http-server)
npx http-server

# PHP
php -S localhost:8000
```

Puis accédez à `http://localhost:8000/index.html`

## 📁 Structure

- `index.html` - Page principale avec structure HTML sémantique
- `styles.css` - Feuille de styles CSS avec design responsive
- `game.html` - Jeu de balle au prisonnier multijoueur tactile (2 équipes, même écran)
- `ACCESSIBILITY.md` - Documentation détaillée sur l'accessibilité
- `.github/workflows/deploy-pages.yml` - Workflow de déploiement GitHub Pages

## ♿ Accessibilité

Cette page respecte les normes WCAG 2.1 AA. Consultez `ACCESSIBILITY.md` pour plus de détails.

## 🎨 Sections

- **En-tête** - Logo et navigation
- **Hero** - Message principal
- **À propos** - Mission, expertise, histoire
- **Activités** - 4 principales activités de Consuel
- **Certifications** - Types d'attestations (jaune, verte, bleue, violette)
- **Contact** - Informations pratiques
- **Pied de page** - Liens et informations légales

## 📄 Licence

Ce projet a été créé pour Consuel.