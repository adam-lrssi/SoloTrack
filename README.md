# 🚀 SoloTrack


> **"Libérez votre talent, SoloTrack s’occupe du reste."**

**SoloTrack** est une application web (SAAS) conçue pour aider les freelances à transformer le chaos administratif en clarté financière. Elle permet de centraliser la gestion des clients, des missions et de la facturation au sein d'une interface "Dark Mode" premium et fluide.

---

## 🌟 Fonctionnalités Clés

* **📊 Tableau de Bord Intelligent :** Visualisation en temps réel du chiffre d'affaires, des missions en cours et de la croissance (+40h de productivité gagnée/mois).
* **🤝 Gestion Clients (CRM) :** Carnet d'adresses centralisé et sécurisé.
* **⚡ Suivi de Missions :** Tracking des projets, des dates et des tarifs journaliers.
* **📄 Facturation Automatisée :** Génération de factures PDF conformes et suivi des statuts (Payée, En attente, Retard).
* **🎨 UI/UX Premium :** Une interface moderne en "Dark Mode" avec effets Glassmorphism et Néon pour un confort visuel optimal.

---

## 🛠️ Stack Technique

Ce projet utilise une architecture **Fullstack Javascript** (PERN Stack adaptée MySQL) :

### 🎨 Frontend
* ![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB) **React.js (Vite)**
* ![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white) **Tailwind CSS**
* ![Framer Motion](https://img.shields.io/badge/Framer_Motion-0055FF?style=for-the-badge&logo=framer&logoColor=white) **Framer Motion (Animations)**

### ⚙️ Backend & Data
* ![NodeJS](https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white) **Node.js**
* ![Express.js](https://img.shields.io/badge/Express.js-404D59?style=for-the-badge) **Express.js (API REST)**
* ![MySQL](https://img.shields.io/badge/MySQL-00000F?style=for-the-badge&logo=mysql&logoColor=white) **MySQL (Base de données Relationnelle)**

---

## 📂 Structure de la Base de Données

L'application repose sur une structure SQL robuste garantissant l'intégrité des données :

| Table | Description |
| :--- | :--- |
| **`Utilisateur`** | Gère les profils freelances, logins et infos légales (SIRET). |
| **`Client`** | Répertoire des entreprises clientes liées à un utilisateur. |
| **`Mission`** | Détails des prestations, dates de début/fin, TJM. |
| **`Facture`** | Liée aux missions, calcul automatique HT/TTC et statuts. |

---

