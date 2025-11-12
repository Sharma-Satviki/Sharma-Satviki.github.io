---
layout: default
title: IS445 – Building Inventory Visualization
---

# 🏛️ Building Inventory Visualization
**Satviki Sharma**  
MSIM, University of Illinois Urbana–Champaign  

---

## Visualization 1 — Building Size vs Construction Year (by Agency)

This visualization explores the relationship between when a building was constructed and its total size, segmented by the agency responsible for it. Each point represents one building; color encodes the agency name. The y-axis uses a log scale to handle large variations in square footage. The data was cleaned by removing missing or zero values and ensuring valid construction years. This visualization shows that some agencies, such as the Department of Transportation or Natural Resources, tend to maintain newer or larger facilities.

![Scatter Plot](chart1.png)

---

## Visualization 2 — Interactive Floor Area Distribution by Usage and Decade

The second visualization introduces interactivity with a decade selector that filters the data dynamically. The histogram displays the distribution of building floor areas (on a log scale) across different usage categories for the selected decade. This allows users to explore temporal patterns — for instance, educational and administrative buildings might have expanded significantly in the 2000s. Consistent color usage across categories ensures clarity and comparability.

![Histogram](chart2.png)

**Interactivity Discussion:**  
The dropdown makes it easier to analyze how state building characteristics have evolved over time without overwhelming the viewer with multiple static plots. Users can focus on a single decade to identify trends in construction scale and usage type, making the visualization both intuitive and engaging.

---

## 🔗 Links

- [**The Data**](https://raw.githubusercontent.com/UIUC-iSchool-DataViz/is445_data/main/building_inventory.csv)  
- [**The Analysis (Notebook)**](https://github.com/Sharma-Satviki/Sharma-Satviki.github.io/blob/main/is445_building_inventory_viz/building_inventory_analysis.ipynb)

---

[⬅ Back to Home](../index.html)
