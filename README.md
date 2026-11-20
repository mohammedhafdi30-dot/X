# 🧬 MIDOOO — Plateforme QCM Concours Médecine

Plateforme web professionnelle de préparation aux concours de médecine, inspirée du design **vermed / Med Concours**, dédiée au module de **Biologie Cellulaire & Génétique Fondamentale** (Faculté de Médecine et de Pharmacie de Casablanca — **Pr. Abdallah BADOU**).

---

## 🌟 Fonctionnalités Clés

### 1. Design & Expérience Utilisateur (Conforme à 100% aux captures vermed)
- **Thème sombre ultra-moderne** : Palette violet/pourpre profond (`#0c0217`, `#14062a`), néon magenta (`#d946ef`), et vert émeraude (`#10b981`).
- **Sidebar interactive** : 
  - Logo **MIDOOO** lumineux avec badge de spécialité.
  - Progression globale en temps réel (`% complété`, `X / 83`).
  - Accordéons repliables pour chaque série (**Série I**, **Série II**, **Série III**).
  - Navigation par matrice de questions avec icônes de statut (Non répondu, Réussi en vert, Erreur en rouge, Favoris en jaune).
  - Recherche instantanée et filtres (Toutes, Mes Favoris ⭐, Erreurs à revoir ❌).
- **Interface QCM & Cartes d'options (A, B, C, D, E)** :
  - En-tête avec fil d'Ariane (`SVT > Génétique Fondamentale > Série I`).
  - Indication claire des choix multiples ou choix uniques.
  - Boutons d'options interactifs avec badge lettre, animations et retour visuel immédiat.
  - Animation de confettis lors des bonnes réponses.
- **Barre d'actions** :
  - Bouton **Vérifier la réponse**.
  - Flèches de navigation `<` et `>` (avec support des touches clavier `←` et `→`).
  - Bouton **💡 Expliquer** magenta fuchsia ouvrant une boîte d'explication détaillée.
  - Bouton **Ajouter à mes questions** (Bookmark).
  - Bouton de réinitialisation pour s'entraîner à nouveau.

---

### 2. Contenu Médical Exhaustif (Issu à 100% du document PDF)
- **83 Questions complètes** réparties sur les 3 séries d'examen :
  - **Série I** : 25 Questions avec correction officielle (Badou - FMPC).
  - **Série II** : 26 Questions avec correction officielle.
  - **Série III** : 32 Questions avec correction officielle.
- **Réponses exactes strictement fidèles aux propositions soulignées** dans le document numérisé.
- **Explications médicales générées et vérifiées** :
  - Analyse conceptuelle pour chaque question.
  - Justification précise de chaque proposition exacte.
  - Explication des distracteurs et pièges classiques de concours.
  - Points clés de cours à mémoriser.

---

### 3. Système d'Accès Payant & Tableau de Bord Administrateur (Contrôle Total)
- **Modèle Freemium / Accès Payant Maîtrisé** :
  - Chaque étudiant s'inscrit avec son **Nom**, **Email**, **Téléphone/WhatsApp** et **Mot de passe**.
  - Dès l'inscription, le compte reçoit automatiquement le statut **`En attente d'activation` (pending)**.
  - L'étudiant ne peut pas accéder aux QCM tant que vous n'avez pas activé son compte.
  - L'étudiant voit un écran élégant l'invitant à vous contacter sur WhatsApp avec un message pré-rempli.
- **Panneau de Contrôle Administrateur (`Admin Dashboard`)** :
  - Accessible via le bouton **Administration** dans la barre supérieure ou en se connectant en tant qu'admin.
  - **Indicateurs KPI** : Total inscrits, Comptes en attente, Abonnés actifs, Total des réponses et taux de précision.
  - **Tableau de gestion des étudiants** :
    - Recherche par nom, email ou numéro de téléphone.
    - Filtrage par statut (**Tous**, **En attente d'activation**, **Actifs**, **Suspendus**).
    - Bouton **Activer** : débloque l'accès en 1 clic.
    - Bouton **WhatsApp** : ouvre une discussion directe avec l'étudiant avec un message de confirmation personnalisé.
    - Bouton **Suspendre** ou **Supprimer**.
  - **Ajout direct d'étudiant** : pour créer un compte déjà activé sans que l'étudiant n'ait à passer par l'inscription.
  - **Configuration du numéro WhatsApp** de l'administrateur.
  - **Modification du mot de passe administrateur**.

---

## 🔑 Identifiants Administrateur par Défaut

- **Email** : `admin@midooo.ma`
- **Mot de passe** : `admin`

*(Vous pouvez modifier le mot de passe à tout moment depuis le tableau de bord administrateur).*

---

## 🚀 Démarrage Rapide

### Option 1 : Double-clic sur Windows
Double-cliquez simplement sur le fichier :
```
start.bat
```

### Option 2 : En ligne de commande
```bash
npm run dev
```

L'application sera accessible sur :
- **Frontend Web** : [http://localhost:3000](http://localhost:3000)
- **API Backend** : [http://localhost:5000](http://localhost:5000)
