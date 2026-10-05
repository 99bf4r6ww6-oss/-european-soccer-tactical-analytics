# European Soccer Tactical Analytics & Chance-Creation Modeling

**R | ggplot2 | Multiple Linear Regression | Interaction Modeling | R Markdown**

## Project Overview

This project analyzes tactical characteristics of European club soccer teams to understand how different styles of play are associated with chance-creation shooting.

Using **1,458 team observations across 10 tactical features**, I developed a multivariate regression framework examining build-up play, passing, crossing, positioning, and defensive strategies while accounting for interactions between tactical variables.

## Research Question

**Which tactical characteristics are most strongly associated with chance-creation shooting, and does the relationship between passing and shooting differ across tactical positioning styles?**

## Dataset

- **1,458 European club-team observations**
- **10 tactical features**
- Response variable: **Chance-Creation Shooting**
- Tactical dimensions include build-up play, passing, crossing, positioning, and defensive characteristics

## Methodology

The analysis follows a reproducible statistical workflow:

1. Explored distributions and relationships among tactical variables
2. Constructed a **multiple linear regression** model for chance-creation shooting
3. Evaluated tactical interactions, including **Passing × Positioning**
4. Estimated and interpreted model coefficients and confidence intervals
5. Assessed model assumptions using **residual diagnostics**
6. Investigated potentially influential observations

## Key Finding

The analysis identified a statistically significant **Passing × Positioning interaction (p < .001)**.

The estimated association between passing and chance-creation shooting was approximately **12× stronger for Free Form teams than for Organised teams**.

This suggests that the relationship between passing and attacking behavior depends substantially on a team's positioning strategy—an effect that would be obscured by interpreting only the aggregate passing coefficient.

## Model Validation

Model reliability was evaluated using:

- Residual diagnostic plots
- Confidence intervals
- Influential-point analysis
- Assessment of regression assumptions

These diagnostics were used to distinguish interpretable tactical relationships from patterns that could be driven by model misspecification or individual observations.

## Tools & Techniques

- **R** — statistical analysis and modeling
- **ggplot2** — exploratory and model visualization
- **Multiple Linear Regression** — multivariable tactical modeling
- **Interaction Modeling** — tactical heterogeneity analysis
- **R Markdown** — reproducible analysis and reporting

## Repository Structure

```text
european-soccer-tactical-analytics/
├── README.md
├── analysis/
├── data/
├── figures/
└── results/
