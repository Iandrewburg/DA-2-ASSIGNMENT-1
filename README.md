# Wage Disparity Amongst Genders in the Health Practitioner Industry

## Data Overview:
- Analyzed occupation codes 3000-3540, focusing on health practitioners.
- Created variables: gender (numeric binary), weekly wages, log of wages.

## Descriptive Analysis:
- Wage distribution: Initially right skewed, normalized after log transformation.
- Earnings histogram by gender: Indicates higher average weekly earnings for males and a higher number of females in the sample.

## Unconditional Wage Gap Analysis:
- OLS regression model indicated a significant wage gap, with females earning lower wages (decrease of 0.132 in log wages, p < 0.01).
- Model's low R-Squared (0.8%) implies gender alone is not a comprehensive indicator of wage disparities.

## Impact of Education Levels:
- Analyzed BA, MA, Professional, and PhD degrees.
- Higher education correlated with increased weekly earnings.
- Males out-earned females across all education levels, but with overlapping ranges, indicating some uncertainty in the exact disparity.

## Regression Models Summary:
- Conducted 11 regression models, but will reflect on the last three here, which explore education levels, gender, and wages.
  - Model 10 (Females): Education level positively impacts log wages, explaining 13.8% of variance.
  - Model 11 (Males): Education level influences log wages (9.7% increase), professional degree significantly boosts wages.
  - Model 12 (Gender Interaction): Education increases wages by 9.7%, but gender wage gap (27.6%) not statistically significant. Overall, degrees do not significantly affect gender wage disparities.

## Predictive Modelling and Interpretation:
- Confidence intervals in predictive models indicate consistent higher earnings for males across all education levels.
- Professional degrees show the least overlap in gender earnings, suggesting a more pronounced disparity at this education level.

## Conclusion:
- Clear wage disparities exist between genders in the healthcare practitioner industry.
- Further research needed to explore other factors influencing this gap and to develop better predictive models.
- Levels of education were found to not significantly affect gender wage disparities.
