# Plants vs. Zombies – Game Balance & Difficulty Analysis (Tableau)

## Project Overview

This Tableau data visualization project explores **game balance and level difficulty** in *Plants vs. Zombies* through large-scale, structured game data.

By integrating **plant attributes**, **zombie characteristics**, and **level configurations**, the project examines how numeric design choices translate into perceived difficulty, pacing, and player pressure. The analysis focuses on how difficulty emerges not from a single factor, but from the interaction between health, damage, density, and spatial distribution.

The project is designed as an **exploratory analytics case study**, demonstrating how multi-dimensional visualizations can surface design patterns and balance trade-offs in complex systems.

---

## Key Insights

### 1. Level difficulty is driven more by **total zombie health** than by zombie count alone
Levels with similar numbers of zombies can differ substantially in overall difficulty. Total zombie HP and health composition play a more decisive role than enemy volume.

### 2. Difficulty progression across chapters is **non-linear**
While later chapters are generally harder, several levels exhibit sharp difficulty spikes. This suggests uneven pacing and intentional challenge design rather than smooth linear progression.

### 3. Plant effectiveness varies widely relative to cost and cooldown
Higher-cost plants do not consistently deliver proportionally higher damage or efficiency. This highlights trade-offs between resource investment, damage output, and strategic utility.

### 4. Player pressure is unevenly distributed across levels
Metrics such as **damage sustained per lane** show that some levels concentrate attack intensity spatially, increasing challenge independently of total enemy count.

---

## Visualization Design & Chart Types

The analysis is supported by a range of visualization techniques commonly used in exploratory data analysis and game analytics:

- **Bar Charts** 
- **Stacked Bar Charts**  
- **Line Charts** 
- **Scatter Plots** 
- **Radar Charts (Spider Charts)** 
- **Treemaps (Mosaic Charts)** 
- **Wind Rose Charts (Polar Area Charts)** 
- **Funnel Charts (Conical Bar Charts)** 

## Methods

- Aggregated and standardized plant, zombie, and level attributes  
- Constructed difficulty proxies using total HP, damage intensity, and spatial distribution metrics  
- Designed multi-dimensional visualizations in Tableau to support exploratory and comparative analysis  
- Focused on interpretability, axis clarity, and consistent encoding across views  

---

## Tools & Files

- **Tableau**  
- Structured game attribute datasets  

Repository contents:
- `README.md` – project overview and methodology  
- `Plants_vs_Zombies_Analysis.pdf` – static visualization export  
- `Plants_vs_Zombies.twbx` – interactive Tableau workbook  
