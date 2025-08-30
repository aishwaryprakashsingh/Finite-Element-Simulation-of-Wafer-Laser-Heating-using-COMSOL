# 🔬 Laser Heating Simulation of Silicon Wafer using COMSOL Multiphysics

## 📌 Overview
This project models the **transient thermal response of a silicon wafer** under **laser heating** using **COMSOL Multiphysics**.  
The study captures **temperature variations, hotspot formation, and thermal gradients** induced by a moving Gaussian laser beam, which is relevant for **semiconductor wafer processing and materials engineering**.

---

## 🎯 Objectives
- Simulate the **temperature distribution** in a silicon wafer subjected to a moving laser beam.  
- Study the effects of **laser power, beam profile, wafer rotation, and radiation losses**.  
- Provide insights for **semiconductor fabrication and thermal process optimization**.  

---

## 🗂️ Model Setup
- **Wafer:** 2-inch diameter, 275 µm thick silicon wafer.  
- **Laser:** 10 W, Gaussian beam, spot radius ≈ 2 mm.  
- **Motion:** Wafer rotates at 10 RPM, laser moves radially with a 20 s period.  
- **Physics:** Heat Transfer in Solids with Gaussian heat flux and surface-to-ambient radiation (ε = 0.8).  
- **Mesh:** Swept triangular mesh, one element through thickness.  

---

## 📊 Results
- Captured **spatial and temporal temperature variations** in wafer.  
- Observed **hotspot concentration** at beam focus with maximum temperature gradients.  
- Showed that **wafer rotation smooths temperature profile**, but hotspots persist under continuous irradiation.  





---

## 🛠️ Tools & Methods
- **Software:** COMSOL Multiphysics (Heat Transfer Module).  
- **Method:** Finite Element Method (FEM).  
- **Physics:** Heat Transfer in Solids, Moving Heat Source, Surface Radiation.  

---

## 🚀 How to Run
1. Open the model file (`Finite Element Simulation of Wafer Laser Heating using COMSOL.mph`) in COMSOL Multiphysics.  
2. Navigate to **Study → Compute** to run the simulation.  
3. Results include temperature plots, hotspot maps, and time evolution curves.  

---

## 📌 Author
👤 **Aishwary Prakash Singh**  
M.Tech, Chemical Engineering  
Indian Institute of Technology, Kanpur  

📧 [aishwary24@iitk.ac.in](mailto:aishwary24@iitk.ac.in)  
🔗 [LinkedIn](https://www.linkedin.com/in/aishwary-prakash-singh-9318a7216)  

---

⭐ If you find this project useful, please consider giving it a star!
