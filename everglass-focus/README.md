# EverGlass Focus Journée — PWA

## Ce que c'est
Application web progressive (PWA) — fiche de focus journalière pour les commerciaux EverGlass.
Fonctionne comme une vraie app sur mobile, sans passer par l'App Store.

---

## Déploiement sur Vercel (gratuit, 5 minutes)

### Étape 1 — Créer un compte Vercel
- Va sur https://vercel.com
- Clique "Sign Up"
- Connecte-toi avec GitHub (crée un compte GitHub si t'en as pas)

### Étape 2 — Déposer les fichiers sur GitHub
- Va sur https://github.com/new
- Nomme le repo "everglass-focus"
- Clique "Create repository"
- Glisse les 4 fichiers dedans (index.html, manifest.json, sw.js, et le dossier icons/)

### Étape 3 — Connecter à Vercel
- Dans Vercel, clique "Add New Project"
- Sélectionne ton repo GitHub "everglass-focus"
- Clique "Deploy" — c'est tout

### Étape 4 — Récupérer l'URL
- Vercel te donne une URL du type : https://everglass-focus.vercel.app
- C'est cette URL que tu envoies sur WhatsApp chaque matin

---

## Comment tes commerciaux l'installent (30 secondes)

### Sur iPhone :
1. Ouvrir le lien dans Safari (pas Chrome)
2. Appuyer sur l'icône Partager (carré avec flèche)
3. "Sur l'écran d'accueil"
4. "Ajouter"

### Sur Android :
1. Ouvrir le lien dans Chrome
2. Appuyer sur les 3 points en haut à droite
3. "Ajouter à l'écran d'accueil"
4. "Ajouter"

---

## Ce que l'app fait
- Sauvegarde automatiquement les données de la journée (localStorage)
- Repart à zéro chaque nouveau jour
- Mémorise le nom et la ville du commercial
- Fonctionne hors connexion une fois chargée

---

## Icônes
Tu dois ajouter 2 fichiers dans le dossier icons/ :
- icon-192.png (192x192 px) — logo EverGlass
- icon-512.png (512x512 px) — logo EverGlass

Utilise Canva ou demande à David de les créer.
