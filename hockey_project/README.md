# Network Analysis of KHL Hockey Players: Mapping Player Connectivity


> ⚠️ **Note:** Due to GitHub’s file size limitations (`"Sorry, this file is too big to display"`), the full interactive notebook is best viewed via [Nbviewer](https://nbviewer.org/github/diana-legrand/pet_projects/blob/main/hockey_project/Diana_Legrand_Hockey_Project.ipynb)

---

## Overview

This project explores player connectivity within the Kontinental Hockey League (KHL) using a graph-based approach. Inspired by the Erdős–Bacon number, it introduces a custom proximity metric to measure how closely any player is connected to Nikolai Lemtyugov through shared team history. The goal is to understand how tightly knit the league is and to visualize how players are linked through their careers, even if they never played together directly.


## Objectives

- Collect and clean historical data on KHL players and the teams they played for  
- Construct a player network graph based on shared team affiliations  
- Develop a proximity metric to quantify the degree of connection between players  
- Visualize the network structure using interactive graphs  
- Test hypotheses about player dynamics and league interconnectedness  

---

## Key Insights

As of 2023, the analysis found that any KHL player is connected to Lemtyugov through no more than **three degrees of separation**.  This highlights the surprisingly dense network within the league, demonstrating that the world of professional hockey is much more interconnected than it might appear.  This type of network-based modeling offers an innovative way to study athlete relationships and team structure in sports analytics.



## Sample Visual

> *(Screenshot of network graph)*

![Screenshot or GIF of network graph](https://github.com/diana-legrand/pet_projects/blob/main/hockey_project/network_graph.png)


## Tools & Libraries

- `pandas` – data preprocessing  
- `networkx` – graph construction and analysis  
- `plotly` – interactive network visualization  
- `matplotlib`, `seaborn` – supplementary plots  
- `scipy`, `pingouin` – statistical testing
