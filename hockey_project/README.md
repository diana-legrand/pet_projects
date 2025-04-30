# 🏒 Network Analysis of KHL Hockey Players: Mapping Player Connectivity


> ⚠️📎  **Note:** GitHub does not render interactive Plotly graphs, so the full interactive notebook is best viewed via [Google Colab](https://colab.research.google.com/drive/1vEyEzPKXookbTDMtaztF4XVjmXQgRVho?usp=sharing)

---

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/diana-legrand/pet_projects/blob/main/hockey_project/network_analysis_hockey_players.ipynb)

> ⚠️ **Note:** GitHub does **not render interactive Plotly graphs**.  
> 📎 **To view the full interactive notebook with all visualizations**, use **[Google Colab](https://colab.research.google.com/github/diana-legrand/pet_projects/blob/main/hockey_project/network_analysis_hockey_players.ipynb)**.

## 🔍 Overview

This project explores player connectivity in the Kontinental Hockey League (KHL) by introducing the Lemtyugov Number — a custom proximity metric inspired by the **Erdős and Bacon numbers**. It quantifies how closely a given player is connected to Nikolay Lemtyugov, based on shared seasons on the same team.

Think of it as hockey’s version of six degrees of separation modeled using **graph theory**. The network is built by treating each player as a node, and drawing edges between players who were teammates in overlapping time periods. The Lemtyugov Number is then computed using shortest-path algorithms to reveal how many "handshakes" connect any player to Lemtyugov.

The concept builds on **social network theory** and quantifies **relational proximity within the league**. This model sheds light on how career paths, team composition, and transfers shape connectivity across the league. It's a novel application of social network theory to professional hockey.


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


## 🖼️ Sample Visualizations

![Screenshot or GIF of network graph](https://github.com/diana-legrand/pet_projects/blob/main/hockey_project/network_graph.png)


## 🛠️ Tools & Libraries

- `pandas` – data preprocessing  
- `networkx` – graph construction and analysis  
- `plotly` – interactive network visualization  
- `matplotlib`, `seaborn` – supplementary plots  
- `scipy`, `pingouin` – statistical testing

---

## 📁 Project Files

```
📂 hockey_project/
├── network_analysis_hockey_players.ipynb    ← ✅ Main notebook
├── players_data.csv                         ← 📊 Cleaned dataset of player records
├── network_graph.png                         ← 🌐 Static image of network graph
├── hockey_dashboard_project_page-0001.jpg    ← 📸 Dashboard preview
└── README.md                                 ← 📄 This file
```

---

