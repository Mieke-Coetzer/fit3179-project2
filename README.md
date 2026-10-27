# The Inescapable Screen: From a Global Wave to Australian Daily Life

**Live Webpage:** (https://mieke-coetzer.github.io/fit3179-project2/)
**Author:** Mieke Coetzer  
**Date:** October 2026  
**Course:** FIT3179 - Data Visualisation 
**Topic Domain:** Digital Communication & Society  

---

## Project Abstract & Overview
*The Inescapable Screen* is an interactive web-based data visualisation dashboard designed for an Australian audience[cite: 11]. The project investigates how digital communication transitioned over the past three decades from an occasional household privilege to an always-on utility. 

By tracking our transition from desktop computers to mobile-first habits, examining distinct generational preferences, and evaluating the split between workplace productivity and personal lifestyle apps, this dashboard maps how screens became an inescapable foundation of modern Australian life[cite: 1, 2].

The story is structured across four logical sections:
1. **Section 1: The Global Wave of Digital Adoption** — Visualises global internet growth velocity (1990–2025), sequential Dorling cartograms, an interactive global choropleth explorer, and a regional adoption intensity heatmap[cite: 1, 3].
2. **Section 2: Zooming in on Australia** — Focuses on local Australian connectivity, comparing metropolitan vs. regional digital divides, regional application adoption, and primary device rank shifts (desktop to mobile) over time[cite: 1, 2].
3. **Section 3: Generational Patterns & Communication Preferences** — Examines how communication portfolio breadth and daily frequency vary across age cohorts (from Gen Z digital natives to 65+ seniors) through bubble scatter plots, interactive multi-series frequency trends, and platform preference breakdowns[cite: 1, 2, 4].
4. **Section 4: Digital Communication Ecosystem & Impact Dimensions** — Contrasts personal lifestyle engagement against professional productivity using an activity density bubble plot and a 5-axis dual-domain radar chart comparing productivity, personal connection, and privacy/security concerns[cite: 1, 2, 4].

---

## Repository Structure

All visualisation specifications are created using **Vega-Lite v5** (and embedded Chart.js for the radar chart) and formatted for human readability within this repository:

```text
├── index.html                  # Main single-page scrollable web deliverable
├── style.css                   # Custom CSS styling, responsive grid alignment, and watermarks
├── chart4_radar.html           # Standalone HTML/Chart.js 5-axis polygon radar chart
├── image0.png                  # Desktop communication hub cartoon graphic
├── image1.png                  # Communication envelope bubble graphic
├── input_file_2.png            # Global globe bubble graphic
├── input_file_3.png            # User profile bubble graphic
├── js/                         # JavaScript and Vega-Lite JSON specifications
│   ├── chart1_continents.vg.json
│   ├── dorling1990.vg.json
│   ├── dorling2005.vg.json
│   ├── dorling2012.vg.json
│   ├── map_interactive.vg.json
│   ├── chart1_heat.vg.json
│   ├── map_divide.vg.json
│   ├── chart2_divide.vg.json
│   ├── chart2_rank.vg.json
│   ├── chart3_circles.vg.json
│   ├── chart3_multi.vg.json
│   ├── chart3_histogram.vg.json
│   ├── chart3_bar.vg.json
│   ├── chart4_circles.vg.json
│   └── chart4_3.vg.json
└── data/                       # Datasets and TopoJSON files
    ├── internet_users.csv
    ├── communication_habits.csv
    ├── trends_and_developments.csv
    ├── Digital_Commun._Networks_vs_Security_Privacy_comparison.csv
    └── chart4_2_dual_radar.csv
