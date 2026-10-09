# Documentation Élan Fitness

## Présentation du Projet
Le projet **Élan Fitness** consiste à transformer un site web initialement conçu sous forme de *one-page* en un **site multipage**, afin d'améliorer l'organisation du contenu, la navigation et l'expérience utilisateur globale.

---

## Pages du Site
1. **Accueil (`index.html`)** : Présentation générale et accès aux informations principales.
2. **À propos (`apropos.html`)** : Présentation de l'établissement, de sa vision.
3. **Programmes (`programmes.html`)** : Détail des activités sportives et des services proposés.
4. **Contact (`contact.html`)** : Coordonnées, localisation et formulaire de prise de contact.

---

## Méthodologie de Travail (Agile / Scrum)
Le projet est conduit selon les principes méthodologiques **Agile/Scrum** :
- **Product Backlog** : Recensement et priorisation des besoins et fonctionnalités.
- **Sprint Planning** : Définition des objectifs de chaque sprint.
- **Daily Scrum** : Synchronisation quotidienne.
- **Sprint Review & Rétrospective** : Démonstration des livrables et amélioration continue.

---

## Bonnes Pratiques SEO & Stratégie SEA
- **SEO (Référencement Naturel)** :
  - Balises `<title>` et métadonnées `<meta name="description">` uniques par page.
  - Hiérarchie stricte des titres (`h1`, `h2`, `h3`).
  - URLs claires et sémantiques.
  - Balises `alt` descriptives sur toutes les images.
  - Maillage interne optimisé et performance de chargement soignée.
- **SEA (Référencement Payant)** :
  - Identification des mots-clés commerciaux, du ciblage géographique et des pages de destination cibles (*landing pages*).

---

## Spécifications Techniques (HTML5 & CSS3)

### Structure HTML5 Sémantique ?
- Balises structurelles : `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<footer>`.
- Formulaires accessibles : `<form>`, `<label>`, `<input>`, `<textarea>`, `<button>`.

### Design & Responsive (CSS3) ?
- **Mise en page** : CSS Grid.
- **Responsive** : Media Queries (`@media`) pour garantir la lisibilité et l'absence de débordement horizontal.
- **Interactions** : Gestion soignée des états `:hover` et `:focus-visible` pour l'accessibilité.

---

### L'ordre réaliser ?
- Analyser le brief et identifier les besoins.
- Définir le parcours utilisateur et l'organisation du contenu.
- Réaliser le zoning.
- Concevoir les wireframes.
- Créer les maquettes UI.
- Relier les écrans dans un prototype si nécessaire.
- Recueillir les retours et valider les choix.
- Commencer le développement HTML/CSS.
  
---
### Qu’est-ce que le SEO ?
Le SEO améliore le classement Google grâce aux mots-clés, au SEO on-page (titres, alt, hrefs), off-page (backlinks), à l’infrastructure, à l’UX/UI, au CTR et à Google Search Console. Le pilier technique, contenu et popularité structure cette optimisation.

---
### Quelles sont les positions en CSS et leurs rôles ?
- **Static** : position par défaut.
- **Relative** : déplace l’élément par rapport à sa position initiale.
- **Absolute** : positionne l’élément par rapport au parent positionné.
- **Fixed** : fixe l’élément sur l’écran, même pendant le scroll.
- **Sticky** : fixe l’élément lorsqu’il atteint un seuil de défilement.

---
### Qu’est-ce que CSS Grid et quelles sont ses propriétés principales ?
CSS Grid permet de créer une mise en page en lignes et en colonnes.

- **Display** : grid; : active Grid.
- **Grid-template-columns** : repeat(3, 1fr); : crée 3 colonnes égales.
- **Grid-template-rows** : repeat(2, 100px); : crée 2 lignes de 100 px.
- **Gap** : 10px; : ajoute un espace entre les éléments.
- **Justify-items** : center; : centre les éléments horizontalement dans leurs cellules.
- **Align-items** : center; : centre les éléments verticalement dans leurs cellules.
- **Place-items** : center; : centre les éléments horizontalement et verticalement.
- **Grid-column** : span 2; : fait occuper 2 colonnes à un élément.
- **Grid-row** : span 2; : fait occuper 2 lignes à un élément.
