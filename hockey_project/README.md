# 🏒 Network Analysis of KHL Hockey Players: Mapping Player Connectivity
---
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/diana-legrand/pet_projects/blob/main/hockey_project/network_analysis_hockey_players.ipynb)

> ⚠️ **Note:** GitHub does **not render interactive Plotly graphs**.  
> 📎 **To view the full interactive notebook with all visualizations**, use **[Google Colab](https://colab.research.google.com/github/diana-legrand/pet_projects/blob/main/hockey_project/network_analysis_hockey_players.ipynb)**.

---

## 🔍 Overview

This project explores player connectivity in the **Kontinental Hockey League (KHL)** by introducing a custom proximity metric: the **Lemtyugov Number** — inspired by the *Erdős* and *Bacon* numbers. It quantifies how closely a player is connected to **Nikolay Lemtyugov**, based on shared team membership across seasons.

🏒 Think of it as hockey’s version of *six degrees of separation*, modeled through **graph theory**.  
Each player is a **node**, and a shared team season creates an **edge**. The Lemtyugov Number reflects the shortest path between a player and Lemtyugov through team-based connections.

The concept builds on **social network theory** and quantifies **relational proximity within the league**. This project applies **social network theory** to the world of hockey — offering a data-driven lens on how team composition, transfers, and career movement shape the league's structure.

---

## 🎯 Objectives

- 📂 Collect and clean historical KHL player and team data  
- 🔗 Construct a graph-based player network using shared team affiliations  
- 🧮 Compute the **Lemtyugov Number** for each player via shortest-path algorithms  
- 📊 Visualize the league-wide player graph, clusters, and connectivity  
- 🧪 Test hypotheses about player movement, league cohesion, and centrality

---

## 📌 Key Insights

- As of **2023**, every KHL player is connected to Lemtyugov by **three or fewer steps**  
- Over time, the network becomes **denser**, reflecting greater player movement and interconnectedness  
- Players with more team transitions tend to have **lower Lemtyugov Numbers**  
- The model reveals **hidden structures**, clusters, and central figures in the league

> 📈 This network-based approach provides a unique angle for analyzing **team strategy**, **player influence**, and **league structure** in sports analytics.

---


##  🖼️ Visual Examples

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

