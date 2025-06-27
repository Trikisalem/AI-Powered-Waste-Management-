# ♻️ AI-Powered Waste Management Platform

Une plateforme intelligente de gestion des déchets combinant **Next.js 14**, **IA (Gemini AI)**, **authentification Web3**, **base de données Neon avec Drizzle ORM**, et **interface responsive avec Tailwind CSS**. Ce projet Full Stack a pour objectif de favoriser des comportements éco-responsables grâce à un système de récompenses, de gestion en temps réel des collectes, et une communauté interactive.

---

## 🚀 Fonctionnalités principales

- ✅ **Vérification des déchets par IA** (Google Gemini)
- 🪙 **Système de récompenses** pour les utilisateurs éco-responsables
- 📦 **Gestion des tâches de collecte en temps réel**
- 🏆 **Classement interactif** pour encourager l'engagement communautaire
- 🛡️ **Authentification sécurisée avec Web3Auth**
- 📊 **Design responsive** pour tous les appareils

---

## 📚 Technologies utilisées

| Domaine                        | Technologie                          |
|-------------------------------|--------------------------------------|
| Frontend                      | [Next.js 14](https://nextjs.org/)   |
| Langage                       | TypeScript                           |
| UI Design                     | [Tailwind CSS](https://tailwindcss.com/) |
| Authentification              | [Web3Auth](https://web3auth.io/)     |
| Base de données               | [Neon](https://neon.tech/) + [Drizzle ORM](https://orm.drizzle.team/) |
| Intelligence Artificielle     | [Google Gemini AI](https://ai.google.dev/) |

---

## 👨‍💻 Guide Étape par Étape

### 1. ⚙️ Initialisation du projet

```bash
npx create-next-app@latest waste-management-ai --typescript
cd waste-management-ai
2. 🎨 Intégration de Tailwind CSS
bash
Copier
Modifier
npm install -D tailwindcss postcss autoprefixer
npx tailwindcss init -p
Configurer tailwind.config.ts et ajouter les styles globaux dans globals.css.

3. 🔐 Authentification avec Web3Auth
bash
Copier
Modifier
npm install --save @web3auth/modal
Implémenter dans _app.tsx avec les clés Web3Auth.

4. 🧠 Intégration de Google Gemini AI
Utiliser les API de Gemini pour analyser des images/textes envoyés par les utilisateurs et vérifier la conformité des déchets.

5. 🧩 Intégration de la base de données avec Drizzle ORM
bash
Copier
Modifier
npm install drizzle-orm
Configurer les schémas et connecter la base de données Neon.

6. 📲 Développement de composants interactifs
🧾 Dashboard utilisateur

🏆 Leaderboard communautaire

🚛 Suivi des collectes

🎁 Système de récompenses dynamiques
![Aperçu 1](https://raw.githubusercontent.com/Trikisalem/AI-Powered-Waste-Management-/main/1.png)



