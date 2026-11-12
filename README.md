# Carnet du poulailler

Appli web installable (PWA) pour suivre un petit poulailler : ponte, achats d'aliments, ventes et dons d'œufs, statistiques, lots de poules, export Excel.

- Aucune donnée envoyée sur Internet : tout est stocké sur le téléphone (localStorage), avec sauvegarde / restauration en fichier JSON.
- Fonctionne hors connexion (service worker `sw.js`). À chaque nouvelle version, changer `CACHE` dans `sw.js` et `VERSION` dans `index.html`.
- Site statique, sans étape de build : déployé tel quel sur Vercel.
