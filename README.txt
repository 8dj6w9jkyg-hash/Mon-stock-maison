MON STOCK MAISON — INSTALLATION SANS ORDINATEUR

Cette version est une application web installable (PWA). Pour qu'elle puisse être ajoutée proprement à l'écran d'accueil et fonctionner hors ligne, les fichiers doivent être publiés sur une adresse HTTPS. Le plus simple et gratuit est GitHub Pages.

1. Sur l'iPhone, ouvrez Safari et allez sur https://github.com/ puis créez un compte ou connectez-vous.
2. Créez un nouveau dépôt (repository) public nommé exactement : mon-stock-maison
3. Dans le dépôt, choisissez Add file > Upload files et téléversez TOUS les fichiers de ce dossier, y compris index.html, manifest.json, sw.js, icon-192.png et icon-512.png. Validez avec Commit changes.
4. Dans le dépôt : Settings > Pages. Dans « Build and deployment », choisissez « Deploy from a branch », branche « main » et dossier « / (root) », puis Save.
5. Attendez quelques minutes. L'adresse sera normalement https://VOTRE-NOM.github.io/mon-stock-maison/
6. Ouvrez cette adresse dans Safari sur l'iPhone. Appuyez sur le bouton Partager (carré avec flèche vers le haut), puis « Sur l'écran d'accueil », puis « Ajouter ».
7. Lancez « Mon Stock » depuis son icône.

UTILISATION
- Ajoutez vos produits, emplacements, quantités et dates.
- Dans « Sauvegarde », choisissez « Exporter une sauvegarde ».
- Enregistrez le fichier JSON dans Fichiers > iCloud Drive.
- Pour transférer vers un autre iPhone, installez/ouvrez l'application, allez dans Sauvegarde et sélectionnez ce fichier pour le restaurer.

IMPORTANT — SAUVEGARDE
Les données de l'inventaire sont enregistrées dans le stockage local du navigateur de cet iPhone. Elles ne sont PAS synchronisées automatiquement avec iCloud. Exportez régulièrement une sauvegarde JSON vers iCloud Drive. Avant de supprimer Safari, effacer ses données ou changer d'appareil, vérifiez que le fichier de sauvegarde existe dans iCloud Drive.

CONFIDENTIALITÉ
Le code fourni n'envoie pas l'inventaire à un serveur. Si vous choisissez un dépôt GitHub public, seuls les fichiers de l'application (le code) sont publics — pas les produits saisis, qui restent sur votre appareil.
