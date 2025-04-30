# 🏒 Network Analysis of KHL Hockey Players: Mapping Player Connectivity


> ⚠️ **Note:** Due to GitHub’s file size limitations (`"Sorry, this file is too big to display"`), the full interactive notebook is best viewed via [Nbviewer](https://nbviewer.org/github/diana-legrand/pet_projects/blob/main/hockey_project/network_analysis_hockey.ipynb) 

---

## 🔍 Overview

This project explores player connections in the Kontinental Hockey League (KHL) by introducing the "Lemtyugov Number" - a custom proximity metric inspired by **Erdős and Bacon numbers**. It measures how closely a given player is connected to Nikolay Lemtyugov based on shared team history. The Lemtyugov Number is hockey’s version of the “six degrees of separation” concept, grounded in **graph theory**. It’s based on the idea that any two players in the KHL can be connected through a chain of teammates — with the number representing how many steps it takes to link them to Lemtyugov. This number captures the relational proximity between players and reveals how team composition and career movement shape the league's network.  Using **Python and NetworkX**, I modeled the player network as a graph, where nodes represent players and edges represent shared seasons on the same team. This approach enabled visualization of league-wide player connections, highlighting clusters, central players, and degrees of separation.

The concept builds on **social network theory** and quantifies **relational proximity within the league**. This project offers insight into the underlying structure of professional hockey networks, revealing how players are interconnected across teams and seasons.


## 🎯 Objectives

- 📥 Collect and clean historical KHL player and team data
- 🧩 Build a graph-based network of players linked by shared team history
- 🔢 Define and compute the Lemtyugov Number for each player
- 📊 Visualize the player network using interactive and static graphs
- 🧪 Test hypotheses about network dynamics, player mobility, and league structure  
---

## 🔑 Key Insights

- As of 2023, any KHL player is connected to Nikolay Lemtyugov through no more than **three degrees of separation**.
- The network becomes denser over time, indicating growing player mobility and tighter interconnections.
- The distribution of Lemtyugov Numbers provides a quantitative view of centrality and reachability in the league.
- Players with more team changes tend to have lower Lemtyugov Numbers, meaning they are more central in the network.
- This network-based approach offers a powerful lens for understanding team strategy, player influence, and league cohesion in sports analytics.


## 🖼️ SExample Visualizations

![Screenshot or GIF of network graph](https://github.com/diana-legrand/pet_projects/blob/main/hockey_project/network_graph.png)


##🛠️ Tools & Libraries

- `pandas` – data preprocessing  
- `networkx` – graph construction and analysis  
- `plotly` – interactive network visualization  
- `matplotlib`, `seaborn` – supplementary plots  
- `scipy`, `pingouin` – statistical testing
