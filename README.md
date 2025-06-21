# Vitr'Alex - Site Vitrine Professionnel

Site vitrine moderne et responsive pour Vitr'Alex, spécialiste en lavage de vitres et nettoyage de locaux à Grenoble et dans l'Isère.

![Vitr'Alex Logo](img/Vitr'Alex_logo.png)

## 🎯 À propos du projet

Site web professionnel développé pour Vitr'Alex, auto-entrepreneur spécialisé dans :
- **Lavage de vitres** pour particuliers et professionnels
- **Nettoyage de locaux** (bureaux, commerces, résidentiel)
- **Entretien régulier** et interventions ponctuelles

**Zone d'intervention :** Grenoble et agglomération, Isère (38)

## ✨ Fonctionnalités

### 🎨 Design & UX
- **Design moderne** et professionnel
- **Responsive design** (mobile-first)
- **Animations fluides** et effets visuels
- **Navigation intuitive** avec menu hamburger mobile
- **Charte graphique** respectant l'identité de marque (#6BA8C5, #F2F2F2, #252525)

### 📱 Fonctionnalités techniques
- **Header fixe** avec logo intégré
- **Formulaire de contact** fonctionnel (mailto)
- **Bouton d'appel direct** optimisé mobile
- **Smooth scrolling** entre les sections
- **Animations au scroll** (Intersection Observer)
- **Performance optimisée** (CSS/JS vanilla)

### 🔍 SEO & Référencement
- **SEO local** optimisé pour Grenoble/Isère
- **Schema.org markup** pour le référencement local
- **Meta tags** complets (Open Graph, Twitter Cards)
- **Structure HTML sémantique**
- **Mots-clés géolocalisés** intégrés
- **Contenu optimisé** pour les recherches locales

## 🛠️ Technologies utilisées

- **HTML5** - Structure sémantique
- **CSS3** - Styling moderne avec variables CSS
- **JavaScript ES6** - Interactions et animations
- **Responsive Design** - Mobile-first approach
- **SEO avancé** - Schema.org, meta tags

## 📂 Structure du projet

```
Vitr-Alex/
├── README.md
├── LICENSE
├── main.html              # Page principale
├── img/
    └── Vitr'Alex_logo.png # Logo de l'entreprise
```

## 🚀 Installation et utilisation

### Prérequis
- Navigateur web moderne
- Serveur web local (optionnel pour le développement)

### Installation
```bash
# Cloner le repository
git clone https://github.com/RochesLaurent/Vitr-Alex.git

# Accéder au dossier
cd Vitr-Alex

# Ouvrir avec un serveur local (optionnel)
# Option 1 : Python
python -m http.server 8000

# Option 2 : Node.js
npx http-server

# Option 3 : Live Server (VS Code)
# Installer l'extension Live Server et clic droit > "Open with Live Server"
```

### Utilisation
1. Ouvrir `main.html` dans un navigateur
2. Le site est entièrement fonctionnel en local
3. Pour la production, déployer sur un hébergeur web

## 📞 Contact et informations

**Vitr'Alex**
- **Téléphone :** 06.29.97.15.93
- **Email :** vitralexgrenoble@outlook.fr
- **Zone :** Grenoble et agglomération, Isère (38)
- **Services :** Lavage vitres, nettoyage locaux

## 🔧 Personnalisation

### Modifier les informations de contact
Dans `main.html`, rechercher et modifier :
```javascript
// Téléphone
href="tel:+33629971593"

// Email
vitralexgrenoble@outlook.fr
```

### Changer les couleurs
Dans le CSS, modifier les variables :
```css
:root {
    --primary-color: #6BA8C5;    /* Bleu principal */
    --secondary-color: #F2F2F2;  /* Gris clair */
    --text-dark: #252525;        /* Texte foncé */
}
```

### Ajouter du contenu
- **Services :** Modifier la section `#services`
- **Témoignages :** Éditer `.testimonials-grid`
- **Zone d'intervention :** Adapter `.coverage-cities`

## 📈 SEO et référencement

### Mots-clés ciblés
- **Principaux :** "laveur vitres Grenoble", "nettoyage locaux Isère"
- **Longue traîne :** "lavage vitres professionnel Grenoble", "nettoyage bureaux Isère"
- **Géolocalisés :** Toutes les villes de l'agglomération grenobloise

### Optimisations incluses
- ✅ Schema.org markup pour business local
- ✅ Meta descriptions optimisées
- ✅ Structure Hn logique
- ✅ Alt text pour images
- ✅ URLs propres et descriptives
- ✅ Temps de chargement optimisé

## 🚀 Déploiement

### Plateformes recommandées (gratuites)
1. **Netlify** - Déploiement automatique depuis Git
2. **Vercel** - Performance excellente
3. **GitHub Pages** - Intégré à GitHub
4. **Surge.sh** - Déploiement simple en ligne de commande

### Commandes de déploiement
```bash
# Netlify
netlify deploy --prod

# Vercel
vercel --prod

# Surge
surge main.html
```

## 📝 Todo / Améliorations futures

- [ ] Intégrer Google Analytics
- [ ] Ajouter un blog pour le SEO
- [ ] Système de prise de rendez-vous en ligne
- [ ] Galerie photos des réalisations
- [ ] Chat/WhatsApp intégré
- [ ] Version multilingue
- [ ] PWA (Progressive Web App)
- [ ] Optimisation Core Web Vitals

## 🤝 Contribution

1. Fork le projet
2. Créer une branche feature (`git checkout -b feature/nouvelle-fonctionnalite`)
3. Commit les changements (`git commit -am 'Ajout nouvelle fonctionnalité'`)
4. Push vers la branche (`git push origin feature/nouvelle-fonctionnalite`)
5. Créer une Pull Request

## 📄 Licence

Ce projet est sous licence MIT. Voir le fichier [LICENSE](LICENSE) pour plus de détails.

## 👨‍💻 Développeur

**Site créé par :** [Votre Nom]
**Contact :** [votre@email.fr]
**Spécialité :** Création de sites vitrine pour auto-entrepreneurs

---

## 📊 Statistiques du projet

- **Lignes de code :** ~1200
- **Taille :** < 100KB
- **Performance :** 95+ PageSpeed
- **Compatibilité :** Tous navigateurs modernes
- **Responsive :** Mobile, tablette, desktop

---

*Dernière mise à jour : Janvier 2025*
