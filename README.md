# Urban Sprawl Data Exploration

### Exploring the relationship between urban design, public health, and pedestrian safety

**Author:** Alex Pham  
**Project:** Engineering Illness and Inefficiency: The True Cost of Urban Sprawl  
**Tools:** R, R Markdown, ggplot2, statistical analysis, and data visualization

## About the Project

What if the way we design our cities influences how healthy and safe we are?

This question motivated my research into urban development and its relationship with public health and pedestrian safety.

Using R, I conducted an exploratory analysis of 10 major U.S. metropolitan areas, comparing car-centric cities such as Atlanta, Dallas, and Phoenix with more compact, transit-oriented cities.

My goal was to understand whether differences in urban design are associated with measurable differences in health and safety outcomes.

## Research Questions

- Do car-centric cities have higher obesity rates?
- Is public transit quality associated with pedestrian safety?
- How do income and education relate to these outcomes?
- What can these relationships tell us about urban planning and public policy?

## Data Sources

The project draws on publicly available data from:

- **CDC PLACES (2024):** Obesity rates
- **Smart Growth America, Dangerous by Design (2024):** Pedestrian fatalities
- **U.S. Census American Community Survey (2022):** Household income and educational attainment
- **AllTransit:** Public transportation performance scores

## Methods and Analysis

I used R to organize and visualize the data, compare city groups, and investigate relationships among variables.

The analysis includes:

- Comparative bar charts
- Scatterplots and linear trend lines
- Pearson correlation analysis
- Two-sample t-tests
- A correlation matrix
- A comparative dashboard

## Selected Findings

Within the 10 metropolitan areas examined:

- Car-centric cities had higher average obesity rates than the more compact cities in the sample.
- Average pedestrian fatality rates were approximately 2.64 versus 1.40 deaths per 100,000 people.
- Transit quality was negatively correlated with obesity rates (r = -0.51) and pedestrian fatality rates (r = -0.73).
- Income and educational attainment were also associated with health outcomes.

These findings describe relationships within a small, selected sample. They do not establish that urban design independently causes the observed differences.

## Limitations

This is an exploratory project, not a comprehensive national study.

The sample includes only 10 metropolitan areas, and some indicators use different geographic boundaries and reporting periods. The analysis identifies correlations but does not establish causation or fully control for confounding variables.

## Project Files

- **`index.html`** — The completed report, including visualizations and statistical results.
- **`index.Rmd`** — The R Markdown source file containing the analysis and code.

## Why I Built This

As an economics student, I'm interested in how decisions about infrastructure, resource allocation, and public policy shape everyday life.

This project gave me an opportunity to move beyond economic theory and work directly with data: asking questions, testing relationships, interpreting results, and communicating findings.

It also reinforced an important lesson: statistical evidence is useful not only for finding patterns, but also for recognizing the limits of what we can confidently conclude.

## Future Improvements

I would like to expand the sample, standardize geographic definitions, examine additional socioeconomic factors, and explore regression models to better understand these relationships.
