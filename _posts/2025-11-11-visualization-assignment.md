---
layout: post
title: "Altair Visualizations: Licenses Dataset"
---

## Visualization 1 – Licenses by Type
<iframe src="/assets/plot1.html" width="700" height="500"></iframe>

**Description:**  
This bar chart shows how many licenses were issued for each type during Fall 2022.  
The *x-axis* encodes License Type and the *y-axis* encodes the count of licenses.  
Each color represents a different license type, making comparison easy.  
No data transformations were required because the dataset was already clean.

---

## Visualization 2 – Interactive Licenses by State
<iframe src="/assets/plot2.html" width="700" height="500"></iframe>

**Description:**  
This interactive bar chart lets users select a state from a dropdown and view how many licenses it holds.  
The *x-axis* shows states, the *y-axis* shows license counts, and color encodes each state consistently.  
The interactivity helps viewers focus on one state at a time, keeping the visualization clear and engaging.

---

### Interactivity Discussion
I used a dropdown menu instead of hover or zoom to allow a focused, uncluttered view.  
This interaction makes the visualization dynamic and highlights geographic variation effectively.

---

### Links
- [The Data](https://raw.githubusercontent.com/UIUC-iSchool-DataViz/is445_data/main/licenses_fall2022.csv)  
- [The Analysis Notebook](https://github.com/AnvekshaPandey/AnvekshaPandey.github.io/blob/main/plot_assignment.ipynb)
