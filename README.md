🌐 Available languages: [English](README.md) | [Français](README.fr.md)

# 🚀 Flexibac – Multi-Agent Simulation with MBSE

![Projet universitaire](https://img.shields.io/badge/Université%20de%20Lorraine-Project-lightgrey?logo=googlescholar)
![AnyLogic](https://img.shields.io/badge/Simulation-AnyLogic-blue.svg)
![MBSE](https://img.shields.io/badge/Approach-MBSE-orange.svg)
![Contributions welcome](https://img.shields.io/badge/Contributions-welcome-brightgreen.svg)

**🎯 Goal:** Optimize a postal sorting system with a 6-axis robot (IMIC’25 Challenge).  
**🛠 Technologies:** AnyLogic • MBSE (Model-Based Systems Engineering)  
**👥 Authors:** Jules Terlez • Abdessamad Boungab • William Derigent  
**🏫 University of Lorraine – Master of Complex Systems Engineering**

---

## ✨ Quick Overview
- 📦 **Multi-agent simulation**: Robot, human operators, carts.  
- ⚡ Dynamic management of flows between human and robotic resources.  
- 📊 Initial results: **25.8%** of boxes sorted automatically (industrial target: 50%).  
- 🔎 Limitations: box losses when carts get saturated, need for improved cart assignment strategy.  

---

## 📷 Visuals
![System diagram](assets/flexibac-diagram.png)  
*PFMS & system architecture of the Flexibac problem*  

---

## 🚀 How to Run the Simulation
1. Install **AnyLogic (version used: specify here)**  
2. Open the model file:  
   ```bash
   /models/Flexibac.alp
3. Run ▶ and observe the simulation results (statistics displayed at the end).
   
---

## 📂 Repository Structure

- /models → AnyLogic models
- /src → auxiliary code (agents, functions, scripts)
- /docs → 📄 Full Report (PDF)
- /assets → images & SysML diagrams
- /results → simulation outputs

---

## 🔮 Future Improvements

- ✅ Optimize cart management strategy
- ✅ Test on more instances (beyond Nc_5_50_10_1)
- ✅ Reduce lost boxes during simulation
- 🔄 Compare with alternative approaches (heuristics, optimization methods)

---

## 🙌 Acknowledgments

Developed for the IMIC’25 Challenge, with support from:
- University of Lorraine
- CRAN, CNRS UMR 7039
- Industrial collaboration with La Poste & University of Nantes
