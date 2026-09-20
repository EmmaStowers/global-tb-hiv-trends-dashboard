# global-tb-hiv-trends-dashboard
Data visualization project analyzing global tuberculosis trends from 1990–2013, examining incidence, mortality, and the role of HIV co-infection across regions using WHO data. Includes exploratory analysis, six custom visualizations (choropleth, line, bar, dumbbell, dot plots), and a companion Tableau dashboard.

# Global Tuberculosis Trends from 1990 to 2013: Incidence, Mortality, and HIV Co-Infection

A data visualization project analyzing the global evolution of the tuberculosis (TB) burden between 1990 and 2013, examining regional disparities in incidence and mortality and the role of HIV co-infection in driving TB outcomes worldwide.

**Live Dashboard:** [View on Tableau Public](https://public.tableau.com/views/GlobalTuberculosisTrendsfrom1990to2013IncidenceMortalityandHIVCo-infection/GlobalTuberculosisTrendsfrom1990to2013IncidenceMortalityandHIVCo-infection?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

## Overview

This project uses WHO data spanning 24 years to explore how coordinated global health interventions — including the 1993 WHO emergency declaration and the rollout of the DOTS (Directly Observed Therapy) treatment framework — affected TB incidence and mortality across six global regions, and how the HIV epidemic complicated progress in the hardest-hit areas.

**Research questions:**
- How did TB incidence and mortality evolve globally and regionally between 1990 and 2013?
- What impact did major health policy interventions (e.g., the DOTS framework) have on outcomes?
- How did HIV co-infection influence TB incidence and mortality trends over this period?

## Data Source

**[Tuberculosis Burden by Country](https://public.tableau.com/app/sample-data/TB_Burden_Country.csv)** — World Health Organization
- 5,121 rows · 47 columns
- Country-level data on TB incidence, mortality, and case detection, 1990–2013

## Tools Used

- **Microsoft Excel** — data cleaning and preprocessing
- **Tableau Desktop** — visualization and dashboard design
- **Jupyter Notebook** — analysis write-up and documentation

## Methodology

The dataset required minimal preprocessing due to its consistent structure and standardized formatting. Exploratory analysis covered 5,120 records across 219 countries and territories, revealing significant regional disparities — from near-zero incidence in some countries to over 1,000 cases per 100,000 in others.

## Key Visualizations

| Visualization | Chart Type | Purpose |
|---|---|---|
| Global Progress Map | Choropleth map | Shows regional TB burden and its evolution over time |
| New TB Case Trends | Line chart | Highlights temporal trends and the impact of diagnostic improvements |
| Reductions in TB-Related Deaths | Line chart | Tracks the sharp mortality decline following the 1993 WHO emergency declaration |
| Closing the Case Detection Gap | Bar chart | Compares case detection before and after major health initiatives |
| Drastic Reductions in TB Deaths | Dumbbell plot | Visualizes 1990 vs. 2013 mortality change by region |
| HIV as a Driver of TB Deaths | Dot plot | Compares HIV-driven mortality across regions |
| HIV as a Driver of TB Incidence & Mortality | Line charts | Separates HIV-associated TB trends from overall TB trends |

*(See the full notebook for each visualization image and accompanying analysis.)*

## Key Findings

TB incidence remained relatively flat over the period studied, while mortality was cut roughly in half — with the steepest improvements occurring after 1993. Progress was uneven, however: HIV-driven TB incidence and mortality worked against overall gains, particularly in Sub-Saharan Africa and Southeast Asia, until expanded antiretroviral therapy access after the early 2000s helped bring HIV-associated TB deaths down significantly.

## Limitations

- The dataset covers only 1990–2013 and does not reflect more recent developments in TB control, evolving global health policy, or disruptions from more recent public health crises (e.g., COVID-19).
- Regional aggregation may mask country-level variation within each region.

## Files

- `Final_Project_Data_Visualization_Emma_Stowers.ipynb` — full written analysis with embedded visualizations
- Supporting image files referenced in the notebook (chart exports)

## Author

Emma Stowers — Data Science student, Georgia College & State University
