# KY Radio TV – v1.1

Application Android TV pour NVIDIA SHIELD. Elle ouvre directement :

`https://keyyou.ddns.net`

## Caractéristiques
- Android TV / SHIELD
- Application visible dans le lanceur TV
- Icône KY Radio personnalisée
- Affichage plein écran
- JavaScript, DOM Storage et lecture média activés
- Navigation Retour avec l’historique Web
- User-Agent identifié `KYRadioTV/1.1`

## Compilation
Ouvrir le dossier `KYRadioTV` avec Android Studio, puis **Build > Build APK(s)**.

APK debug généré : `app/build/outputs/apk/debug/app-debug.apk`

Le workflow GitHub Actions `.github/workflows/build.yml` peut également compiler automatiquement l’APK.

## Installation sur la SHIELD
1. Transférer `app-debug.apk` sur la SHIELD.
2. Autoriser l’installation depuis cette source si Android le demande.
3. Installer l’APK.
4. Lancer **KY Radio**.
5. Depuis l’écran d’accueil, maintenir **Select/OK** sur KY Radio pour la placer dans les favoris.

## Important
La SHIELD doit pouvoir accéder à `https://keyyou.ddns.net` et valider son certificat HTTPS.
