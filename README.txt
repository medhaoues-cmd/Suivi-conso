SUIVI HYBRIDE v2

Fonctions :
- Lecture OCR du kilométrage depuis une photo du tableau de bord.
- Saisie manuelle de secours si la photo n'est pas lisible.
- Saisie manuelle des kWh rechargés et des litres ravitaillés.
- Calcul des kWh/100 km, L/100 km et du coût aux 100 km.
- Historique local, export CSV pour Excel, sauvegarde/restauration JSON.
- Application web installable sur iPhone après hébergement HTTPS.

Installation iPhone :
1. Publier tous les fichiers sur un hébergement HTTPS.
2. Ouvrir le site dans Safari.
3. Partager > Sur l'écran d'accueil > Ajouter.

Important :
- La reconnaissance OCR utilise Tesseract.js depuis un CDN, donc une connexion Internet est nécessaire pour charger le moteur lors de son premier usage. La reconnaissance peut se tromper selon la photo, vérifiez le kilométrage proposé.
- L'historique est conservé localement sur l'appareil et le navigateur. Exportez régulièrement une sauvegarde JSON.
- Les kWh et litres saisis sont des quantités ajoutées, pas forcément la consommation réelle sur cette période. Pour de meilleurs résultats, comparez des niveaux de batterie et de réservoir similaires.
