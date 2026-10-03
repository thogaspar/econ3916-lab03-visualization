# econ3916-lab03-visualization
Econ 3916 Lab 03 - Honest vs. Misleading Visualizations
## Objective

To show how the same data can be drawn to mislead or to inform, and to practice building charts that stay honest.

## Methodology

- Recreated Anscombe's Quartet: four datasets with the same means, variances and correlation but completely different shapes.
- Computed a Lie Factor of 49 for a revenue chart with a truncated axis, then redesigned the chart honestly.
- Drew four versions of real average hourly earnings (FRED series AHETPI, deflated to 2020 dollars), each of which told a different story.
- Ran a four-step EDA checklist (structure, distributions, relationships, anomalies) on World Bank GDP data covering 262 economies (countries plus aggregates such as World) over 63 years.
- Built an interactive honest-chart toggler that shows a live Lie Factor.

## Key Findings

- Summary statistics alone can hide big differences. The four Anscombe datasets match on means, variances and correlation, yet look nothing alike once plotted.
- A truncated axis can distort a chart badly. The revenue chart had a Lie Factor of 49, and the redesigned version removed the distortion.
- Choices in how I drew the data changed the message. The same earnings series, deflated to 2020 dollars, produced four different stories depending on how I drew it.
- The EDA checklist gave me a repeatable order for looking at a new dataset: structure, distributions, relationships, then anomalies. The GDP data's mix of countries and aggregates is a reminder to check what each row represents before comparing them.
