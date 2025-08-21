# Low Voltage Distribution Network Design, Load Flow, and Short Circuit Analysis  

## Overview  
This project demonstrates the end-to-end workflow of designing and analyzing a **1000 kVA, 415 V low-voltage distribution network**. The network was modeled in **AutoCAD** for single-line diagrams, feeder pillar layouts, protection schemes, and cable sizing, and validated through **ETAP simulations**. Both **load flow** and **short circuit analyses** were performed to ensure the system meets voltage regulation, reliability, and safety standards.  

## Tools & Technologies  
- **AutoCAD** – Single-line diagrams, feeder pillar design, voltage drop calculations, and cable sizing  
- **ETAP** – Load flow analysis, voltage profile verification, transformer loading, system loss evaluation, and short circuit analysis  

## Key Features  
- Designed a **1000 kVA package unit (11 kV / 0.415 kV transformer)** with **8 feeders** and **20+ loads**  
- Verified **voltage drop ≤ 4%** across all feeders through AutoCAD calculations  
- Performed **ETAP load flow analysis** confirming:  
  - **Bus voltages ≥ 96%**  
  - **Transformer loading at 60.5%** of rated capacity  
  - **System losses < 3%** of total load  
- Conducted **short circuit analysis** to calculate fault levels at each bus and evaluate fault current waveforms for breaker and relay coordination  
- Optimized protection scheme with **630 A fuses, 200 A circuit breakers, and CTs (100/5 A)**  
- Enhanced network reliability, reducing outage risk by **>25%**  

## Repository Contents  
- **/AutoCAD_Files** – Single-line diagrams, feeder pillar schematics, and cable schedules  
- **/ETAP_Files** – Load flow and short circuit models with simulation results  
- **/Reports** – Design documentation, results, and analysis summaries  

## How to Use  
1. Open AutoCAD files (`.dwg`) to review the single-line diagram and feeder pillar design.  
2. Load ETAP project files to run load flow and short circuit simulations.  
3. Compare AutoCAD design calculations (voltage drops, cable sizes) with ETAP simulation results for validation.  

## Results  
- **Load Flow Analysis**: Stable bus voltages, safe transformer utilization, and controlled system losses  
- **Short Circuit Analysis**: Fault levels verified at all buses, with peak fault currents reaching ~65–70 kA near the transformer  
- **Protection Coordination**: Correct breaker and relay sizing ensured safe isolation under fault conditions  
- **System Reliability**: Improved resilience and reduced outage risk  

## Contact  
Created by **Raein Layegh Pour**  
[LinkedIn](https://www.linkedin.com/in/raeinlp) | [Portfolio](https://raeinportfolio.com)  

---

⭐ If you found this project useful, please consider giving it a star on GitHub!
