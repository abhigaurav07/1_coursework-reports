# Land Use Land Cover Change in Singrauli District

**Course:** B.Tech Exploratory Project, Civil Engineering
**Programme:** B.Tech in Civil Engineering, IIT (BHU) Varanasi

## Objective

To quantify land use / land cover (LULC) change in the Singrauli coalfield region over a 15-year period, and to link observed change to coal-mining expansion and environmental impact.

## Brief Description

Multi-temporal Landsat 5/8 satellite imagery spanning 2006-2021 was classified using supervised (maximum-likelihood) classification in ArcGIS across an 11,285 km² coalfield region, producing a time series of land-cover maps used to track deforestation and vegetation change.

## Methodology

- Acquired and pre-processed multi-temporal Landsat 5/8 imagery (band composition, composites) for four time points: 2006, 2011, 2016, and 2021.
- Generated training samples and performed supervised maximum-likelihood classification into six land-cover classes.
- Computed class-wise area statistics for each time point to quantify change.
- Found a 13.4-point decline in dense forest cover and a 28.7-point rise in vegetation/agricultural land, linked to coal-mining expansion. This produced a reproducible remote-sensing workflow for environmental change monitoring.

## Tools Used

ArcGIS 10.0, Landsat 5/8 imagery, remote sensing, supervised (maximum-likelihood) classification.

## Repository Structure

```
Land-Use-Land-Cover-Change-Analysis/
├── README.md
├── report.pdf          # Final report
├── images/              # Figures used in the report
└── source/              # LaTeX source
    ├── report.tex
    └── report_style.tex
```

## Report

📄 [View Full Report](report.pdf)
