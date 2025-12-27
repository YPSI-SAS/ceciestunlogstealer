# Anatomie d'un Infostealer

Animation pédagogique en pixel art 8-bit expliquant le fonctionnement d'un infostealer, de l'infection à la revente des données.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![Canvas](https://img.shields.io/badge/Canvas-API-green)

## 🎯 Objectif

Support de formation pour sensibiliser aux risques des infostealers :
- Comment ils infectent les machines
- Pourquoi les antivirus classiques les détectent difficilement
- Ce qu'ils volent et comment
- Comment se protéger

## 🎮 Démo

Ouvrir `index.html` dans un navigateur moderne (Chrome, Firefox, Edge).

Navigation manuelle avec les boutons **PRÉCÉDENT** / **SUIVANT** ou clic direct sur les étapes.

## 📚 Étapes couvertes

| Étape | Contenu |
|-------|---------|
| **1. Infection** | Vecteurs : cracks, pièces jointes, faux sites |
| **2. AV vs EDR** | Pourquoi l'AV dort (lecture seule) et l'EDR détecte |
| **3. Collecte** | Fichiers ciblés : Login Data, Cookies, Web Data, Wallets |
| **4. Exfiltration** | ZIP + AES + HTTPS POST |
| **5. Revente** | Tarifs darknet, account takeover, pivot entreprise |
| **6. Défense** | Recommandations : gestionnaire MDP, 2FA matériel, EDR... |

## 🛠 Caractéristiques techniques

- **100% standalone** : un seul fichier HTML, aucune dépendance externe
- **Pixel art** : sprites dessinés en JavaScript (pas d'images)
- **Animations** : système de particules, easing, effets visuels
- **Responsive** : adapté desktop et mobile
- **Léger** : ~40 Ko

## 🔒 Points clés pédagogiques

**Pourquoi l'AV ne détecte pas :**
- Le stealer ne fait que LIRE des fichiers existants
- Comportement identique à Chrome ou Word
- Pas de chiffrement, injection ou modification

**Pourquoi l'EDR a plus de chances :**
- Analyse comportementale
- Corrélation des accès fichiers sensibles
- Détection des connexions réseau suspectes

**Données ciblées :**
- `Login Data` → mots de passe (SQLite)
- `Cookies` → sessions actives (bypass 2FA)
- `Web Data` → cartes bancaires
- `Wallets` → clés crypto

## 📝 Licence

Libre d'utilisation pour la formation et la sensibilisation cybersécurité.

Créé par [YPSI](https://ypsi.fr) - Formation Cybersécurité & Gestion de Crise

## 🤝 Contributions

Issues et PR bienvenues pour :
- Corrections techniques
- Nouvelles recommandations de défense
- Traductions
