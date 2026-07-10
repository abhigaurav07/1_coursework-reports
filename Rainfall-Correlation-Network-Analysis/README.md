# Network-Theoretic Analysis of Spatial Rainfall Correlation Structures Across India

**Course:** CE 605 — Applied Statistics
**Programme:** M.Tech in Transportation Systems Engineering, IIT Bombay · Autumn 2024

## Objective

To characterize the spatial dependence structure of Indian monsoon rainfall by modeling meteorological stations as a correlation-based network, and to quantify how connectivity and hub structure change as the correlation-significance threshold is varied.

## Brief Description

Long-term monthly rainfall records from 20 meteorological stations across India (1961–2014, 54 years) were used to construct pairwise correlation matrices. Stations were treated as network nodes, with edges drawn between station pairs whose rainfall correlation exceeded a chosen significance threshold, producing correlation-based adjacency graphs at three thresholds (0.2, 0.3, 0.5).

## Methodology

- Computed pairwise Pearson correlation coefficients between all station rainfall time series.
- Built adjacency graphs at three correlation thresholds to study network sparsification.
- Calculated degree centrality, clustering coefficient, global efficiency, and harmonic mean shortest-path length for each network.
- Identified hub stations and regional dependence clusters, and quantified the connectivity–specificity trade-off across thresholds (global efficiency fell from 0.45 to 0.36 as the threshold tightened).

## Tools Used

Python, NetworkX (complex network theory), statistical/correlation analysis, data visualization.

## Repository Structure

```
Rainfall-Correlation-Network-Analysis/
├── README.md
├── report.pdf          # Final report
├── images/              # Figures used in the report
└── source/              # LaTeX source
    ├── report.tex
    └── report_style.tex
```

## Report

📄 [View Full Report](report.pdf)
