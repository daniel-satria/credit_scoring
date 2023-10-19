Credit Scoring with IV & WOE

# Scorecard Development Process

## Scorecard Development Process

**1. Explore data.**
- Simple statistics such as distributions of values, mean/median, etc.
- Checking data integrity.

**2. Handle missing values and outliers.**
- Most financial industry data contains missing values, or values that do not make sense for a particular characteristic

**3. Check correlation.**

**4. Initial characteristic analysis.**
- To assess the strength of each characteristic individually as a predictor of performance.

**5. Statistical Measures.**
- Weight of Evidence (WoE) — measures the strength of each attribute.
- Information Value (IV) — measures the total strength of the characteristic.

**6. Check logical trend.**
- Attribute strengths must also be in a logical order, and make operational sense.

**7. Check business/operational considerations.**
- The consideration is business or operational relevance. e.g. postal codes.

**8. Design scorecards.**
- Preliminary scorecard
- Reject inference — To make educated guesses about how rejected applicants would have performed if accepted.
- Final scorecard production

**9. Choose a scorecard — using a combination of statistical and business measures.**
- For example: misclassification, scorecard strength (KS, Chi-square, AIC, AUC), etc.

**10. Deployment.**
- Deploying the scorecard model into production.

