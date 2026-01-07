# Circular Supply Chain Design for Photovoltaic Modules
**Indo-German Challenge Project (Group 1)**

## Project Overview
This project develops a **Multi-Objective** mathematical optimization model to design and analyze a closed-loop supply chain for Photovoltaic (PV) modules in Germany. The model optimizes the trade-offs between **economic costs** and **environmental impacts ($CO_2e$)** using the $\epsilon$-constraint method to generate Pareto frontiers.

The project addresses the gap in quantitative analysis for PV circular supply chains by operationalizing these concepts with detailed regional data.

## Mathematical Model
The model represents a closed-loop network flow including Material Suppliers, OEMs, Customers, Collection Centers, Refurbishing Centers, and Landfills.

* **Objective 1:** Minimize Total Economic Cost ($Z_{Cost}$), including fixed, operation, transport, and penalty costs minus revenues.
* **Objective 2:** Minimize Environmental Impact ($Z_{Env}$), including emissions from production, operations, and transportation.
* **Key Constraints:** Demand satisfaction, flow balance, capacity limits (forward & reverse), and refurbishing yields.

## Scenarios Analyzed
The optimization compares four specific circularity configurations:
1.  **Scenario A (Linear/Baseline):** Limited reuse and low refurbishment yield.
2.  **Scenario B (Industrial Refurbishment):** High refurbishment efficiency.
3.  **Scenario C (Consumer Reuse):** High direct reuse rates.
4.  **Scenario D (Ideal Balanced Circular):** Moderate reuse combined with moderate refurbishment.

## 📊 Results & Pareto Frontiers
<img width="3000" height="2100" alt="Comparison_2_Cost_on_X" src="https://github.com/user-attachments/assets/d58c8080-27c2-4459-9d0a-854699c0db3b" />

<img width="3000" height="2100" alt="Comparison_1_Env_on_X" src="https://github.com/user-attachments/assets/a6459b00-8fcf-4a02-90cf-02a3418fa85f" />

## 🛠️ Tech Stack
* **Language:** Python 
* **Solver:** Gurobi Optimizer 
* **Data Source:** Realistic magnitudes based on German PV market data (2025 estimates).

## 👥 Authors
* **Anushka Pawar** (Manipal University Jaipur) 
* **Ananya Jain** (Manipal University Jaipur) 
* **Eric Hübner** (Technical University of Braunschweig)

---
**Supervisors:** Dr. Alexander Barke, Dr. Vijaypal Poonia.
