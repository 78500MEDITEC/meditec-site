# Meditec – Redesign 2024
## Instructions de déploiement sur GitHub Pages

### Fichiers fournis
- `style.css` — Design system complet (à utiliser sur TOUTES les pages)
- `index.html` — Page d'accueil redesignée
- `mobilite.html` — Page catalogue Mobilité redesignée
- `contact.html` — Page de contact & devis redesignée

### Pour les autres pages catégorie (même structure que mobilite.html)
Copier `mobilite.html` et adapter :
- Le titre (`<title>` et `<h1>`)
- Le breadcrumb
- L'icône et l'eyebrow du page-hero
- Le contenu catalogue (sections + produits)
- L'attribut `class="active"` sur le bon lien de nav

Pages à créer sur ce modèle :
- `maintien-domicile.html`
- `salle-de-bain.html`
- `confort-bien-etre.html`
- `incontinence.html`
- `aide-vie-quotidienne.html`

### Déploiement GitHub Pages
1. Copier tous les fichiers dans votre repo `78500MEDITEC/meditec-france.com`
2. Remplacer les anciens fichiers HTML et CSS
3. Le fichier `style.css` doit être à la **racine** du repo (même niveau que les HTML)
4. Vos images existantes (webp, jpg) restent inchangées — les chemins sont identiques

### Polices (Google Fonts)
Le CSS charge automatiquement Inter + Lora via Google Fonts.
Si vous voulez éviter la dépendance externe, téléchargez les polices sur fonts.google.com et hébergez-les dans un dossier `/fonts/`.

### Personnalisation des couleurs
Dans `style.css`, section `:root`, modifiez :
- `--blue-700` : couleur principale (actuellement `#1A4F72`)
- `--blue-500` : couleur des CTA et liens (actuellement `#2A7AB5`)
- `--accent`   : couleur teal des badges (actuellement `#1FB8A0`)
