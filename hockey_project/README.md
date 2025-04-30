# Network Analysis of KHL Hockey Players: Mapping Player Connectivity


> ⚠️ **Note:** Due to GitHub’s file size limitations (`"Sorry, this file is too big to display"`), the full interactive notebook is best viewed via [Nbviewer](https://nbviewer.org/github/diana-legrand/pet_projects/blob/main/hockey_project/network_analysis_hockey.ipynb) 

---

## Overview

This project explores player connections in the Kontinental Hockey League (KHL) by introducing the "Lemtyugov Number" - a custom proximity metric inspired by **Erdős and Bacon numbers**. It measures how closely a given player is connected to Nikolay Lemtyugov based on shared team history. The Lemtyugov Number is hockey’s version of the “six degrees of separation” concept, grounded in **graph theory**. It’s based on the idea that any two players in the KHL can be connected through a chain of teammates — with the number representing how many steps it takes to link them to Lemtyugov. This number captures the relational proximity between players and reveals how team composition and career movement shape the league's network.  Using **Python and NetworkX**, I modeled the player network as a graph, where nodes represent players and edges represent shared seasons on the same team. This approach enabled visualization of league-wide player connections, highlighting clusters, central players, and degrees of separation.

The concept builds on **social network theory** and quantifies **relational proximity within the league**. This project offers insight into the underlying structure of professional hockey networks, revealing how players are interconnected across teams and seasons.


## Objectives

- Collect and clean historical data on KHL players and the teams they played for  
- Construct a player network graph based on shared team affiliations  
- Develop a proximity metric to quantify the degree of connection between players  
- Visualize the network structure using interactive graphs  
- Test hypotheses about player dynamics and league interconnectedness  

---

## Key Insights

As of 2023, the analysis found that any KHL player is connected to Lemtyugov through no more than **three degrees of separation**.  This highlights the surprisingly dense network within the league, demonstrating that the world of professional hockey is much more interconnected than it might appear.  This type of network-based modeling offers a novel lens for exploring athlete relationships and team dynamics within sports analytics.


## Screenshot of network graph

![Screenshot or GIF of network graph](https://github.com/diana-legrand/pet_projects/blob/main/hockey_project/network_graph.png)


## Tools & Libraries

- `pandas` – data preprocessing  
- `networkx` – graph construction and analysis  
- `plotly` – interactive network visualization  
- `matplotlib`, `seaborn` – supplementary plots  
- `scipy`, `pingouin` – statistical testing
