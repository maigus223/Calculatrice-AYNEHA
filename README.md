# 🧮 Calculatrice Web AYNEHA

[![Web App](https://img.shields.io/badge/Platform-Web%20App-blue.svg)](#)
[![JavaScript](https://img.shields.io/badge/Language-JavaScript%20%2F%20HTML5-yellow.svg)](#)
[![CSS3](https://img.shields.io/badge/Styling-CSS3%20%2F%20Flexbox-blue.svg)](#)
[![Direction-RTL](https://img.shields.io/badge/Directionality-Right--to--Left%20(RTL)-orange.svg)](#)
[![License](https://img.shields.io/badge/License-Copyright%20MAIGUS-blue.svg)](#)

Une application web interactive de calcul mathématique nativement intégrée au **système d'écriture AYNEHA**. Elle prend en charge la numération décimale **Right-to-Left (RTL)** et le rendu typographique de la langue **Soŋay**.

---

## 🌟 Présentation

La **Calculatrice Web AYNEHA** permet d'exécuter des opérations arithmétiques directement dans le navigateur en utilisant la plage de chiffres RTL d'AYNEHA (`U+E000` à `U+E009`). L'interface s'appuie sur la police web vectorielle `@font-face` pour afficher dynamiquement les chiffres et symboles du registre calculatoire.

### Key Features / Fonctionnalités Clés
* **Interface Web Responsive** : S'adapte parfaitement aux écrans mobiles, tablettes et ordinateurs.
* **Affichage RTL Dynamique** : Alignement à droite des opérandes, résultats et historique d'affichage.
* **Intégration Typographique Web** : Chargement direct du fichier de police `Ayneha-Regular.ttf` / `woff2`.
* **Saisie Clavier & Tactile** : Prise en charge des clics sur les boutons interactifs et raccourcis clavier.

---

## 📐 Spécifications Typographiques (Unicode PUA)

L'application s'appuie sur la **Matrice Officielle AYNEHA** :

| Catégorie | Plage Unicode PUA | Description |
| :--- | :--- | :--- |
| **Chiffres Décimaux RTL** | `U+E000` à `U+E009` | Chiffres 0 à 9 conçus pour la numération et le calcul RTL. |
| **Directionalité** | `Right-to-Left` (RTL) | Flux applicatif et saisie calculatoire de droite à gauche (`dir="rtl"`). |
| **Font-Face Web** | `Ayneha-Regular.ttf` | Police vectorielle chargée via CSS (`@font-face`). |

---

## 📁 Structure du Projet

```text
Calculatrice-AYNEHA/
├── index.html          # Structure HTML5 (avec attribut dir="rtl")
├── style.css           # Feuilles de style, layout responsive & @font-face
├── script.js           # Logique de calcul et gestion des entrées PUA
└── fonts/
    └── Ayneha-Regular.ttf # Police vectorielle AYNEHA
