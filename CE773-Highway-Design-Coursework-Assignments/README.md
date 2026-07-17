# CE 773 Coursework Assignments: Geometric Design and Analysis of High-Speed Roadways

**Course:** CE 773: Geometric Design and Analysis of High-Speed Roadways
**Programme:** M.Tech in Transportation Systems Engineering, IIT Bombay · Spring 2025

## Objective

To compile the four individual coursework assignments submitted for CE 773 into a single, faithfully
transcribed reference document, preserving each assignment's original questions, calculations, tables,
and figures.

## Brief Description

This repository combines four separate CE 773 assignments -- a smaller, more frequent kind of
deliverable than a term project -- into one document, organised as one section per assignment:

- **Assignment 1:** A case-study review of the geometric design concepts applied in the
  Agra--Lucknow Expressway project (greenfield alignment, complete streets, median/roadside safety,
  context-sensitive solutions, performance-based design, and related concepts). **This was a group
  submission, completed jointly with Shivam Singh (Roll No. 24M0552)**, as recorded on the original
  submission.
- **Assignment 2:** Estimation of the Average Daily Traffic (ADT) and 30th-hour design volume for a
  rural, median-divided, four-lane highway from 50 days of hourly traffic-count data, followed by a
  10-year Level of Service (LOS) forecast under IRC growth-rate assumptions, concluding that a 4-to-6
  lane capacity expansion is justified.
- **Assignment 3:** Development of the tangent cross-section of a four-lane expressway located in the
  high-rainfall North-East region of India, based on IRC/MoRTH design guidelines (carriageway, median,
  shoulder, service lane, camber, side slopes, and right-of-way).
- **Assignment 4:** A field-based geometric design and safety review of the H10 intersection on the IIT
  Bombay campus, covering conflict-point analysis, skew angle, sight-triangle evaluation, problem
  identification, and proposed design improvements. **This was a group submission, completed jointly
  with Karshan M. Kanjariya (24D0322), Irfan Ali (24D0314), Menbere Aklilu (24D0315), and Fred
  Ssemwogerere (24D0326)**, as recorded on the original submission's title page.

All content is transcribed faithfully from the original submissions -- the same figures, tables, and
numbers as submitted -- with no invented real-world framing beyond a short factual restatement of each
assignment's question.

## Methodology

- Reviewed the original PDF submissions for all four assignments, including visual reading of embedded
  charts, diagrams, and field photographs (not just text extraction).
- Transcribed each assignment's question, step-by-step solution/method, tables, and figures into LaTeX,
  preserving the original numbers exactly as submitted.
- Extracted chart and diagram figures (hourly-volume and traffic-histogram charts from Assignment 2,
  cross-section diagrams from Assignment 3, and conflict-diagram/field photographs from Assignment 4)
  as image files for inclusion in the compiled report.
- Merged the four original submission PDFs into a single reference PDF
  (`source_assignments_combined.pdf`) as a backup of the raw originals.

## Tools Used

LaTeX (pdflatex), `pdftotext`/`pdftoppm` (Poppler utilities) for source-PDF text and image extraction,
`pdfunite` for merging the original submission PDFs, and IRC/MoRTH design-standard references.

## Repository Structure

```
CE773-Highway-Design-Coursework-Assignments/
├── README.md
├── report.pdf                          # Final compiled report
├── source_assignments_combined.pdf      # Merged original submission PDFs (reference only)
├── images/                              # Figures used in the report
└── source/                              # LaTeX source
    ├── report.tex
    └── report_style.tex
```

## Report

📄 [View Full Report](report.pdf)
