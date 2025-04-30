# Network Analysis of KHL Hockey Players: Mapping Player Connectivity

Так как github не отображает визуализацию в plotly, рекомендуется смотреть проект через nbviewer по [ссылке](https://nbviewer.org/github/diana-legrand/pet_projects/blob/main/hockey_project/Diana_Legrand_Hockey_Project.ipynb).

> ⚠️ **Note:** Due to GitHub’s file size limitations (`"Sorry, this file is too big to display"`), the full interactive notebook is best viewed via **[Nbviewer]([https://nbviewer.org/your-notebook-link-here](https://nbviewer.org/github/diana-legrand/pet_projects/blob/main/hockey_project/Diana_Legrand_Hockey_Project.ipynb))**.

---

## Overview

This project explores player connectivity within the Kontinental Hockey League (KHL) using a graph-based approach. Inspired by the Erdős–Bacon number, it introduces a custom proximity metric to measure how closely any player is connected to Nikolai Lemtyugov through shared team history.

The goal is to understand how tightly knit the league is and to visualize how players are linked through their careers, even if they never played together directly.


## Вывод

Итак, в данном проекте было рассчитано число Лемтюгова - это своего рода аналог "шести рукопожатий" в мире хоккея, которое измеряет степень связи между хоккеистами в лиге КХЛ через команды, в которых они играли вместе с Николаем Лемтюговым. По состоянию на 2023 г., макисмальное число Лемтюгова - 3, то есть хоккеисты лиги КХЛ знакомы друг с другом максимум через 3 рукопожатия. Если максимальное число Лемтюгова равно 3, это означает, что два случайных хоккеиста в лиге КХЛ, даже если они никогда не играли в одной команде с Лемтюговым, могут быть связаны цепочкой общих команд через других хоккеистов, где каждый последующий хоккеист играл с кем-то, кто играл с Лемтюговым. Это интересная концепция, которая демонстрирует, как мир спорта может быть связан через относительно небольшое количество связей. Такие метрики помогают наглядно представить, насколько сильно переплетено хоккейное сообщество и как близки могут быть взаимоотношения между игроками.

## Objectives

- Collect and clean historical data on KHL players and the teams they played for  
- Construct a player network graph based on shared team affiliations  
- Develop a proximity metric to quantify the degree of connection between players  
- Visualize the network structure using interactive graphs  
- Test hypotheses about player dynamics and league interconnectedness  

---

## Key Insights

As of 2023, the analysis found that any KHL player is connected to Lemtyugov through no more than **three degrees of separation**.  
This highlights the surprisingly dense network within the league, demonstrating that the world of professional hockey is much more interconnected than it might appear.  

This type of network-based modeling offers an innovative way to study athlete relationships and team structure in sports analytics.

Также построен [интерактивный дашборд в Power BI](https://app.powerbi.com/view?r=eyJrIjoiNGI0OGU1M2YtOTFjYy00YjgzLWFhZmMtNWI3MGJkMWNjNWI0IiwidCI6IjFjZDhlNDFkLTEyYTctNDkzYi1iOTRhLTNkMWZkOWY1MDA5OSIsImMiOjEwfQ%3D%3D&embedImagePlaceholder=true) по проекту:

![Иллюстрация к проекту](https://github.com/diana-legrand/pet_projects/blob/main/hockey_project/hockey_dashboard_project_page-0001.jpg)

## How to View

GitHub cannot render large notebooks with Plotly visualizations. To view the interactive analysis, please use **Nbviewer**:

🔗 [View in Nbviewer](https://nbviewer.org/your-notebook-link-here)

---

## Sample Visual

> *(Screenshot or GIF of network graph)*
>


![Screenshot or GIF of network graph](https://github.com/diana-legrand/pet_projects/blob/main/hockey_project/hockey_dashboard_project_page-0001.jpg)





## Tools & Libraries

- `pandas` – data preprocessing  
- `networkx` – graph construction and analysis  
- `plotly` – interactive network visualization  
- `matplotlib`, `seaborn` – supplementary plots  
- `scipy`, `pingouin` – statistical testing
