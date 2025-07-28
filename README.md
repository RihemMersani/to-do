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

```
to-do-main/
├── app/                # Routes (App Router)
│   ├── dashboard/      # Interface de l'utilisateur connecté
│   └── api/            # Routes API (GET, POST)
├── components/         # Composants réutilisables (input, bouton, etc.)
├── db/                 # Config Drizzle et base SQLite
├── migrations/         # Migrations de base de données
├── public/             # Fichiers statiques
├── styles/             # Styles globaux (tailwind.css)
├── .env                # Variables d'environnement
├── drizzle.config.ts   # Config Drizzle ORM
├── middleware.ts       # Middleware Clerk
├── package.json
└── tsconfig.json
```

---

## ⚙️ Installation

1. **Cloner le dépôt**

```bash
git clone https://github.com/votre-utilisateur/to-do-main.git
cd to-do-main
```

2. **Installer les dépendances**

```bash
npm install
```

3. **Configurer les variables d’environnement**

Crée un fichier `.env` :

```env
DATABASE_URL="file:./dev.db"
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=your_clerk_key
CLERK_SECRET_KEY=your_clerk_secret
```

4. **Lancer les migrations Drizzle**

```bash
npx drizzle-kit push
```

5. **Démarrer le projet en local**

```bash
npm run dev
```

Accède à l'application sur `http://localhost:3000`.

---



## 👩‍💻 Auteur

Projet développé par **Rihem Mersani**  
Contact : rihemmersani05@gmail.com

---

## 📜 Licence

Ce projet est open-source. Utilisation libre à but éducatif.
