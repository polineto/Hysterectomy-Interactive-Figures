# Interactive Supplementary Figures
## Hysterectomy Trends and Disparities in Brazil (2008–2024)

> **Associated manuscript:** *Temporal trends, regional disparities, and socioeconomic determinants of hysterectomy in the Brazilian public health system, 2008–2024*
> Submitted to *The Lancet Regional Health – Americas*

---

## Overview

This repository contains five interactive HTML visualisations that supplement the figures and analyses presented in the manuscript. They allow readers, reviewers, and policymakers to explore the data at greater depth than is possible in static figures — including state-level drill-down, year-by-year navigation, and dynamic axis selection.

All figures are self-contained HTML files. No installation, software, or internet connection is required to view them: simply open the file in any modern web browser (Chrome, Firefox, Edge, or Safari).

---

## Repository Structure

```
.
├── README.md                          ← this file
├── interactive_figures_legend.md      ← full captions for all interactive figures
└── Figures/
    ├── figure_1_interactive.html      ← Interactive Figure I1 — Surgical approach
    ├── figure_2_interactive.html      ← Interactive Figure I2 — Patient travel flows
    ├── figure_3_interactive.html      ← Interactive Figure I3 — Evolution of age-standardised hysterectomy rates
    ├── figure_4_interactive.html      ← Interactive Figure I4 — Correlation with socioeconomic determinants
    └── figure_5_interactive.html      ← Interactive Figure I5 — Transition between surgical rate clusters

```

---

## Interactive Figures at a Glance

| Figure    | Title                                                           | Complements       |
|-----------|-----------------------------------------------------------------|-------------------|
| [I1](#i1) | Surgical approach — state-level explorer                        | Figure 2          |
| [I2](#i2) | Patient travel flows and hubs                                   | Figure 4          |
| [I3](#i3) | Spatiotemporal evolution of age-standardised hysterectomy rates | Figures 3, S5, S6 |
| [I4](#i4) | Socioeconomic determinants — correlation explorer               | Figure 5          |
| [I5](#i5) | State cluster transitions — pre- to post-pandemic Sankey        | Main text         |

---

## Figure Descriptions

### I1
**Interactive Figure I1 — Surgical approach: state-level explorer**

Stacked bar charts showing the annual distribution of surgical routes (abdominal, vaginal, and laparoscopic) for hysterectomy across Brazilian states, 2008–2024. Users can select individual states from the dropdown menu to display local trends alongside national benchmarks, including a national aggregate ("All Brazil"). Data are derived from the SIH/SUS hospital admissions database. Complements Figure 2.

---

### I2
**Interactive Figure I2 — Patient travel flows between the municipality of residence and the hospital**

Origin–destination flow map of patient travel for hysterectomy procedures, stratified by year and macro-region of residence, Brazil, 2008–2024. Only patients travelling ≥ 50 km are shown. Lines connect the municipality of residence (origin) to the municipality of the treating hospital (destination); line thickness and opacity reflect flow intensity, quantified as the number of procedures sharing the same origin–destination pair and grouped into up to four quantile-based bins. Use the dropdown menu to navigate across years. Complements Figure 4 and the travel distance analysis.

---

### I3
**Interactive Figure I3 — Spatiotemporal evolution of age-standardised hysterectomy rates by region**

Interactive choropleth map illustrating regional surgical rates across Brazil, 2008-2024. The dropdown menu allows users to select data for specific years. Colour intensity represents the age-standardised rate per 100,000 women. Interactive hovers provide region-specific rates. Complements the longitudinal data presented in the main text and Supplementary Figures S5 and S6.

---

### I4
**Interactive Figure I4 — Socioeconomic determinants of hysterectomy rate and surgical technicity: an interactive correlation explorer**

Scatter plots displaying state–year observations for hysterectomy rate (per 100,000 SUS-dependent women) and technicity index — defined as the proportion of hysterectomies performed via minimally invasive approaches (laparoscopic or vaginal route) — against a user-selected socioeconomic indicator. The x-axis can be toggled across multiple dimensions of the Human Development Index (overall HDI, education, longevity, and income subindices), gender-specific variants, and the Gini coefficient. Each selection updates the Spearman ρ, corresponding p-value, and LOWESS smoother in real time. Complements Figure 5.

---

### I5
**Interactive Figure I5 — State cluster transitions from pre-pandemic to post-pandemic: a Sankey visualisation**

Sankey diagram showing how Brazilian states transitioned among surgical rate clusters (High, Intermediate, and Low) from the pre-pandemic era through the post-pandemic recovery period. Interactive hovers provide state-specific rates. Complements the spatiotemporal trends described in the main text.

---

## How to Use

1. **Download** the repository (click *Code → Download ZIP* or clone with `git clone`).
2. **Open** any `.html` file in your browser — no server or installation needed.
3. **Interact** using the controls described in each figure caption above (dropdowns, sliders, toggles).

> For the best experience, use a recent version of Chrome or Firefox on a desktop or laptop screen. Mobile browsers are supported but some figures are optimised for wider viewports.

---

## Data Sources

All data are drawn from:

- **SIH/SUS** (Sistema de Informações Hospitalares do SUS) — hospital admission records, Ministry of Health, Brazil, 2008–2024
- **IBGE** — Brazilian population estimates by state, sex, and age group
- **ANS** (Agência Nacional de Saúde Suplementar) — private health insurance coverage estimates
- **PNUD/Atlas Brasil** — Human Development Index and subindices by state

Raw data are publicly available at [datasus.saude.gov.br](http://datasus.saude.gov.br) and [atlasbrasil.org.br](http://atlasbrasil.org.br). Analysis code will be made available upon reasonable request to the corresponding author.

---

## Citation

If you use these visualisations, please cite the associated manuscript:

> **[Author names].** Hysterectomy for non-malignant conditions in the Brazilian Public Health System, 2008-2024: a nationwide population-based study of trends, technicity and socioeconomic disparities. *The Lancet Regional Health – Americas* (under review). DOI: [to be assigned upon publication]

---

## Licence

These supplementary materials are shared under the Creative Commons Attribution-NoDerivatives 4.0 International (CC BY-ND 4.0) licence. You are free to share and redistribute the materials in any medium or format, provided appropriate credit is given. Modification or adaptation of these materials is not permitted.

---

## Contact

For questions regarding the interactive figures or the underlying data, please contact the corresponding author via the journal submission system or open an issue in this repository.
