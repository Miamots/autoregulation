# Autorégulation au quotidien

Outil web qui accompagne la formation « Soutenir le développement de l'autorégulation en tenant compte des particularités sensorielles », de Virginie Clavel et Valérie Ferron, ergothérapeutes.

## Contenu

- `index.html` : l'application complète (une seule page).
- `img/` : les images utilisées par l'application.
- `manifest.webmanifest`, `sw.js` et `icons/` : permettent d'installer l'app sur un téléphone et de l'utiliser hors ligne.
- `.nojekyll` : indique à GitHub Pages de servir les fichiers tels quels.

## Installer sur un téléphone

- **Android (Chrome) :** ouvrir l'adresse du site, puis menu ⋮ › **Installer l'application** (ou **Ajouter à l'écran d'accueil**).
- **iPhone (Safari) :** ouvrir l'adresse du site, toucher le bouton Partager, puis **Sur l'écran d'accueil**.

## Mettre à jour l'app

Remplacez les fichiers modifiés dans le dépôt. Si vous changez des images, changez aussi le numéro `autoreg-v1` en haut de `sw.js` (par exemple `autoreg-v2`) pour que les téléphones téléchargent la nouvelle version.

## Mettre en ligne avec GitHub Pages

1. Créez un nouveau dépôt sur GitHub (par exemple `autoregulation`).
2. Cliquez sur **Add file › Upload files** et glissez-y tout le contenu de ce dossier (fichiers et dossiers `img` et `icons`).
3. Cliquez sur **Commit changes**.
4. Allez dans **Settings › Pages**. Sous **Branch**, choisissez `main` et `/ (root)`, puis **Save**.
5. Après une ou deux minutes, l'adresse du site s'affiche en haut de la page (par exemple `https://votre-nom.github.io/autoregulation/`).

## Données

Tout ce que les personnes écrivent (idées gardées, notes, fiches) reste dans leur propre navigateur. Rien n'est envoyé à un serveur. Changer d'appareil ou vider l'historique efface ces données : téléchargez vos PDF.

L'outil a besoin d'Internet pour charger les polices (Google Fonts) et la bibliothèque de PDF (jsPDF, cdnjs).

© Virginie Clavel et Valérie Ferron, ergothérapeutes. Tous droits réservés.
