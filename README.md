# Maison Ondé · Salon de coiffure mixte · Lyon

Site vitrine one-page éditorial premium pour un salon de coiffure mixte à Lyon (12 rue Auguste Comte, 69002).

## 🎨 Identité

- **Palette** : Beige cream (#FAF8F5) + brown deep (#1F1B17) + accent caramel (#A07551)
- **Typo** : Cormorant Garamond (display serif italique) + Manrope (body sans-serif)
- **Ton** : Éditorial premium, calme, masculin/féminin équilibré
- **Cible** : Clientèle exigeante Lyon — coupe, couleur, balayage, barbe, mariage

## 🏗️ Stack

- HTML5 sémantique + CSS3 + Vanilla JS (zéro framework)
- Schema.org HairSalon (SEO local)
- i18n FR/EN intégré
- Hero vidéo full-bleed
- Filtres galerie réalisations (femme/homme/enfant)
- Animations scroll-reveal douces
- Cookie banner RGPD
- Newsletter inline
- Mobile-first responsive

## 📦 Structure

```
maison-onde/
├── index.html              ← page complète one-page (~97 KB)
├── assets/
│   ├── images/
│   │   ├── logo.webp       ← logo principal
│   │   ├── logo-mark.svg   ← marque SVG vectorielle
│   │   ├── salon-interior.webp
│   │   └── cuts/           ← 9 photos de coupes (.webp ~40 KB chacune)
│   └── video/
│       └── hero.mp4        ← vidéo hero (~8 MB)
├── .gitignore
├── .nojekyll
└── README.md
```

## 🚀 Lancement local

```bash
cd maison-onde
python -m http.server 8000
```

Puis ouvrir <http://localhost:8000>.

## 🌐 Production

Live : <https://nadnad250.github.io/maison-onde/>

## 📐 Performance

- Hero vidéo `<video preload="metadata">` (chargement progressif)
- Images **WebP** optimisées (cuts de 1.8 MB PNG → 40 KB WebP, -98%)
- Total assets : ~9 MB (essentiellement la vidéo hero)
- Aucun framework, zéro dépendance npm

## 🔒 Conformité

- Cookie banner avec consent (accept/refuse/custom)
- Schema.org HairSalon avec horaires + adresse + tel + geo
- `prefers-reduced-motion` respecté sur toutes les animations
- Touch targets ≥ 44px (WCAG AA)

## 📄 Licence

Code privé — usage commercial réservé.
