# Evaluating the Impact of Over Speeding & Alcohol Consumption on Road Accidents

This project explores how over-speeding and alcohol consumption contribute to road traffic accidents in India. Using panel data collected from 36 states over the span of 8 years (2015–2022), we aimed to understand the statistical relationship between these factors and overall accident rates. The study uses econometric methods to draw policy-relevant conclusions that could help improve road safety enforcement in the country.

Tools Used
EViews – for panel data regression and statistical modeling

Microsoft Excel – for data cleaning, transformation, and structuring,

SPSS


Data Source – Official government data from data.gov.in

Methodology
We began by gathering and organizing accident-related data at the state level. After cleaning and converting the data into a balanced panel format, we defined our variables:
Dependent Variable: Total number of reported road accidents (TOTAL)
Independent Variables: Number of accidents due to over-speeding (OVERSPEED) and due to alcohol consumption (ALCOHOL)
We applied several regression models to evaluate the impact of these two factors:

Pooled OLS
Fixed Effects Model (FEM)
Random Effects Model (REM)

To decide between FEM and REM, we used the Hausman Test, which confirmed that FEM was the more suitable model for our dataset. We also performed diagnostics to check for issues like autocorrelation and heteroskedasticity.

Model Equation
Basic Linear Form:
TOTAL = β₀ + β₁ * OVERSPEED + β₂ * ALCOHOL + ε

TOTAL = total number of road accidents
OVERSPEED = number of accidents caused by speeding

ALCOHOL = number of accidents caused by alcohol

β₀ = starting value (when speeding and alcohol accidents are zero)

β₁ = how much TOTAL increases when speeding accidents increase

β₂ = how much TOTAL increases when alcohol accidents increase

ε = other random factors not included in the model

Summary of Findings
Our final regression model, based on the Fixed Effects approach, showed that over-speeding has a statistically significant impact on the total number of accidents. Alcohol-related accidents also showed a positive relationship, but the effect was not statistically significant in this particular specification.

The model explained a large portion of the variation in accident data, with an Adjusted R² of 0.875. This suggests that over-speeding is a key area of concern and should be a major focus in policy interventions aimed at improving road safety.

