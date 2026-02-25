# Rhabelais GEPP

**Gestion Électronique des Parcours Professionnels**

Application web de gestion des compétences pour les entreprises.

## 🚀 Fonctionnalités

- ✅ Gestion des postes et compétences
- ✅ Évaluation des collaborateurs
- ✅ Hiérarchie manager (N+2, N+1, N)
- ✅ Identification des écarts de compétences
- ✅ Exports Excel
- ✅ Interface Admin RH et Manager
- ✅ Authentification sécurisée

## 🛠️ Technologies

- **Frontend :** HTML, JavaScript, Tailwind CSS
- **Backend :** Supabase (PostgreSQL)
- **Hébergement :** Vercel

## 📦 Déploiement

### Déploiement sur Vercel

1. Fork ce repository
2. Connectez votre compte Vercel
3. Importez le projet
4. Déployez !

L'application sera accessible sur : `votre-projet.vercel.app`

## 🔧 Configuration

### Configuration Supabase

L'application nécessite un projet Supabase configuré avec :

1. **Base de données** avec les tables :
   - `entreprises`
   - `profils`
   - `metiers`
   - `competences`
   - `niveaux_attendus`
   - `collaborateurs`
   - `evaluations_competences`

2. **Authentification** activée

3. **RLS (Row Level Security)** désactivé pour simplifier (ou configuré selon vos besoins)

### Connexion par défaut

- **Email :** contact@rhabelais.fr
- **Mot de passe :** Test1234!

⚠️ Changez ces identifiants après le premier déploiement !

## 📚 Documentation

Consultez la page `/docs.html` pour le guide d'utilisation complet.

## 🔐 Sécurité

- Authentification via Supabase Auth
- Gestion des rôles (Admin RH / Manager)
- HTTPS automatique via Vercel
- Mots de passe chiffrés

## 📄 Licence

© 2026 Rhabelais - Tous droits réservés

## 🤝 Support

Pour toute question ou assistance, contactez le support Rhabelais.
