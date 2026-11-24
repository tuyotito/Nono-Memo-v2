# Nono Memo — application Android hors ligne

Jeux de mémoire pour tablette et téléphone Android. L'application est **100 % autonome** : aucune connexion internet, aucune permission.

Le jeu se trouve dans `app/src/main/assets/index.html`.

## Obtenir l'APK (sans rien installer)
1. Déposez tous les fichiers de ce dossier dans un dépôt GitHub (y compris le dossier caché `.github`).
2. Ouvrez l'onglet **Actions** > **Build APK** > **Run workflow** (il se lance aussi à chaque dépôt de fichiers).
3. Attendez environ 3 minutes, ouvrez l'exécution terminée, puis téléchargez **NonoMemo-apk** en bas de page (zip contenant `app-debug.apk`).
4. Copiez l'APK sur l'appareil, ouvrez-le et autorisez les « sources inconnues » si Android le demande.

## Avec Android Studio
Ouvrir ce dossier, attendre la synchronisation, puis **Build > Build APK(s)**.
