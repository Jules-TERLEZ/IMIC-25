# 🚀 Flexibac – Simulation Multi-Agent avec MBSE

![Projet universitaire](https://img.shields.io/badge/Université%20de%20Lorraine-Project-lightgrey?logo=googlescholar)
![AnyLogic](https://img.shields.io/badge/Simulation-AnyLogic-blue.svg)
![MBSE](https://img.shields.io/badge/Approach-MBSE-orange.svg)
![Contributions welcome](https://img.shields.io/badge/Contributions-welcome-brightgreen.svg)

**🎯 Objectif :** Optimiser un système de tri postal avec un robot 6 axes (Concours IMIC’25).  
**🛠 Technologies :** AnyLogic • MBSE (Model-Based Systems Engineering)  
**👥 Auteurs :** Jules Terlez • Abdessamad Boungab • William Derigent  
**🏫 Université de Lorraine – Master Ingénierie des Systèmes Complexes**

---

## ✨ Aperçu rapide
- 📦 Simulation **multi-agents** : Robot, opérateurs humains, chariots.  
- ⚡ Gestion dynamique des flux entre ressources humaines et robotisées.  
- 📊 Résultats initiaux : **25,8 %** de tri robotisé (objectif industriel : 50 %).  
- 🔎 Points à améliorer : pertes liées aux chariots saturés, optimisation des destinations.  

---

## 📷 Visuels
![Schéma système](assets/flexibac-diagram.png)  
*Architecture et PFMS du système Flexibac*  

---

## 🚀 Lancer la simulation
1. Installer **AnyLogic (version utilisée : préciser ici)**  
2. Ouvrir le modèle :  
   ```bash
   /models/Flexibac.alp
3. Lancer ▶ et observer les résultats (statistiques affichées en fin de simulation).

---

## 📂 Organisation du dépôt

- /models → fichiers AnyLogic
- /src → code auxiliaire (agents, fonctions, scripts)
- /docs → 📄 Rapport complet (PDF)
- /assets → images & diagrammes SysML
- /results → exports de simulation

---

## 🔮 Améliorations prévues

- ✅ Optimiser la stratégie de gestion des chariots
- ✅ Tester sur plusieurs instances (au-delà de Nc_5_50_10_1)
- ✅ Réduire le nombre de boîtes perdues
- 🔄 Comparer avec d’autres approches (heuristiques, optimisation mathématique)

---

## 🙌 Remerciements

- Projet réalisé dans le cadre du Concours IMIC’25 avec le soutien de :
- Université de Lorraine
- CRAN, CNRS UMR 7039
- Collaboration industrielle avec La Poste & Université de Nantes
