# 🎓 Projet de Gestion des Stages

## 📖 Description

Ce projet est une application permettant de **gérer les stages** au sein du département informatique. Il facilite la gestion des **offres de stages, candidatures, affectations des étudiants et notation des stages** par un jury.

L'application est conçue pour répondre aux besoins de plusieurs utilisateurs :
- 📌 **Responsable des stages** : Ajoute et supprime des offres, assigne des étudiants aux stages.
- 📌 **Étudiants** : Consultent les offres et postulent à un maximum de trois stages.
- 📌 **Jury** : Note les stages à la fin de l'année.

---

## 🎯 Fonctionnalités Implémentées

- 📂 **Gestion des Offres de Stages**
  - Ajout et suppression d’une offre de stage.
  - Stockage des offres dans un fichier.
  - Consultation des offres disponibles.

- 📝 **Candidature des Étudiants**
  - Postulation à un stage (limité à 3 candidatures par étudiant).
  - Vérification des contraintes (max 3 candidats par stage).
  - Affichage des candidatures en cours.

- 📌 **Affectation des Stages**
  - Attribution d’un stage à un étudiant.
  - Suppression automatique des autres candidatures de l’étudiant.
  - Mise à jour du fichier des stages.

- 🏅 **Notation des Stages**
  - Attribution de 3 notes par le jury :
    - Note d’entreprise (coefficient 2).
    - Note du rapport (coefficient 1).
    - Note de soutenance (coefficient 1).
  - Calcul de la **moyenne des notes**.
  - Classement des étudiants par note décroissante.

- 📊 **Affichages Divers**
  - Liste des stages **pourvus** et les étudiants affectés.
  - Liste des stages **non pourvus**.
  - Liste des étudiants **sans stage**.
  - Détails d’un stage donné.
  - Recherche de stages par **référence** ou **département**.

- 💾 **Sauvegarde et Chargement des Données**
  - Les données sont stockées dans des **fichiers textes**.
  - Chargement des données à l’ouverture de l’application.
  - Sauvegarde automatique à la fermeture.

- 🔒 **Sécurisation avec Mot de Passe**
  - Accès restreint pour les fonctionnalités administratives.
  - Stockage sécurisé des mots de passe.

---

## 🛠️ Technologies Utilisées

- **Langage** : C
- **Gestion des fichiers** : Stockage des données dans des fichiers texte.
- **Structures de données** :
  - Listes triées pour optimiser la recherche.
  - Listes interconnectées avec mise à jour des indices.

---

Développé par Ghassan Jabbour et Sami Halilou dans le cadre du projet **SAÉ S1.02 - Comparaison d’approches algorithmiques** à **Université Clermont Auvergne**.
