# ✅ To-Do App with Next.js, Drizzle & Clerk

Cette application est une to-do list moderne construite avec :

- ✅ Next.js (App Router)
- ✅ TypeScript
- ✅ Drizzle ORM
- ✅ Clerk (authentification)
- ✅ Tailwind CSS

---

## ✨ Fonctionnalités

- Authentification sécurisée avec Clerk
- Ajout, modification et suppression de tâches
- Sauvegarde persistante avec Drizzle + SQLite
- Interface responsive et moderne

---

## 📁 Structure du projet

to-do-main/
├── app/ # Routes (App Router)
│ ├── dashboard/ # Interface de l'utilisateur connecté
│ └── api/ # Routes API (GET, POST)
├── components/ # Composants réutilisables (input, bouton, etc.)
├── db/ # Config Drizzle et base SQLite
├── migrations/ # Migrations de base de données
├── public/ # Fichiers statiques
├── styles/ # Styles globaux (tailwind.css)
├── .env # Variables d'environnement
├── drizzle.config.ts # Config Drizzle ORM
├── middleware.ts # Middleware Clerk
├── package.json
└── tsconfig.json
