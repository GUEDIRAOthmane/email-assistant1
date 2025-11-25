# 🚀 Assistant Email Professionnel - Déploiement Groq (100% GRATUIT)

## ✅ TOUT EST PRÊT - SUIS CES ÉTAPES

---

## 📋 ÉTAPE 1 : Obtenir une clé API Groq (GRATUIT)

1. Va sur **https://console.groq.com/**
2. Crée un compte (email suffit)
3. Une fois connecté, clique sur **"API Keys"**
4. Clique sur **"Create API Key"**
5. Nom : `Email Assistant`
6. **COPIE la clé** (commence par `gsk_...`)
7. **Sauvegarde-la** dans un fichier texte

💡 **100% GRATUIT - Aucun paiement requis !**

---

## 🌐 ÉTAPE 2 : Créer un compte Vercel (GRATUIT)

1. Va sur **https://vercel.com/signup**
2. Inscris-toi avec **GitHub**
3. Si tu n'as pas GitHub, crée un compte sur **https://github.com/signup**
4. **Aucune carte bancaire demandée** ✅

---

## 📤 ÉTAPE 3 : Créer un repository GitHub

1. Connecte-toi sur **https://github.com/**
2. Clique sur le **"+"** en haut à droite
3. Sélectionne **"New repository"**
4. **Nom** : `email-assistant`
5. Choisis **Public** ou **Private** (au choix)
6. ❌ **NE coche PAS** "Add a README file"
7. Clique **"Create repository"**

---

## 📁 ÉTAPE 4 : Upload les fichiers sur GitHub

Sur la page de ton nouveau repository :

1. Clique **"uploading an existing file"**
2. **Drag & drop** TOUS les fichiers de ce dossier :
   - `index.html`
   - `package.json`
   - `vercel.json`
   - Le dossier `api/` avec `generate.js` dedans

**IMPORTANT** : Assure-toi que la structure est :
```
email-assistant/
├── api/
│   └── generate.js
├── index.html
├── package.json
└── vercel.json
```

3. Clique **"Commit changes"**

---

## 🚀 ÉTAPE 5 : Déployer sur Vercel

1. Retourne sur **https://vercel.com/**
2. Clique sur **"Add New..."** → **"Project"**
3. Sélectionne **"Import Git Repository"**
4. Choisis ton repository **`email-assistant`**
5. Clique **"Import"**

6. **Configure la clé API** :
   - Dans **"Environment Variables"**
   - **Name** : `GROQ_API_KEY`
   - **Value** : Colle ta clé Groq (celle qui commence par `gsk_...`)
   - Clique **"Add"**

7. Clique **"Deploy"**
8. Attends 30-60 secondes...
9. 🎉 **C'EST EN LIGNE !**

---

## 🎯 ÉTAPE 6 : Utiliser ton assistant

Vercel te donne une URL : `https://email-assistant-xxx.vercel.app`

**Ouvre cette URL** et profite de ton assistant email ! 🚀

---

## ✨ Fonctionnalités

- ✅ Correction orthographique et grammaticale
- ✅ Amélioration du ton (professionnel, amical, décontracté)
- ✅ Traduction (français, anglais, auto-détection)
- ✅ Vouvoiement / Tutoiement
- ✅ Longueur détaillée ou courte
- ✅ 100% GRATUIT avec Groq
- ✅ Design bleu et rouge

---

## ❓ Problèmes courants

**❌ Erreur 404**
→ Vérifie que `index.html` est bien à la racine du repository
→ Vérifie que le dossier `api/` contient `generate.js`

**❌ "API key not configured"**
→ Va dans Vercel → Settings → Environment Variables
→ Vérifie que `GROQ_API_KEY` est bien configurée
→ Redéploie le projet (Deployments → ... → Redeploy)

**❌ "Erreur lors de la génération"**
→ Vérifie que ta clé Groq est valide sur https://console.groq.com/keys

---

## 🎉 Félicitations !

Tu as maintenant ton propre assistant email professionnel accessible partout !

**Partage ton URL avec tes collègues** et profite de l'outil ! 🚀

---

## 💡 Conseils

- Sauvegarde ton URL quelque part
- Ajoute-la à tes favoris
- Partage-la avec ton équipe
- L'outil est accessible 24/7 gratuitement

---

**Bon courage et profite bien !** 😊