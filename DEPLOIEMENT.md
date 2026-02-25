# 🚀 GUIDE DE DÉPLOIEMENT VERCEL

## Étape 1 : Créer un compte Vercel (GRATUIT)

1. Allez sur https://vercel.com
2. Cliquez sur "Sign Up"
3. Connectez-vous avec votre compte GitHub (recommandé)

---

## Étape 2 : Créer un repository GitHub

### Option A : Depuis le dossier local

1. Allez sur https://github.com/new
2. Créez un nouveau repository : `rhabelais-gepp`
3. Ne cochez rien (pas de README, pas de .gitignore)
4. Cliquez "Create repository"

5. Dans votre terminal (dans le dossier du projet) :

```bash
cd rhabelais-gepp-deploy
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/VOTRE-USERNAME/rhabelais-gepp.git
git push -u origin main
```

### Option B : Upload manuel

1. Créez le repository sur GitHub
2. Cliquez sur "uploading an existing file"
3. Glissez-déposez tous les fichiers du dossier `rhabelais-gepp-deploy`
4. Commit

---

## Étape 3 : Déployer sur Vercel

1. Connectez-vous sur https://vercel.com
2. Cliquez sur "Add New" → "Project"
3. Importez votre repository GitHub `rhabelais-gepp`
4. Vercel détecte automatiquement les fichiers HTML
5. Cliquez sur "Deploy"

⏳ **Déploiement en cours... (30-60 secondes)**

---

## Étape 4 : Votre app est en ligne ! 🎉

URL : `https://rhabelais-gepp.vercel.app`

(ou `votre-nom-projet.vercel.app`)

---

## Étape 5 : Tester l'application

1. Ouvrez l'URL de votre app
2. Cliquez sur "Ouvrir l'application"
3. Connectez-vous avec :
   - Email : contact@rhabelais.fr
   - Mot de passe : Test1234!

---

## 🎯 Personnaliser le domaine (Optionnel)

### Option A : Utiliser un domaine Vercel gratuit

Dans Vercel :
1. Settings → Domains
2. Changez `rhabelais-gepp` en `votre-nom`
3. Nouveau domaine : `votre-nom.vercel.app`

### Option B : Utiliser votre propre domaine

Dans Vercel :
1. Settings → Domains
2. Add : `gepp.votre-entreprise.com`
3. Configurez les DNS selon les instructions

---

## 🔄 Mettre à jour l'application

### Méthode simple (via GitHub)

1. Modifiez les fichiers sur GitHub
2. Commit
3. Vercel redéploie automatiquement ! ✨

### Méthode développeur

```bash
git add .
git commit -m "Mise à jour"
git push
```

Vercel redéploie automatiquement en 30 secondes.

---

## 📊 Surveiller les déploiements

Dans Vercel :
- Onglet "Deployments" : voir l'historique
- Onglet "Analytics" : voir les visites
- Onglet "Logs" : voir les erreurs

---

## ⚠️ Points de vigilance

### ✅ À FAIRE après le premier déploiement :

1. **Changer le mot de passe admin** dans Supabase
2. **Configurer SMTP** pour "mot de passe oublié"
3. **Vérifier que l'URL Supabase** est bien la vôtre dans app.html

### ❌ NE PAS FAIRE :

- Partager vos clés Supabase publiquement
- Laisser le mot de passe par défaut en production
- Ignorer les mises à jour de sécurité

---

## 🆘 Problèmes courants

### "Database error"
→ Vérifiez que RLS est désactivé sur toutes les tables Supabase

### "Failed to fetch"
→ Vérifiez l'URL et la clé Supabase dans app.html

### "Page not found"
→ Vérifiez que tous les fichiers sont dans le repo GitHub

---

## 🎉 C'EST TERMINÉ !

Votre application est maintenant :
- ✅ En ligne 24/7
- ✅ Accessible de partout
- ✅ Sécurisée (HTTPS)
- ✅ Mise à jour automatique
- ✅ GRATUITE (jusqu'à 100GB de bande passante/mois)

**URL de démo :** https://rhabelais-gepp.vercel.app
