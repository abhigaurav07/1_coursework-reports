# Urban Transport Accessibility in India: A Comparative Study of PTAL Scores in Bangalore and Varanasi

**Course:** B.Tech Project (BTP)
**Programme:** B.Tech in Civil Engineering, IIT (BHU) Varanasi

## Objective

To adapt the London/TfL Public Transport Accessibility Level (PTAL) methodology to Indian data constraints and use it to compare public-transport accessibility patterns in Bangalore and Varanasi, two structurally different Indian cities.

## Brief Description

Grid-cell-level accessibility indices were computed for both cities using a 7-step walk-time/wait-time/frequency PTAL algorithm, then related to population distribution via regression to test whether accessibility and population density move together — and whether that relationship differs by city type.

## Methodology

- Adapted the PTAL methodology (walk time, wait time, service frequency) to Indian public-transport data constraints, computing grid-cell accessibility scores for both cities.
- Ran OLS regression to quantify the population–accessibility relationship per city.
- Found a statistically significant but divergent relationship: positive in Bangalore (p < 0.001), negative in Varanasi (p < 0.05).
- Produced GIS-mapped comparative accessibility scores and targeted policy recommendations (transit-oriented zoning, parking policy, infrastructure prioritization) for both cities.

## Tools Used

Python, OLS regression, GIS mapping, Public Transport Accessibility Level (PTAL) methodology.

## Repository Structure

```
Public-Transport-Accessibility-Analysis/
├── README.md
├── report.pdf          # Final report
├── images/              # Figures used in the report
└── source/              # LaTeX source
    ├── report.tex
    └── report_style.tex
```

## Report

📄 [View Full Report](report.pdf)
