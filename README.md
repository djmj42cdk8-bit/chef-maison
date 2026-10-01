# Chef Maison v0.1 — PWA

## Lancer localement
Node.js 18+ : `npm install`, puis `npm run dev`.

## Construire
`npm run build` produit `dist/`, déployable sur un hébergeur statique HTTPS.

## Déjà fonctionnel
Interface responsive, installation PWA, capture/choix d'image, édition locale des ingrédients, suggestions par correspondance, recettes, lien YouTube, défis et XP stockés sur l'appareil.

## Non encore connecté
La photo n'est pas analysée par IA. Il faut un backend sécurisé (clé API côté serveur), un moteur de recettes plus riche, comptes/synchronisation et tests. La publication iOS/Android nécessitera ensuite un client mobile (par exemple Expo) partageant le backend. Ce zip est le socle PWA, pas une publication store.
