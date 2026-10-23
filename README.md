# 🚀 Connecteo Hub - Espace de Gestion

Bienvenue sur le dépôt officiel du **Connecteo Hub**. Cet outil centralise la gestion opérationnelle à travers trois espaces de travail distincts, chacun disposant de sa propre interface et de son propre univers graphique.

## 📋 Les 3 Modules

L'application est divisée en trois pôles accessibles depuis la page d'accueil (`index.html`) :

1. **VOC (Voice of Customer) - Thème Teal** 
   * *Gestion des enquêtes mystères et de la satisfaction client.*
   * Projets typiques : Études de marché, NPS, audits de conformité.
2. **Training Hub - Thème Violet**
   * *Gestion des formations et des sessions d'apprentissage.*
   * Projets typiques : Ingénierie pédagogique, animation de sessions.
3. **PMO (Project Management Office) - Thème Orange**
   * *Gestion de projet classique et pilotage opérationnel.*
   * Projets typiques : Déploiement ERP, projets IT, lancement de produit.

## ✨ Fonctionnalités Clés (communes aux 3 modules)

Chaque module est une application web autonome offrant les vues suivantes :
*   **Fiche de Cadrage** : Définition du contexte, objectifs, budget, risques et parties prenantes.
*   **Roadmap (Gantt)** : Vue temporelle interactive avec affichage des dates de début/fin par tâche, gestion des jalons et **dépendances visuelles** (flèches).
*   **Kanban** : Vue opérationnelle avec **glisser-déposer** (Drag & Drop) pour faire évoluer le statut des tâches.
*   **Checklist** : Vue liste détaillée pour cocher l'avancement.
*   **Tableau de Bord** : Indicateurs de performance (KPI), progression globale et alertes sur les prochaines échéances.
*   **Mode Présentation** : Un mode "clean" qui masque les boutons d'édition pour présenter la roadmap à un client en toute sécurité.
*   **Export** : Génération de PDF (impression) et d'un fichier JSON de sauvegarde.

## 🛠️ Stack Technique

*   **Frontend** : HTML5, CSS3 (Vanilla), JavaScript (Vanilla - sans framework).
*   **Design** : Glassmorphism, animations CSS, intégration de la charte graphique (Police *Mada*, Logo SVG en Base64).
*   **Stockage (Actuel)** : `localStorage` du navigateur (les données restent sur l'ordinateur local).
*   **Hébergement** : [Vercel](https://vercel.com).
*   **Base de données (À venir)** : [Supabase](https://supabase.com) (PostgreSQL + Authentification).

## 📁 Structure des Fichiers

```text
├── index.html       # Page d'accueil (Hub de sélection des modules)
├── voc.html         # Application Voice of Customer
├── training.html    # Application Training Hub
├── pmo.html         # Application PMO
└── README.md        # Documentation du projet
