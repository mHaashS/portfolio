# Portfolio Personnel

Un portfolio moderne et responsive développé avec HTML, CSS et JavaScript pour présenter vos projets et compétences.

## 🚀 Fonctionnalités

- **Design moderne et responsive** - S'adapte à tous les écrans
- **Navigation fluide** - Menu hamburger pour mobile
- **Animations au scroll** - Effets visuels engageants
- **Section projets** - Présentation de vos réalisations
- **Barres de compétences** - Visualisation de vos compétences
- **Formulaire de contact** - Système de notification intégré
- **Effets de parallaxe** - Animations subtiles
- **Thème moderne** - Palette de couleurs professionnelle

## 📁 Structure du projet

```
Portfolio/
├── index.html          # Page principale
├── styles.css          # Styles CSS
├── script.js           # Logique JavaScript
└── README.md           # Documentation
```

## 🛠️ Personnalisation

### 1. Informations personnelles

Modifiez les éléments suivants dans `index.html` :

- **Nom** : Remplacez "Votre Nom" par votre nom
- **Email** : Changez "votre.email@example.com"
- **Téléphone** : Mettez à jour le numéro de téléphone
- **Localisation** : Modifiez "Paris, France"

### 2. Projets

Dans la section projets, remplacez les exemples par vos vrais projets :

```html
<div class="project-card">
    <div class="project-image">
        <i class="fas fa-laptop-code"></i> <!-- Icône du projet -->
    </div>
    <div class="project-content">
        <h3>Nom de votre projet</h3>
        <p>Description de votre projet...</p>
        <div class="project-tech">
            <span class="tech-tag">Technologie 1</span>
            <span class="tech-tag">Technologie 2</span>
        </div>
        <div class="project-links">
            <a href="URL_DU_PROJET" class="project-link">
                <i class="fas fa-external-link-alt"></i> Voir le projet
            </a>
            <a href="URL_DU_CODE" class="project-link">
                <i class="fab fa-github"></i> Code source
            </a>
        </div>
    </div>
</div>
```

### 3. Compétences

Ajustez les compétences et leurs niveaux dans la section compétences :

```html
<div class="skill-item">
    <span class="skill-name">Nom de la compétence</span>
    <div class="skill-bar">
        <div class="skill-progress" data-width="85%"></div> <!-- Pourcentage -->
    </div>
</div>
```

### 4. Liens sociaux

Mettez à jour les liens sociaux dans la section contact :

```html
<div class="social-links">
    <a href="VOTRE_LINKEDIN" class="social-link">
        <i class="fab fa-linkedin"></i>
    </a>
    <a href="VOTRE_GITHUB" class="social-link">
        <i class="fab fa-github"></i>
    </a>
    <a href="VOTRE_TWITTER" class="social-link">
        <i class="fab fa-twitter"></i>
    </a>
</div>
```

### 5. Couleurs

Modifiez les couleurs dans `styles.css` en changeant les variables CSS :

```css
:root {
    --primary-color: #6366f1;    /* Couleur principale */
    --accent-color: #06b6d4;     /* Couleur d'accent */
    --text-primary: #1e293b;    /* Couleur du texte */
    /* ... autres variables */
}
```

## 🎨 Icônes disponibles

Le portfolio utilise Font Awesome. Voici quelques icônes populaires :

- `fas fa-laptop-code` - Développement web
- `fas fa-mobile-alt` - Application mobile
- `fas fa-chart-line` - Analytics/Dashboard
- `fas fa-gamepad` - Jeu vidéo
- `fas fa-robot` - IA/Machine Learning
- `fas fa-database` - Base de données
- `fas fa-cloud` - Cloud computing

## 📱 Responsive Design

Le portfolio est entièrement responsive et s'adapte à :
- **Desktop** : 1200px et plus
- **Tablet** : 768px à 1199px
- **Mobile** : Moins de 768px

## 🚀 Déploiement

### Option 1 : GitHub Pages
1. Créez un repository GitHub
2. Uploadez vos fichiers
3. Activez GitHub Pages dans les paramètres
4. Votre portfolio sera accessible à `https://votreusername.github.io/nom-du-repo`

### Option 2 : Netlify
1. Créez un compte sur Netlify
2. Glissez-déposez votre dossier
3. Votre site sera déployé automatiquement

### Option 3 : Vercel
1. Créez un compte sur Vercel
2. Connectez votre repository GitHub
3. Déployez en un clic

## 🔧 Fonctionnalités JavaScript

- **Navigation mobile** : Menu hamburger responsive
- **Scroll fluide** : Navigation entre sections
- **Animations** : Effets au scroll et au hover
- **Formulaire** : Validation et notifications
- **Parallaxe** : Effet de profondeur
- **Typing effect** : Animation de frappe pour le titre

## 📝 Notes

- Le formulaire de contact est configuré pour l'affichage uniquement
- Pour un vrai envoi d'emails, intégrez un service comme Formspree ou EmailJS
- Les images de projets peuvent être ajoutées en remplaçant les icônes
- Le portfolio est optimisé pour les performances et le SEO

## 🎯 Prochaines étapes

- Ajouter vos vraies images de projets
- Intégrer un vrai système d'envoi d'emails
- Ajouter un blog ou une section articles
- Intégrer Google Analytics
- Optimiser les images avec WebP
- Ajouter des tests unitaires

---

**Développé avec ❤️ pour présenter vos projets de manière professionnelle**

