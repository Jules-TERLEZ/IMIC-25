# 🧠 Flexibac – Simulation Multi-Agent avec MBSE

![Projet universitaire](https://img.shields.io/badge/Université%20de%20Lorraine-Project-lightgrey?logo=googlescholar)
![AnyLogic](https://img.shields.io/badge/Simulation-AnyLogic-blue.svg)
![MBSE](https://img.shields.io/badge/Approach-MBSE-orange.svg)
![Contributions welcome](https://img.shields.io/badge/Contributions-welcome-brightgreen.svg)

**💡 Contexte :** Concours IMIC'25 : Flexibac    
**🎯 Objectif :** Proposer une solution d'intégration d'un robot 6 axes à un système de tri postal  
**🛠 Technologies :** AnyLogic • Cameo Systems Modeler • Rhapsody   
**👥 Auteurs :** Jules Terlez • Abdessamad Boungab • William Derigent  
**🏫 Université de Lorraine** – Projet universitaire - Master Ingénierie des Systèmes Complexes

---

## ✨ Aperçu rapide
- 💡 **IMIC (International Manufacturing International Contest)** : [Concours annuel](https://hal.science/EC-NANTES/hal-04770839v1) entre universités/écoles pour créer un Benchmark.
  Concours **IMIC 2025 : [Flexibac](https://github.com/GIS-S-mart/Benchmark-9-IMIC)** --> Intégrer un robot 6 axes au système de tri de la Poste de Nantes
  ![Schéma système de tri](documents/images/Topology.png)
  
    
- 🎯 **Maximiser le nombre de cartons traités par le robot** (ce qui implique) :  
      1. Aiguiller les cartons vers le robot ou vers les opérateurs  
      2. Gérer les chariots
    
- 🛠 **Conception de la solution avec approche MBSE** (Model-Based Systems Engineering) :  
      1. Ingénierie des Exigences *(définition des exigences, cycle de vie, cas d'utilisation)*  
      2. Architecture Système *(comportement du système : flux de travail et décisions)*  
      3. Modélisation du système sur [Anylogic](https://www.anylogic.fr/)
    
- 📦 Simulation **multi-agents** disponible ici.
 

---

## 📷 Visuels
![Aperçu simulation Anylogic](documents/images/Anylogic_screenshot.png) 
![Schéma système](Anylogic_screenshot.png)  
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

Projet réalisé dans le cadre du Concours IMIC’25 avec le soutien de :
- Université de Lorraine
- CRAN, CNRS UMR 7039
- Collaboration industrielle avec La Poste & Université de Nantes
