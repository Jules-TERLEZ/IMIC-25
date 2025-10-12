# Flexibac – Simulation Multi-Agent avec approche MBSE

![Projet universitaire](https://img.shields.io/badge/Université%20de%20Lorraine-Project-lightgrey?logo=googlescholar)
![AnyLogic](https://img.shields.io/badge/Simulation-AnyLogic-blue.svg)
![MBSE](https://img.shields.io/badge/Approach-MBSE-orange.svg)
![Contributions welcome](https://img.shields.io/badge/Contributions-welcome-brightgreen.svg)

**💡 Contexte :** Concours IMIC'25 : Flexibac - **🥈 2ème meilleure solution**       
**🎯 Objectif :** Proposer une solution pour intégrer un robot 6 axes à un système de tri postal  
**🛠 Technologies :** AnyLogic • Cameo Systems Modeler • Rhapsody   
**👥 Auteurs :** Jules Terlez • Abdessamad Boungab • William Derigent  
**🏫 Université de Lorraine** – Projet universitaire - Master Ingénierie des Systèmes Complexes  

---

## ✨ Aperçu rapide

- 💡 **IMIC (International Manufacturing International Contest) : [Concours annuel international](https://hal.science/EC-NANTES/hal-04770839v1)** pour créer un **Benchmark**.  
  En **2025**, **dans le cadre de ce concours**, le problème posé est : **[Flexibac](https://github.com/GIS-S-mart/Benchmark-9-IMIC)** --> **_Intégrer un robot 6 axes au système de tri de la Poste de Nantes_**
<details>
  <summary>En savoir plus sur le concours IMIC</summary>

  > Chaque année, un problème de production intelligente est posé à plusieurs universités participantes dans le monde.  
  > 1. Les universités participantes **proposent** chacune une **solution**.  
  > 2. Ces solutions forment ainsi un **Benchmark** pour le problème posé.  
  > 3. La **meilleure solution** est retenue comme **référence** pour ce problème.  
  > 4. Un **article scientifique** présentant cette solution est publié.
---
<p align="center">
    <img src="assets/images/Topology.png" width="600"><br>
    <em>Schéma du système de tri pour le problème Flexibac</em>
  </p>
</details>

- 🎯 **Maximiser le nombre de cartons traités par le robot** (ce qui implique) :  
      1. Aiguiller les cartons vers le robot ou vers les opérateurs  
      2. Gérer les chariots
    
- 🛠 **Conception de la solution avec approche MBSE** (Model-Based Systems Engineering) :  
      1. Ingénierie des Exigences  
      2. Architecture Système  
      3. Modélisation du système sur Anylogic
    
- 📦 Simulation **multi-agents** disponible ici.

---

## 📷 Visuels 

<details>
  <summary>Aperçu simulation Anylogic</summary>
<p align="center">
    <img src="assets/images/Anylogic_screenshot.png" width="800"><br>
    <em>Aperçu simulation Anylogic</em>
  </p>
</details>

---

## 📂 Organisation du dépôt

- assets → instances & images  
- docs → 📄 Rapports complets (PDF)  
- models → fichiers AnyLogic, Cameo Systems Modeler, Rhapsody
- results → exports de simulation + rapport final

---

## 🚀 Lancer la simulation

1. Téléchargez le dossier -> models/Anylogic_Modelisation/Flexibac
2. Téléchargez Anylogic (version 8.9.4 ou supérieure).
3. Lancez Anylogic.
4. Ouvrez le fichier Anylogic (Ctrl+O ou Fichier -> Ouvrir) : Flexibac.alp
5. Exécutez (F5 ou Modèle -> Exécuter).

---

## 🙌 Remerciements

Projet réalisé dans le cadre du Concours IMIC’25 avec le soutien de :
- Université de Lorraine
- CRAN, CNRS UMR 7039
- Collaboration industrielle avec La Poste & Université de Nantes
