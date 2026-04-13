# credit-risk-analysis-R
## Credit Risk Analysis with Loan Default Study

**Tools:** R · Propensity Score Matching (MatchIt) · OLS regression  
**Dataset:** 2,000 borrowers  

### Objective
Estimate the causal effect of liquidity on loan default amount,
controlling for selection bias.

### Methodology
- Propensity Score Matching to balance treatment/control groups
  (income, age, education, gender)
- Comparison of PSM estimates vs naïve OLS to measure selection bias

### Key finding
High liquidity reduces average default amount by €256 
vs €543 in naïve OLS, a 53% reduction in estimated effect 
after controlling for confounders.

