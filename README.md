# MC Peinture — site vitrine one-page (démo prospection)

Page unique de démonstration pour **MC Peinture**, entreprise de peinture à Nieul-sur-Mer (17), conçue pour la prospection. Objectif : un site **simple à maintenir** mais **fortement optimisé pour le référencement local** (« peintre Nieul-sur-Mer », « peintre La Rochelle »).

## ⚡ Points forts

- **Léger & sans build** : un seul fichier `index.html`, sans framework ni dépendance. Police système, icônes/cartes en SVG intégré. Les photos sont des images **libres de droits (licence Unsplash, usage commercial autorisé)** servies via CDN optimisé (redimensionnement automatique, `loading="lazy"`, `fetchpriority` sur le hero) → bons Core Web Vitals / Lighthouse.
- **Responsive mobile-first** + barre d'action fixe (Appeler / Devis) sur mobile, là où se font 3 recherches sur 4.
- **SEO on-page** : `<title>` et meta description géolocalisés, H1/H2 avec « Nieul-sur-Mer » et « La Rochelle », alt text descriptifs, canonical, Open Graph.
- **Données structurées Schema.org** (JSON-LD) : `HousePainter` (LocalBusiness) avec adresse, géo, horaires, zone desservie, prestations ; `FAQPage` (éligible aux résultats enrichis) ; `BreadcrumbList`.
- **SEO local** : bloc zone d'intervention listant les communes de l'agglo, NAP cohérent (nom / adresse / téléphone), section avis.
- **Conversion** : hero avec proposition de valeur claire, CTA « Devis gratuit sous 24h » répétés, formulaire qualifié (type de projet, code postal), preuves de confiance (décennale, SIRET, avis).
- **Accessibilité** : lien d'évitement, focus visibles, contrastes, `aria-*`, `prefers-reduced-motion`.

## 🔧 À personnaliser avant mise en ligne

Ces éléments sont des **placeholders de démonstration** :

1. **Téléphone** — remplacer `06 XX XX XX XX` et `+33600000000` (attributs `tel:`, header, footer, JSON-LD, barre mobile).
2. **Email** — remplacer `contact@mc-peinture-nieul.fr`.
3. **Nom de domaine** — remplacer `https://www.mc-peinture-nieul.fr/` (canonical, Open Graph, sitemap, robots, JSON-LD).
4. **Photos de chantiers** — les photos actuelles sont des images de stock libres de droits (Unsplash). Les remplacer par **vos vraies photos de chantiers** (avant/après), idéalement auto-hébergées dans un dossier `/img` pour la performance et l'authenticité. C'est le principal levier de conversion.
5. **Avis** — remplacer par de **vrais** avis Google. ⚠️ Ne jamais publier de faux avis ni de faux `aggregateRating` (sanctions Google) : la note 4,9/5 et les 27 avis du JSON-LD sont des exemples.
6. **Horaires** — vérifier les horaires réels.
7. **Mentions légales / RGPD** — créer les pages ou remplacer par le contenu réel.
8. **Formulaire** — le formulaire est en démo (aucun backend). Le brancher sur un service (Formspree, Netlify Forms, e-mail, CRM…) pour recevoir les leads.
9. **Carte** — la carte est une carte interactive **OpenStreetMap** (sans clé API, gratuite) centrée sur Nieul-sur-Mer, avec un lien « Itinéraire » vers Google Maps. Une fois la **fiche Google Business Profile** créée, tu peux la remplacer par la carte Google intégrée de la fiche pour renforcer le lien avec le SEO local.

## 🚀 Mise en ligne rapide (GitHub Pages)

`Settings` → `Pages` → Source : branche `main`, dossier `/root`. Le site sera servi sur `https://<user>.github.io/mcpeinture/`. Pour un vrai référencement, brancher ensuite un nom de domaine et créer/optimiser la **fiche Google Business Profile** (levier n°1 du SEO local).

## 📈 Après la mise en ligne (checklist SEO local)

- Créer et compléter à 100 % la fiche **Google Business Profile** (catégorie « Peintre »), ajouter des photos régulièrement.
- Assurer la cohérence **NAP** sur le site, GBP et les annuaires (PagesJaunes, etc.).
- Collecter des avis (viser 20–30 avis, 4,5+/5) et y répondre.
- Soumettre le `sitemap.xml` dans Google Search Console.

---
*Données société : SARL MC Peinture, gérante Christelle Moquay, 4 Rue du Four à Chaux, 17137 Nieul-sur-Mer, SIRET 535 265 367 00024, APE 4334Z. Site de démonstration réalisé à des fins de prospection commerciale.*
