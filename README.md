# 🧪 IBKR Portfolio Analyzer - DEV Version

[![Version](https://img.shields.io/badge/version-1.0-orange.svg)](https://github.com/Quasar-Nebulus/IBKR-Portfolio-Analyzer-DEV)
[![Status](https://img.shields.io/badge/status-TESTING-orange.svg)](https://quasar-nebulus.github.io/IBKR-Portfolio-Analyzer-DEV/)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)

## 🚀 Accès à la version DEV

**URL de test :** https://quasar-nebulus.github.io/IBKR-Portfolio-Analyzer-DEV/

⚠️ **Cette version est en phase de développement** - Les nouvelles fonctionnalités sont testées ici avant d'être mises en production.

---

## 📋 À propos

Analyseur de portefeuille **100% local** pour Interactive Brokers (IBKR).

- ✅ **Zéro serveur** - Vos données restent sur votre navigateur
- ✅ **IndexedDB** - Stockage local sécurisé et persistant
- ✅ **Import CSV** - Consolidation automatique de plusieurs fichiers
- ✅ **Détection doublons** - Gestion intelligente des réimports
- ✅ **Statistiques** - Vue d'ensemble de votre portefeuille
- ✅ **Fiscalité** - Calculs pour la déclaration d'impôts

---

## 🧪 Fonctionnalités en test

### ✨ Nouvelles dans cette version :

- **Suppression de données** - Bouton dans les paramètres pour vider complètement la base
- **Export JSON** - Exporter vos données au format JSON
- **Modal de confirmation** - Sécurité renforcée avant suppression

### 🔜 En développement :

- 📈 Graphiques et visualisations
- 📐 Calculs automatiques PV/PL
- 🔄 Détection avancée des roulements
- 📄 Génération d'IFU fiscale
- 💱 Analyse FOREX
- 🇺🇸 Calcul retenues USA

---

## 🎯 Comment tester

### 1. Importer des données

1. Cliquez sur **"Importer CSV"**
2. Sélectionnez un ou plusieurs fichiers CSV d'IBKR
3. Cliquez sur **"Consolider les données"**

### 2. Explorer

- **Explorer** → Voir les données par catégorie
- **Statistiques** → Résumé global
- **Roulements** → Détection des mouvements d'options

### 3. Gérer les données

- **Paramètres** → Supprimer toutes les données
- **Paramètres** → Exporter en JSON

---

## 💾 Stockage des données

Toutes les données sont stockées localement via **IndexedDB** :

```
navigateur → IndexedDB (IBKRPortfolio) → Stores:
  ├── transactions (clé: id)
  └── metadata (clé: key)
```

**Aucun upload vers serveur**. Vos données restent privées. 🔒

---

## 🔄 Workflow Dev → Prod

```
Branche DEV (ce repo)
    ↓
Vous testez à /IBKR-Portfolio-Analyzer-DEV/
    ↓
Vous validez : "C'est bon, passe en prod"
    ↓
Copie automatique vers repo PROD
    ↓
Live à /IBKR-Portfolio-Analyzer/
```

---

## 📢 Feedback

Vous avez une idée ? Un bug ? Une amélioration ?

→ [Ouvrir une issue](https://github.com/Quasar-Nebulus/IBKR-Portfolio-Analyzer-DEV/issues)

---

## 🔗 Liens utiles

- **Version PROD** : https://quasar-nebulus.github.io/IBKR-Portfolio-Analyzer/
- **Code source PROD** : https://github.com/Quasar-Nebulus/IBKR-Portfolio-Analyzer
- **Documentation** : Voir le code source

---

## ⚡ Tech Stack

- **Frontend** : HTML5 + CSS3 + Vanilla JavaScript
- **Stockage** : IndexedDB (navigateur)
- **Hosting** : GitHub Pages
- **Hash** : WebCrypto (SHA-256)

---

## 📝 License

MIT - Libre d'utilisation, modification et distribution.

---

**v1.0 - Version DEV** 🧪
