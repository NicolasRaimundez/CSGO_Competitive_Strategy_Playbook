# CS:GO Competitive Strategy Playbook

## Executive Summary
Counter-Strike: Global Offensive (CS:GO) is a tactical, round-based objective shooter that serves as a high-stakes **resource management simulation**. As one of my favorite games, I chose to analyze its data because it represents a perfect intersection of high-velocity telemetry and complex economic decision-making.

This playbook identifies three critical levers of competitive success: **Spatial Dominance**, **Early-Stage Momentum**, and **Resource Allocation**.

---

## 1. Geospatial Analysis: Tactical Intelligence
*Project Title: [Strategic Performance Analytics: CS:GO Tactical Intelligence]*

<p align="center">
<img src="Images/Heatmaps_CSGO.png" width="800" alt="Heatmaps_CSGO">
</p>

In this phase, I utilized event-level telemetry to map the "Winning Geometry" of the map **de_mirage**. By transforming raw engine coordinates into normalized 2D spatial data, I answered several key tactical questions:

* **Defensive Anchors:** Which specific coordinates yield the highest survival-to-kill ratio for Counter-Terrorists?
* **Objective Retention:** How does the optimal defensive perimeter shift for Terrorists once the bomb is active?
* **Asset Optimization:** Where are the highest ROI positions for the AWP (Sniper Rifle) compared to standard rifles?

**Key Finding:** Success on Mirage is driven by "Active Anchoring"—controlling access corridors (Window, Connector, Palace) rather than passive site defense.

---

## 2. Pistol Round Analysis: First-Mover Advantage

The Pistol Round is the primary driver of economic momentum. In this section, I will analyze the "Snowball Effect" of the initial round of each half.

* **The Question:** How strongly does winning the first round correlate with a 15-round half victory?
* **Planned Insights:** Analyzing weapon selection (Glock vs. USP-S) and utility impact during resource-constrained engagements.

---

## 3. Gunplay Economics: Resource ROI

CS:GO is unique because players must buy their tools. This section treats the game as a financial model to evaluate the "Cost of Victory."

* **The Question:** At what equipment-value threshold does a round become statistically "unwinnable"?
* **Planned Insights:** Identifying the most cost-efficient weapons (Damage-per-Dollar) and the impact of "Eco" vs. "Full Buy" rounds on win probability.

---

## Tech Stack & Methodology
* **Language:** Python (Pandas, NumPy)
* **Visualization:** Seaborn, Matplotlib (Spatial Heatmaps & KDE Plots)
* **Data Source:** [CS:GO Matchmaking Damage Dataset](https://www.kaggle.com/datasets/skihikingkevin/csgo-matchmaking-damage) (400k+ event logs)
* **Logic:** Minto Pyramid Principle (Situation-Complication-Question-Answer)
