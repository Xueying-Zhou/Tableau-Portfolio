## Project Overview

This Tableau data visualization project analyzes character attributes and level difficulty in *Plants vs. Zombies* using large-scale game data.  
By integrating plant statistics, zombie attributes, and level configurations, the project explores how game difficulty and balance emerge from underlying numeric design choices.

## Key Insights

- **Level difficulty is driven more by total zombie HP than by zombie count alone.**  
  Levels with similar numbers of zombies can differ substantially in overall difficulty, indicating that health composition plays a larger role than volume.

- **Difficulty progression across chapters is non-linear.**  
  While later chapters are generally harder, several levels show sharp difficulty spikes, suggesting uneven pacing in game design.

- **Plant effectiveness varies widely relative to cost and cooldown.**  
  Higher-cost plants do not consistently deliver proportionally higher damage or efficiency, highlighting potential balance trade-offs in character design.

- **Player pressure is unevenly distributed across levels.**  
  Metrics such as damage absorbed per grid reveal that certain levels concentrate attack intensity, increasing challenge independently of total enemy count.

## Methods

- Aggregated and standardized plant, zombie, and level attributes  
- Constructed difficulty proxies using total HP, damage intensity, and distribution metrics  
- Designed multi-dimensional visualizations (scatter plots, bubble charts, treemaps, and comparative bar charts) in Tableau to support exploratory analysis

## Tools

- Tableau  
- Structured game attribute datasets

This project demonstrates how data visualization can be used to diagnose balance issues and support design decisions in complex systems.
