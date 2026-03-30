# Portfolio Thomas Sonzogni

Portfolio professionnel single-page, minimaliste et authentique. Design sérieux et crédible pour une Data Analyst.

## 🎯 Caractéristiques

✅ **Une seule page** - Tout en scroll continu
✅ **Design professionnel** - Bleu marine + gris, très sérieux
✅ **Authentique & crédibilisant** - Minimaliste et épuré
✅ **100% responsive** - Parfait sur PC et mobile
✅ **Navigation intuitive** - Menu sticky avec liens actifs
✅ **Basé sur CV à jour** - Toutes tes infos et projets

## 📁 Structure

```
username.github.io/
├── index.html      (Tout ton portfolio)
├── photo.png       (Ta photo 280x280px)
└── README.md       (Ce fichier)
```

**C'est tout ce qu'il te faut !** Aucun dossier `assets/` complexe.

## 🚀 Installation rapide

### 1️⃣ Créer le repository

```bash
# Sur GitHub.com
# Crée un repo nommé : username.github.io
# (remplace username par ton username GitHub)
# Rends-le public
```

### 2️⃣ Télécharger les fichiers

- Clique sur les fichiers ci-dessous pour télécharger
- Tu auras : `index.html` + `README.md` + `_config.yml`

### 3️⃣ Ajouter ta photo

- Enregistre une photo carrée : 280x280px (ou plus)
- Formate : PNG ou JPG
- Renomme-la exactement : **photo.png**
- Place-la à la racine du repository (même niveau que index.html)

### 4️⃣ Uploader sur GitHub

**Option A : Web Interface (plus simple)**
1. Va sur `github.com/username/username.github.io`
2. Click **Add file** → **Upload files**
3. Glisse/dépose `index.html`, `photo.png`, `README.md`
4. Click **Commit changes**

**Option B : Git (plus professionnel)**
```bash
git clone https://github.com/username/username.github.io.git
cd username.github.io

# Copie tes fichiers ici
# Puis :
git add .
git commit -m "Portfolio initial"
git push origin main
```

### 5️⃣ C'est live ! 🎉

- Attends 1-2 minutes
- Visite `https://username.github.io`
- Ton portfolio est en ligne !

## ✏️ Comment modifier le contenu

### Via GitHub Web (recommandé pour les petites modifs)

1. Va sur ton repository
2. Clique sur `index.html`
3. Clique le crayon ✏️ (Edit)
4. Modifie le texte
5. Scroll en bas → **Commit changes**
6. Attends 30 sec, rafraîchis ton site (Ctrl+F5)

### Via Git (pour des modifications régulières)

```bash
# Clone ton repo (une seule fois)
git clone https://github.com/username/username.github.io.git

# Modifie index.html dans VS Code, etc.

# Puis commit/push
git add .
git commit -m "Mise à jour expériences"
git push origin main
```

## 📝 Sections que tu peux modifier

### 1. **Texte du Hero** (Haut de la page)
```html
<h1>Thomas Sonzogni</h1>
<div class="hero-title">Data Analyst • Gestion de Projets Data</div>
```

### 2. **À propos**
Change le texte dans la section `<!-- À Propos -->`

### 3. **Expérience**
Ajoute/modifie tes expériences dans `<!-- Expérience -->`

### 4. **Formation**
Modifie dans `<!-- Formation -->`

### 5. **Compétences**
Ajoute/retire des tags dans `<!-- Compétences -->`

### 6. **Contact**
- Email : `thomas.paul.sonzogni@gmail.com`
- LinkedIn : `linkedin.com/in/thomas-sonzogni`
- Téléphone : `06 32 45 13 63`

## 🎨 Personnalisations avancées

### Changer les couleurs

Cherche cette section au début du CSS :

```css
:root {
    --primary: #1f2937;      /* Gris très foncé - titres */
    --accent: #2563eb;       /* Bleu - accents et liens */
    --bg-light: #f3f4f6;     /* Très léger - fond */
}
```

**Idées de couleurs pro :**
- Bleu marine : `#1f2937`
- Bleu professionnel : `#2563eb`
- Gris foncé : `#374151`
- Vert : `#059669`
- Slate : `#475569`

### Changer la photo

- Remplace simplement le fichier `photo.png` par ta nouvelle photo
- Même nom, même dossier
- Push sur GitHub

## 💡 Conseils

✅ **Test local avant de pusher** - Ouvre simplement `index.html` dans ton navigateur
✅ **Ctrl+F5 pour voir les changements** - Force le rechargement du cache
✅ **Commits clairs** - "Ajout projet Power BI" vs "modif"
✅ **Mets à jour régulièrement** - Ajoute tes nouveaux projets
✅ **Mobile first** - Teste toujours sur ton téléphone

## 🔍 Sections du portfolio

1. **Hero** - Présentation avec photo
2. **À propos** - Bio + valeurs
3. **Expérience** - Tes jobs avec détails
4. **Formation** - Diplômes + projet principal
5. **Compétences** - Outils, méthodologies, soft skills, langues
6. **Contact** - Email, LinkedIn, téléphone

## 📱 Responsive

Le site s'affiche parfaitement sur :
- 💻 Desktop (1200px+)
- 📱 Tablette (768px+)
- 📵 Mobile (< 768px)

Aucun travail supplémentaire à faire !

## ⚡ Performance

- HTML/CSS pur (pas de dépendances lourdes)
- Chargement ultra rapide
- SEO optimisé
- Lighthouse score excellent

## 🆘 Dépannage

### Le site ne s'affiche pas
- Vérifie que le repo s'appelle `username.github.io`
- Vérifie que le repo est **public**
- Attends 2-3 minutes
- Rafraîchis (Ctrl+F5)

### La photo ne s'affiche pas
- Fichier s'appelle exactement `photo.png` ?
- Est à la racine du repo ?
- Format PNG ou JPG ?

### Les styles ne s'appliquent pas
- Ouvre F12 (console)
- Vérifies qu'il n'y a pas d'erreurs

### Lien ne marche pas
- Vérifie l'URL (email, LinkedIn, téléphone)

## 🎯 À faire après setup

1. ✅ Ajoute ta photo
2. ✅ Complète tes expériences
3. ✅ Mets à jour les liens (email, LinkedIn)
4. ✅ Teste sur mobile
5. ✅ Partage l'URL sur LinkedIn/CV

## 📊 Next Steps

- Ajoute ton portfolio à ton CV
- Partage le lien sur LinkedIn
- Envoie-le dans les candidatures
- Mets à jour régulièrement

---

**Portfolio authentique et professionnel ✨**

Questions ? Utilise la console (F12) ou remonte les problèmes sur GitHub.
