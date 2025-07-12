# 🏏 IPL 2025 Data-Driven Dream Squad Project

## 📄 Overview

This project showcases a fully **data-driven approach** to building an IPL 2025 dream squad.  
Instead of relying on historical reputation or big names, this squad was created purely using **player impact scores, auction prices, and role balance**, all backed by advanced data analysis and custom algorithms.

---

## 📂 Repository Contents

### 📁 Datasets

#### ✅ Raw Scraped Datasets

- `bowling_stats.csv` — Detailed bowling statistics scraped and processed
- `ipl_player_stats.csv` — Overall performance and season-wise stats for each player
- `ipl_player_data.csv` — Additional metadata about players (type, team, matches, etc.)
- `ipl_2025_auction_players.csv` — Auction dataset with player sold prices for 2025

#### ✅ Final Dataset

- `final_dataset.csv` — Fully cleaned and merged dataset containing all players with their auction price, type, impact score, performance, and other attributes

---

### 🐍 Python Scripts

- `merge_datasets.py` — Script to merge and clean all scraped datasets into one final unified dataset
- `top_15_selection.py` — Script to select top 15 players based on user-defined role requirements and budget constraints
- `squad_algo.py` — Flexible algorithm to generate customizable squads by specifying exact player counts (batsmen, bowlers, ARs) and budget splits

> ⚡ All scripts also export an **HTML version** for easy sharing or presentation.

---

### 📊 Dashboard

- `IPL_2025_Dashboard.pbix` — Interactive Power BI dashboard (5 pages), covering squad overview, budget analysis, batsmen analysis, all-rounders analysis, and bowlers analysis
- `IPL_2025_Dashboard.pdf` — Static PDF export of the dashboard for offline viewing or slides

---

### 🖼️ Visuals

- `final_squad.jpg` — High-quality poster of the final 15-player data-driven squad, suitable for social media or presentations

---

## 💡 Key Features

- Fully **user-customizable** squad creation logic
- Detailed **impact vs price analysis** for each role
- Visual breakdown: batsmen, all-rounders, bowlers
- Strict budget and overseas player constraints
- Professionally designed Power BI dashboard for presenting insights
- Real-life IPL 2025 auction data incorporated
- Ready for sharing or showcasing to recruiters, sports analytics enthusiasts, or cricket communities

---

## ⚡ How to Run

1️⃣ Clone this repository.  
2️⃣ Run scripts in order:
