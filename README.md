## Data visualisation
https://www.data-to-viz.com/#explore
https://www.data-to-viz.com/caveats.html
https://www.kdnuggets.com/2021/02/telling-great-data-story-visualization-decision-tree.html

One numeric variable (univariate):
*Histogram
*Density plot

One categorical variable:
*Barplot (seaborn = countplot)
*Pie/Doughnut charts (not recommended)

One Numeric + One Categorical:
*Scatter plots
*Distribution plots (box, violin, etc.)

Two numeric variables (bivariate):
One can be x, the other can be y allowing to visualize statistical relationship
*Scatterplots
*Regression plots

Several groups
*Facet grid
*Pair plots

Interactive graphs
*Plotly

## Brainstorming Ideas
1) Descriptive statistics
  - total number of different observators over time
  - total number of visitors over time


2) Temporal trends (with relative and not absolute numbers):
- daily, monthly, yearly trends?
- hour of observation: peak time?
- Start-end hour analysis. Mean duration of observation per month/year?

3) Species analysis
  - total number of observations (=individuals)
  - species frequency (the most frequently observed species?)
  - divide month by 3 (0-10, 10-20, 20-30)
  - Species abundance monthly (on the same graph?) yearly? (per species)
  - species diversity (ex: Shannon diversity per month/year)
  - species richness (nb ob species over time?) (local vs migrating species)
  - Which local species is mostly observed? How many consecutive days?
  - Number of individuals per migrating species group (solitary or social migration?) Per timestamp? What is the threshold?

4) Demographic analysis
- Age class (1 years old, older than 1 year, 2 years old, 3 years old, 4 years old, strict adult) and sex Distribution for each species
- Seasonal Changes: how age class and sex distribution change over the months/years
- maybe young red kites are migrating earlier in the year?

5) Weather/temperature
++ If we miss information about a temperature we can find this information with an API
- Relationship between weather and nb of individuals, species ...

6) Observators/visitors
- Investigate how the number of visitors and observators impacts the number of observations



7) Advanced statistical analysis
- Regression analysis: identify predictors of bird presence?
- Time Series: forecast future bird migration patterns based on historical/our data
