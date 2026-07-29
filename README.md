# A/B Testing Eniac Website Analysis

## Project Overview

This project analyzes an A/B test conducted for **Eniac**, an online retailer, to determine whether redesigning the homepage call-to-action button increases user engagement.

The marketing team wanted to improve the click-through rate (CTR) of the homepage's **SHOP NOW** button. Four different button versions were tested using a randomized controlled experiment.

---

## Business Problem

The homepage button achieved only a **2% Click-Through Rate (CTR)** despite being prominently displayed.

The UX team proposed several design changes to improve engagement:

| Version | Description |
|---------|-------------|
| A | Original white "SHOP NOW" button |
| B | Red "SHOP NOW" button |
| C | White "SEE DEALS" button |
| D | Red "SEE DEALS" button |

The objective was to determine whether any design significantly increased user interaction while maintaining user engagement throughout the purchasing process.

---

## Objectives

- Compare the CTR across four website versions.
- Determine whether observed differences are statistically significant.
- Identify the best-performing design.
- Evaluate additional behavioral metrics.
- Provide data-driven recommendations for implementation.

---

## Experimental Design

### Random Assignment

Visitors were randomly assigned to one of the four website versions.

Randomization ensured:

- unbiased allocation
- comparable user groups
- valid statistical inference
- consistent user experience using cookies/user IDs

---

## Success Metrics

### Primary Metric

- Click-Through Rate (CTR)

CTR = Clicks / Total Visits

This metric measures how effectively each button encourages users to click.

### Secondary Metrics

- Drop-off Rate
- Homepage Return Rate
- Purchase Conversion Rate
- Revenue per Visit

These metrics ensure that increased clicks also translate into meaningful business outcomes.

---

## Statistical Hypotheses

### Null Hypothesis (H₀)

All button versions have the same Click-Through Rate.

### Alternative Hypothesis (H₁)

At least one button version has a different Click-Through Rate.

---

## Statistical Methods

The analysis includes:

- Exploratory Data Analysis (EDA)
- CTR calculations
- Chi-Square Test of Independence
- Post-hoc pairwise Chi-Square comparisons
- Bonferroni correction
- Business interpretation of results

Python libraries used:

- pandas
- numpy
- scipy
- matplotlib
- seaborn

---

## Results

The analysis found statistically significant differences among the button variants.

Key findings include:

- White buttons consistently outperformed red buttons.
- Changing the button text to **"SEE DEALS"** improved engagement.
- The overall Chi-Square test rejected the null hypothesis.
- Pairwise post-hoc tests identified which variants differed significantly after Bonferroni correction.

Secondary metrics were also evaluated before making a final recommendation.

---

## Business Recommendation

Based on statistical significance and user behavior metrics, Eniac can confidently implement the highest-performing variant while continuing to monitor downstream conversion metrics.

The project demonstrates how experimental design and statistical hypothesis testing support evidence-based product decisions.

---

Data Analytics Bootcamp Project
