# Coursework Reports

A curated collection of coursework, project, and seminar reports completed during my **B.Tech in Civil Engineering (IIT (BHU) Varanasi)** and **M.Tech in Transportation Systems Engineering (IIT Bombay)**. The repository spans transportation planning, traffic engineering, geometric road design, project economics, GIS/remote sensing, and applied machine learning.

Each project is self-contained: a compiled report, the figures used in it, and the full LaTeX source needed to reproduce it.

## Purpose

This repository serves as a portfolio of academic and analytical work, organized for easy review by recruiters, collaborators, and reviewers. It documents the methods, tools, and findings behind each report in a consistent, reproducible format.

## Technologies & Software Used

- **Programming & Analysis:** Python (NetworkX, scikit-learn, SHAP, OLS regression/statsmodels)
- **GIS & Remote Sensing:** ArcGIS, Landsat imagery, supervised classification
- **Transportation Engineering:** PTV VISSIM (microsimulation), AutoCAD Civil 3D, IRC design standards
- **Project Economics:** Cost-Benefit Analysis (EIRR, NPV, BCR)
- **Documentation:** LaTeX

## Projects

| Project | Course | Tools | Report |
|---|---|---|---|
| [Rainfall Correlation Network Analysis](Rainfall-Correlation-Network-Analysis/) | CE 605: Applied Statistics | Python, NetworkX, Statistical Analysis | [report.pdf](Rainfall-Correlation-Network-Analysis/report.pdf) |
| [Geometric Design of Bypass Road](Geometric-Design-of-Bypass-Road/) | CE 773: Geometric Design and Analysis of High-Speed Roadways | AutoCAD Civil 3D, IRC Standards, DEM | [report.pdf](Geometric-Design-of-Bypass-Road/report.pdf) |
| [Unsignalized Junction Sensitivity Analysis](Unsignalized-Junction-Sensitivity-Analysis/) | CE 774: Traffic Management and Design | PTV VISSIM, Microsimulation, HCM/IRC LOS | [report.pdf](Unsignalized-Junction-Sensitivity-Analysis/report.pdf) |
| [Delhi Metro Economic Evaluation](Delhi-Metro-Economic-Evaluation/) | CE 776: Transportation Project Evaluation and Decision Making | Cost-Benefit Analysis, EIRR, NPV, BCR | [report.pdf](Delhi-Metro-Economic-Evaluation/report.pdf) |
| [Thane Station Mobility Ecology](Thane-Station-Mobility-Ecology/) | PS 651: Mobility Policy and Infrastructure | Qualitative Field Research, Systems Analysis | [report.pdf](Thane-Station-Mobility-Ecology/report.pdf) |
| [Land Use Land Cover Change Analysis](Land-Use-Land-Cover-Change-Analysis/) | B.Tech Exploratory Project | ArcGIS, Landsat, Remote Sensing | [report.pdf](Land-Use-Land-Cover-Change-Analysis/report.pdf) |
| [Public Transport Accessibility Analysis](Public-Transport-Accessibility-Analysis/) | B.Tech Project (BTP) | Python, OLS Regression, GIS, PTAL Methodology | [report.pdf](Public-Transport-Accessibility-Analysis/report.pdf) |
| [Demand-Responsive Transit: Machine Learning](Demand-Responsive-Transit-Machine-Learning/) | CE 694: Credit Seminar | Python, Random Forest, ANN, DNN, SHAP | [report.pdf](Demand-Responsive-Transit-Machine-Learning/report.pdf) |
| [CE 773 Highway Design Coursework Assignments](CE773-Highway-Design-Coursework-Assignments/) | CE 773: Geometric Design and Analysis of High-Speed Roadways | AutoCAD/Field Study, IRC/MoRTH Standards, LaTeX | [report.pdf](CE773-Highway-Design-Coursework-Assignments/report.pdf) |

## Repository Structure

```
coursework-reports/
├── README.md
├── assets/
│   └── iitb_logo.png          # shared institutional logo used on report title pages
└── <Project-Name>/
    ├── README.md               # project-specific summary
    ├── report.pdf              # compiled report
    ├── images/                 # figures used in the report
    └── source/                 # LaTeX source (compile with: cd source && pdflatex report.tex)
        ├── report.tex
        └── report_style.tex
```

## Author

**Abhijeet Kumar Gaurav**
- M.Tech, Transportation Systems Engineering, Indian Institute of Technology Bombay (2024-2026)
- B.Tech, Civil Engineering, Indian Institute of Technology (BHU) Varanasi (2020-2024)
