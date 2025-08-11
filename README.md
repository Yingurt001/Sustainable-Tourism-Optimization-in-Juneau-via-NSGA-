# 🌏 Sustainable Tourism Optimization Model  

**A Multi-Objective Optimization Framework for Balancing Economic Growth, Environmental Protection, and Social Well-Being in Tourism Management**  

<!-- Banner -->
<div align="center">
  <img src="Assets/Banner.png" width="100%" alt="Project Banner">
</div>

<!-- Badges -->
<div align="center">
  <img src="https://img.shields.io/github/stars/YourRepoName/Sustainable-Tourism-Model?style=flat-square" alt="Stars">
  <img src="https://img.shields.io/github/license/YourRepoName/Sustainable-Tourism-Model?style=flat-square" alt="License">
  <img src="https://img.shields.io/badge/Python-3.8%2B-blue?style=flat-square" alt="Python Version">
</div>

---

## 📜 Overview  

This repository presents an **integrated, data-driven framework** for sustainable tourism management, designed to help policymakers, researchers, and urban planners strike a **delicate balance between economic growth, environmental preservation, and social well-being**.  

Using **Juneau, Alaska** as the primary case study, the project integrates two complementary models:  

1. **Sustainability & Productivity Evaluation Model (SPEM)** – A weighted composite index to quantify the economic, environmental, and social dimensions of tourism.  
2. **Sustainability & Productivity Genetic Optimization Model (SP-GOM)** – A **multi-objective NSGA-II optimization** for maximizing both **economic productivity** and **sustainability performance**.  

**Key Research Goals:**  
- 📈 Quantify economic benefits, environmental costs, and social impacts of tourism.  
- 🧮 Optimize route- and activity-specific tourism tax rates.  
- 🌿 Create transferable, destination-adaptive models (e.g., Bali, Santa Barbara).  
- 🔍 Conduct sensitivity analyses to identify the most influential policy levers.  

---

## 📦 Installation  

```bash
git clone https://github.com/YourRepoName/Sustainable-Tourism-Model.git
cd Sustainable-Tourism-Model
pip install -r requirements.txt
```



## 📊 Dataset Description  

The dataset consolidates **tourism flow**, **economic**, **environmental**, and **social indicators** for **Juneau**, with adapted datasets for **Bali** and **Santa Barbara**.

### 1️⃣ Tourism Flow Data  
- Annual visitor numbers, distributed across three major routes: **Glacier**, **Whale Watching**, and **Rainforest**.  
- Route-specific breakdown across five expenditure categories: sightseeing, shopping, dining, accommodation, and transportation.  
- Seasonal fluctuations and long-term trends (2011–2023).  

### 2️⃣ Economic Data  
- Average tourist expenditure per route and activity type.  
- Government tourism tax rates by consumption path.  
- Household income distribution (low, middle, high, very high).  
- Poverty rate variation and employment capacity metrics.  

### 3️⃣ Environmental Indicators  
- **Per-capita carbon emissions** for each route.  
- **Biodiversity loss index**, including mitigation effects from tourism revenue allocation.  
- **Glacier retreat data** for Mendenhall Glacier (annual degradation rates).  
- Estimated environmental carrying capacity for the city.  

### 4️⃣ Social Indicators  
- **Overcrowding index**: tourist-to-capacity ratio per route.  
- **Resident satisfaction** linked to infrastructure investment and congestion.  
- **Infrastructure pressure index**: utilization of transport, energy, and public facilities.  

### 5️⃣ Adapted City Datasets  
- **Bali**: Volcano, beach, and cultural tour routes, including coral reef degradation and infrastructure load.  
- **Santa Barbara**: Beach, cultural, and hiking routes, with sea-level rise and marine pollution indicators.  

---

## 🔬 Methodology  

### 1️⃣ Sustainability & Productivity Evaluation Model (SPEM)  
- **Tourism Revenue** – Computed using route-specific expenditures and tax rates.  
- **Environmental Cost** – Derived from carbon emissions, biodiversity loss, and glacier retreat rates.  
- **Social Cost** – Includes overcrowding, resident satisfaction, and infrastructure stress.  
- **Dynamic System Framework** – Feedback-loop integration with dynamic programming for long-term simulation.  

### 2️⃣ Sustainability & Productivity Genetic Optimization Model (SP-GOM)  
- **Algorithm** – NSGA-II multi-objective optimization.  
- **Decision Variables** – 15 tourism tax rates (3 routes × 5 activities).  
- **Objectives** – Maximize **Sustainability Index (Z)** and **Economic Productivity Index (EPI)**.  
- **Outcome** – Pareto frontier providing optimal trade-offs between economic and environmental objectives.  

### 3️⃣ Sensitivity Analysis  
- Assessed the impact of tax rate changes on route-specific tourist flows.  
- Estimated price elasticity coefficients for each tourism route.  

### 4️⃣ Model Adaptability  
- Applied to **Bali** and **Santa Barbara** with adjusted route structures and environmental constraints.  
- Generated destination-specific taxation and sustainability strategies.  

---

## 🧱 Project Structure  

```bash
├── data/                              # Raw and processed datasets
├── models/                            # SPEM and SP-GOM model code
├── optimization/                      # NSGA-II optimization scripts
├── sensitivity_analysis/              # Sensitivity analysis modules
├── results/                           # Pareto plots, simulation outputs
├── requirements.txt                   # Python dependencies
├── LICENSE
├── README.md
