# 🚀 Portfolio Thomas Sonzogni - Multi-pages Audacieux & Créatif

Portfolio professionnel moderne avec design audacieux, animations fluides et navigation multi-pages.

## 📋 Pages incluses

- **index.html** - Page d'accueil spectaculaire avec hero section
- **about.html** - À propos avec valeurs et intérêts
- **experience.html** - Timeline interactive des expériences
- **education.html** - Formations et certifications
- **skills.html** - Compétences techniques et soft skills
- **projects.html** - Portfolio de projets (template prêt)
- **contact.html** - Page de contact avec formulaire

## 🎨 Design

- **Couleurs** : Orange (#ff6b35) + Bleu (#0066cc) + Noir (#0f0f0f)
- **Typographie** : Poppins pour les titres, Space Mono pour le code
- **Animations** : Transitions fluides, scroll animations, hover effects
- **Responsive** : Adapté mobile, tablette, desktop
- **Moderne** : Gradients, asymétrie, layouts créatifs

## 📁 Structure

```
portfolio/
├── index.html              # Page d'accueil
├── about.html             # À propos
├── experience.html        # Expériences professionnelles
├── education.html         # Formations
├── skills.html            # Compétences
├── projects.html          # Projets
├── contact.html           # Contact & formulaire
├── photo.png              # Ta photo (à ajouter)
└── assets/
    ├── styles.css         # Styles globaux
    └── script.js          # JavaScript
```

## 🚀 Guide d'implémentation

### 1. **Créer le repository GitHub**

```bash
# Va sur GitHub → New repository
# Nomme-le : username.github.io
# (remplace username par ton username GitHub)
```

### 2. **Cloner ou télécharger les fichiers**

**Option A : Via Git (recommandé)**
```bash
git clone https://github.com/username/username.github.io.git
cd username.github.io

# Copie tous les fichiers du portfolio ici
# Puis :
git add .
git commit -m "Initial commit: Portfolio multi-pages"
git push origin main
```

**Option B : Via GitHub Web Interface**
1. Va sur ton repository
2. Add file → Create new file
3. Crée chaque fichier manuellement en copiant le contenu

### 3. **Ajouter ta photo**

1. Prépare une photo carrée (280x280px ou plus)
2. Enregistre-la en PNG ou JPG
3. Renomme-la exactement : **photo.png**
4. Place-la à la racine du repository
5. Commit et push

### 4. **Configuration du formulaire de contact**

Par défaut, le formulaire utilise Formspree. Pour l'activer :

1. Va sur https://formspree.io
2. Crée un compte gratuit
3. Ajoute un nouveau formulaire
4. Dans `contact.html`, remplace :
   ```html
   action="https://formspree.io/f/YOUR_FORM_ID"
   ```
   par ton ID de formulaire

### 5. **Vérifier le déploiement**

1. Attends 1-2 minutes
2. Visite `https://username.github.io`
3. 🎉 C'est live !

## 🎨 Personnalisations

### Changer les couleurs

Dans `assets/styles.css`, modifie les variables :

```css
:root {
    --primary-orange: #ff6b35;  /* Couleur principale 1 */
    --primary-blue: #0066cc;    /* Couleur principale 2 */
    --primary-dark: #0f0f0f;    /* Noir */
    --primary-light: #f5f5f5;   /* Très clair */
}
```

### Ajouter des projets

Dans `projects.html`, ajoute des cartes :

```html
<div class="project-card">
    <div class="project-content">
        <h3 class="project-title">Nom du Projet</h3>
        <p class="project-description">Description...</p>
        <div class="project-tags">
            <span class="project-tag">Power BI</span>
            <span class="project-tag">Python</span>
        </div>
    </div>
</div>
```

### Ajouter des liens personnalisés

Mets à jour dans chaque page :
- Email : thomas.paul.sonzogni@gmail.com → ton email
- LinkedIn : linkedin.com/in/thomas-sonzogni → ton profil
- Téléphone : 06 32 45 13 63 → ton numéro

## 📱 Responsive Design

Le site s'adapte automatiquement à :
- 💻 Desktop (1200px+)
- 📱 Tablette (768px - 1200px)
- 📵 Mobile (< 768px)

## ⚡ Performance

- HTML/CSS/JS pur (pas de framework lourd)
- Chargement rapide
- SEO friendly
- Optimisé pour les moteurs de recherche

## 🔧 Technologies

- HTML5
- CSS3 (Flexbox, Grid, Variables CSS)
- JavaScript vanilla (animations, navigation active)
- Google Fonts (Poppins, Space Mono)

## 📊 Bonnes pratiques appliquées

✅ Navigation intuitive avec liens actifs
✅ Animations au scroll et au hover
✅ Formulaire de contact fonctionnel
✅ Métadonnées SEO
✅ Design accessible
✅ Code propre et commenté
✅ Performance optimisée

## 🚀 Améliorations futures

- [ ] Blog/Articles
- [ ] Intégration API GitHub (afficher tes repos)
- [ ] Mode sombre
- [ ] Filtre par catégorie (projets)
- [ ] Analytics (Google Analytics)
- [ ] Multilingue

## 📞 Support

Si quelque chose ne marche pas :

1. Vérifie les noms de fichiers (sensibles à la casse)
2. Vérifiez la syntaxe HTML/CSS
3. Ouvrez la console du navigateur (F12) pour voir les erreurs
4. Attendez quelques minutes et rafraîchissez

## 📄 Fichiers importants

- **assets/styles.css** - Tous les styles (couleurs, animations, responsive)
- **assets/script.js** - Navigation active, animations au scroll
- **index.html** - Page d'accueil principale
- **contact.html** - Formulaire intégré (Formspree)

## 💡 Pro Tips

1. **Commits réguliers** : À chaque modification, fais un commit
2. **Test local** : Ouvre index.html dans ton navigateur pour tester
3. **Backup** : Garde des copies de tes contenus ailleurs aussi
4. **Mises à jour** : Ajoute régulièrement tes nouveaux projets
5. **SEO** : Complète les meta descriptions dans le <head>

---

**Fait avec ❤️ et beaucoup de data ✨**

© 2024 Thomas Sonzogni. Tous droits réservés.
