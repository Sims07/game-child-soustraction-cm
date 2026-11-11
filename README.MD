# 🦉 L'Académie de Soustraction Magique (CE2)

Une application web interactive et ludique conçue pour aider les enfants de CE2 à s'entraîner au calcul mental, en particulier à la **soustraction d'un nombre à 1 chiffre** (méthode de franchissement de la dizaine inférieure).

![Niveau](https://img.shields.io/badge/Niveau-CE2-purple.svg)
![Mobile Friendly](https://img.shields.io/badge/Compatibilit%C3%A9-iPhone%2017%20Pro-blue.svg)
![Tech Stack](https://img.shields.io/badge/Stack-HTML5%20%7C%20TailwindCSS%20%7C%20JS-emerald.svg)

---

## 🧙‍♂️ Contexte & Objectif Pédagogique

Basé sur les leçons de calcul mental du programme de CE2 (**Fiche CM5 : Soustraire un nombre inférieur à 9**), le jeu aide à automatiser deux stratégies clés :
1. **Atteindre la dizaine inférieure** : En décomposant le nombre à soustraire pour passer par la dizaine courante (ex: $52 - 7 = (52 - 2) - 5 = 50 - 5 = 45$).
2. **Retrait direct des unités** : Quand le retrait d'unités ne nécessite pas de casser la dizaine (ex: $57 - 5 = 52$).

Pour rendre la pratique stimulante et attrayante, l'interface plonge l'enfant dans un univers d'école de magie guidé par **Archibald le Hibou Mentor**.

---

## ✨ Fonctionnalités

- **📱 Optimisé pour Mobile & iPhone 17 Pro** : Interface responsive sur mesure, zones tactiles de frappe agrandies, respect des zones d'affichage (Safe Areas / Dynamic Island).
- **✨ Mode Entraînement** : Sans limite de temps, avec un volet d'aide escamotable expliquant la décomposition du calcul pas à pas.
- **⚡ Mode Défi Chronométré** : Reproduit le format officiel du cahier d'exercice (15 calculs en 3 minutes max).
- **🦉 Explications interactives** : En cas d'erreur, Archibald explique la stratégie de décomposition pour réexpliquer le raisonnement.
- **🔊 Effets Sonores Magiques** : Sons générés via l'API Web Audio (aucun fichier audio externe lourd à charger).
- **⭐ Système de Récompenses** : Obtention d'étoiles et de grades de sorcier en fonction des performances.

---

## 🚀 Installation & Utilisation

Aucune installation complexe requise (projet 100% web autonome en un seul fichier).

### En local
1. Clonez ce dépôt GitHub :
   ```bash
   git clone https://github.com/votre-nom-utilisateur/soustraction-magique.git
   ```
2. Ouvrez le fichier `index.html` dans n'importe quel navigateur sur ordinateur, tablette ou smartphone.

### Déploiement en ligne gratuit (GitHub Pages)
1. Allez dans les **Settings** de votre dépôt GitHub.
2. Section **Pages** (dans le menu latéral gauche).
3. Sous *Build and deployment*, choisissez la branche `main` et enregistrez.
4. Votre jeu sera accessible en ligne sur un lien type `https://votre-nom.github.io/soustraction-magique/` à enregistrer sur l'écran d'accueil de l'iPhone !

---

## 🛠️ Stack Technique

- **HTML5** & **CSS3** (Tailwind CSS via CDN)
- **JavaScript (ES6)** (Logique de jeu, gestionnaire de chrono, génération dynamique)
- **Web Audio API** (Sons magiques générés à la volée)
- **Google Fonts** (*Fredoka One* & *Quicksand*)

---

## 📜 Licence

Projet libre de droits et éducatif, créé avec amour pour encourager l'apprentissage des mathématiques en s'amusant ! 🪄
