# Site Web Personnel - Jean-Christophe Bohin

## Vue d'ensemble

Site web personnel publié avec GitHub Pages, accessible à l'adresse [jc.bohin.net](http://jc.bohin.net).

Le site présente le parcours professionnel de Jean-Christophe Bohin : entrepreneur, advisor et investisseur dans l'écosystème tech européen, co-fondateur de Matters (un product studio).

## Structure du Projet

```
jcbohin.github.io/
├── index.html          # Page principale du site (unique page)
├── CNAME              # Configuration du domaine personnalisé (jc.bohin.net)
├── README.md          # Documentation du repository
├── .gitignore         # Fichiers ignorés par Git
└── claude.md          # Ce fichier - contexte pour Claude AI
```

## Caractéristiques Techniques

### Architecture
- **Type**: Site statique simple, single-page
- **Framework**: Aucun - HTML pur avec CSS inline
- **JavaScript**: Aucun
- **Hébergement**: GitHub Pages
- **Domaine**: jc.bohin.net (via CNAME)

### Style et Design
- Design minimaliste et épuré
- CSS inline dans `<style>` dans le `<head>`
- Palette de couleurs sobre : fond gris clair (#EEE), texte gris foncé (#444)
- Typographie : police sans-serif, taille de base 1.2em
- Largeur maximale : 40em pour une lecture confortable
- Responsive : adapté aux écrans mobiles via meta viewport
- Print-friendly : styles d'impression optimisés

### Langue
- **Langue principale**: Français
- Tout le contenu est en français

## Contenu

Le site se compose d'un article unique avec :
- **Header** : Nom (h1)
- **Section** : Présentation professionnelle en plusieurs paragraphes :
  - Rôles : entrepreneur, advisor, investisseur
  - Expérience : 10+ ans stratégie d'entreprise, 15+ ans accompagnement ventures tech
  - Entreprise actuelle : Matters (product studio)
  - Approche : expertise produit, design et technologie
  - Investissements : Limited Partner dans plusieurs fonds VC
  - Call-to-action : Lien LinkedIn pour contact

## Conventions de Modification

### Mise à jour du contenu
- Modifier directement `index.html`
- Maintenir la structure sémantique HTML5 : `<article>`, `<header>`, `<section>`
- Utiliser `<strong>` pour les éléments importants
- Conserver le style minimaliste

### Mise à jour du style
- Le CSS est inline dans le `<head>` de `index.html`
- Conserver la cohérence de la palette de couleurs
- Maintenir le responsive design (max-width: 40em)
- Préserver les styles d'impression

### Bonnes pratiques
- Tester le site en local avant de commit
- Conserver la simplicité : pas de framework, pas de JavaScript sauf nécessité
- S'assurer que le site reste léger et rapide à charger
- Vérifier la compatibilité mobile
- Maintenir l'accessibilité

## Déploiement

Le site est automatiquement déployé via GitHub Pages lorsque des modifications sont poussées sur la branche principale.

**URL de production**: http://jc.bohin.net

## Fichiers Spéciaux

### CNAME
Configure le domaine personnalisé pour GitHub Pages. Ne pas supprimer.

## Contact

Pour toute question ou projet, contacter Jean-Christophe sur [LinkedIn](http://linkedin.com/in/jcbohin/).
