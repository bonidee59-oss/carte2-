# CartesID BF

Application web hors ligne (PWA) de création de cartes d'identité scolaires et de documents professionnels — Burkina Faso. Inclut le module **préscolaire (CEEP)** : sections Petite / Moyenne / Grande section, cartes enfants recto-verso, modèles « Éveil ».

## Publier avec GitHub Pages

1. Créez un dépôt sur GitHub et envoyez-y tout le contenu de ce dossier (`index.html` doit être à la racine du dépôt).
2. Dans le dépôt : **Settings → Pages**.
3. **Source** : « Deploy from a branch », branche `main`, dossier `/ (root)`, puis **Save**.
4. Après 1 à 2 minutes, l'application est disponible à `https://<utilisateur>.github.io/<depot>/`.

Ouvrez le site une première fois avec une connexion : l'application se met ensuite en cache et fonctionne hors ligne.

## Mise à jour

Remplacez les fichiers dans le dépôt. Pour que les appareils déjà installés se mettent à jour, changez le numéro `CACHE_NAME` (ex. `cartesid-bf-v21`) dans `sw.js`.

Les données restent dans le navigateur de chaque appareil (aucun serveur).
