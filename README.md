# Sable & Soleil — Boutique COD

Boutique multi-produits avec paiement à la livraison pour l'Algérie.

## Structure

- `index.html` — page d'accueil (grille de produits)
- `content.js` — TOUT le contenu du site, un seul fichier à éditer
- `thank-you.html` — page de remerciement après commande
- `track.html` — page de suivi de commande par numéro de téléphone
- `fonts/` — polices (Inter)
- `products/` — une page par produit, chacune indépendante
- `TEMPLATE/` — dossier à copier pour ajouter un nouveau produit

## Pour éditer le contenu

**Un seul fichier : `content.js`**

Tout ce qui concerne vos produits, prix, remises, livraison, FAQ, avis, contact
est dans ce fichier. Les instructions en français sont à côté de chaque champ.

## Pour ajouter un produit

1. Copiez le dossier `TEMPLATE/`
2. Renommez-le avec le nom de votre produit (minuscules, tirets)
3. Placez-le dans `products/`
4. Éditez `content.js` pour ajouter le produit
5. Ajoutez les photos dans `products/votre-produit/images/`
6. Ajoutez le produit à la liste dans la page d'accueil (`content.js`)

## Pour ajouter des photos

Chaque produit a besoin de :
- 7 photos pour le carrousel : `slide-1.jpg` à `slide-7.jpg`
- 2 photos détail : `detail-1.jpg`, `detail-2.jpg`
- 1 photo de tuile pour la page d'accueil : `tile.jpg`

Total : 10 images par produit.

## Backend (Google Apps Script)

Le fichier `order-receiver.gs` **n'est pas dans ce repo**.
Il se trouve dans Google Apps Script, lié à votre Google Sheet.

## Déploiement

Ce site est déployé sur Cloudflare Pages. Chaque push sur GitHub
déclenche un redéploiement automatique.

## Support

Contact : contact@sable-soleil.dz
