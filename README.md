# 🏙️ Défis Numérique Urbain | SNT Seconde

[![SNT](https://img.shields.io/badge/Thème-SNT%20Seconde-blueviolet)](https://eduscol.education.fr/1660/sciences-numeriques-et-technologie-en-classe-de-seconde)
[![Mode](https://img.shields.io/badge/Mode-100%25%20Débranché-orange)](#)
[![Durée](https://img.shields.io/badge/Durée-1h30-green)](#)

> **Simulation d'une cellule de crise à Numéropolis.** > Ce projet documente la résolution d'une alerte incendie majeure en utilisant exclusivement les concepts des Sciences Numériques et Technologie (SNT).

---

## 📜 Scénario
La ville connectée de **Numéropolis** fait face à une urgence : un incendie a été détecté dans le quartier Nord par des capteurs de température. En tant que **cellule de crise numérique**, notre mission est de localiser le sinistre, de transmettre l'information de manière sécurisée et de coordonner les secours via les infrastructures de la *Smart City*.

---

## 🎯 Compétences SNT Mobilisées
Le défi est structuré autour des 7 thèmes du programme de seconde :

| Thème | Concept Clé | Application dans le défi |
| :--- | :--- | :--- |
| **Localisation** | Triangulation GPS | Calcul des coordonnées `(latitude, longitude)` du foyer. |
| **Photographie** | Encodage & Pixels | Numérisation d'une image témoin en grille 8x8 (noir/blanc). |
| **Internet** | Protocoles TCP/IP | Simulation de routeurs et acheminement de paquets de données. |
| **Web** | HTML/CSS | Création d'une page d'alerte publique pour les citoyens. |
| **Données** | Fichiers CSV | Mise à jour de la base de données des incidents urbains. |
| **Réseaux Sociaux** | Graphes de relations | Analyse de la propagation de l'alerte sur le réseau urbain. |
| **Embarqué** | Algorithmique | Programmation logique des actionneurs (bornes incendie). |

---

## 🚀 Déroulement du Défi

### 📍 Étape 1 : Localisation & Identification
* **Objectif :** Identifier le point exact de l'incendie sur le plan de la ville (Grille A-J / 1-8).
* **Production :** Encodage binaire d'une vignette de fumée détectée par drone.

### 🌐 Étape 2 : Le Réseau Numéropolis
* **Objectif :** Envoyer l'alerte vers la caserne des pompiers via un réseau de routeurs.
* **Méthode :** Découpage du message en 3 paquets IP, adressage et gestion des pertes de paquets.

### 📊 Étape 3 : Information & Base de Données
* **Objectif :** Rédiger le code HTML de la page d'urgence et ajouter l'entrée correspondante dans le fichier `incidents.csv`.
* **Analyse :** Calcul du degré de séparation sur le graphe social pour toucher un maximum d'habitants.

### 🤖 Étape 4 : Action & Éthique
* **Objectif :** Définir l'algorithme "Si [Température > 50°C] Alors [Ouvrir vannes]".
* **Réflexion :** Débat sur les enjeux de la surveillance urbaine et de la protection des données privées.

---

## 🛠️ Matériel utilisé
- [x] Carte A3 de Numéropolis
- [x] Cartes événements (Triangulation, Paquets IP)
- [x] Grille de pixel art 8x8
- [x] Graphes de réseaux sociaux papier

---

## 👥 Membres de la cellule de crise
* **Nom 1** (@username) - Spécialiste Réseaux
* **Nom 2** (@username) - Analyste de Données
* **Nom 3** (@username) - Développeur Web
* **Nom 4** (@username) - Responsable Systèmes Embarqués

---
*Ce projet a été réalisé dans le cadre du cours de SNT (Sciences Numériques et Technologie) - Lycée [Nom de votre lycée].*
