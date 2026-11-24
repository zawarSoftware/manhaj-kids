# Site statique Manhaj Kids

Ce dossier contient les pages web exigées par Google Play et l'App Store : accueil, politique de confidentialité (`confidentialite/`) et suppression de compte (`supprimer-mon-compte/`). HTML et CSS seulement, aucune ressource externe.

## Publier

- **Netlify Drop** : glisser le dossier `site/` sur app.netlify.com/drop.
- **Cloudflare Pages** : créer un projet, envoyer le dossier `site/` (upload direct).
- **GitHub Pages** : depuis un dépôt public contenant ce dossier.

## Après publication

Remplacer `[SITE]` dans `docs/privacy_policy_fr.md` (encadré du haut et section 8) par l'URL de la page de suppression, par exemple `https://…/supprimer-mon-compte/`. Renseigner aussi les URL de la politique et de la suppression dans les consoles Play et App Store.

## Maintenance

La politique existe en deux exemplaires : `docs/privacy_policy_fr.md` et `site/confidentialite/index.html`. Toute modification se reporte dans les deux, avec la date de mise à jour.
