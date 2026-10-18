# 🏫 BKA School Platform

![Status](https://img.shields.io/badge/Status-En_Développement_Actif-success?style=for-the-badge)
![Laravel](https://img.shields.io/badge/Laravel-11.x-FF2D20?style=for-the-badge&logo=laravel)
![PHP](https://img.shields.io/badge/PHP-8.3-777BB4?style=for-the-badge&logo=php)
![Tailwind](https://img.shields.io/badge/Tailwind_CSS-3.x-06B6D4?style=for-the-badge&logo=tailwindcss)

> **Système de Gestion Scolaire Complet** développé pour le **Complexe Scolaire BKA** à Kolwezi, République Démocratique du Congo. Une application web moderne conçue pour digitaliser, sécuriser et fluidifier l'ensemble du processus administratif et pédagogique d'un établissement scolaire.

---

## 📸 Aperçu du Projet

*(💡 Astuce : Remplace ces liens par de vraies captures d'écran de ton application pour un impact visuel maximal !)*

<div align="center">
  <img src="https://via.placeholder.com/800x400/0f172a/D4AF37?text=Tableau+de+Bord+Administratif" alt="Tableau de bord" width="100%" />
  <p><em>Tableau de bord administratif avec statistiques en temps réel et gestion des admissions</em></p>
  
  <img src="https://via.placeholder.com/800x400/0f172a/D4AF37?text=Formulaire+d'Inscription+Public" alt="Formulaire d'inscription" width="100%" />
  <p><em>Formulaire d'inscription public moderne et responsive</em></p>
</div>

---

## ✨ Fonctionnalités Clés

### 📝 Pipeline d'Admission Dynamique
- **Formulaire Public** : Inscription en ligne avec validation stricte des données.
- **Suivi par Code Unique** : Génération automatique d'un code de suivi à 8 caractères pour les parents.
- **Traitement Administratif** : Approbation, refus (avec motif) et conversion automatique en élève.
- **Corbeille Intelligente** : Suppression douce (soft delete) avec possibilité de restauration ou suppression définitive.

### 📊 Tableau de Bord Administratif (Ultra-Pro)
- **Statistiques en Temps Réel (KPI)** : Total, en attente, approuvées, refusées.
- **Recherche & Filtres Avancés** : Filtrage instantané par nom, référence, téléphone ou statut.
- **Modal de Détail** : Consultation rapide du dossier complet sans quitter la page.

### ⚙️ Gestion des Paramètres en Temps Réel
- Ouverture et fermeture des inscriptions en un clic (sans modifier le code).
- Gestion des dates limites et du nombre de places disponibles.

### 🛡️ Sécurité & Robustesse
- Protection CSRF et validation des formulaires côté serveur.
- Génération infaillible de références uniques (gestion des conflits et éléments supprimés).
- Architecture MVC propre et respect des standards Laravel.

---

## 🛠️ Stack Technique

| Catégorie | Technologies |
|-----------|--------------|
| **Backend** | PHP 8.3, Laravel 11.x |
| **Frontend** | Blade Templates, Tailwind CSS, JavaScript (Vanilla), Font Awesome |
| **Base de Données** | MySQL / SQLite |
| **Outils de Dev** | Git, GitHub, Composer, Artisan CLI, Laragon/XAMPP |

---

## 🚀 Installation et Démarrage Local

Suivez ces étapes pour cloner et exécuter le projet sur votre machine locale :

### 1. Prérequis
- PHP >= 8.1
- Composer
- MySQL ou SQLite
- Node.js & NPM (pour la compilation des assets si nécessaire)

### 2. Cloner le dépôt
```bash
git clone https://github.com/bkatech123/bka-school-platform.git
cd bka-school-platform
