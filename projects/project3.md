---
layout: default
title: Statistical Inference and Behavioral Data Analysis in R
permalink: /projects/project3/
---

# Statistical Inference and Behavioral Data Analysis in R

## Project Overview

This project applies statistical inference techniques in R to investigate behavioral and psychological characteristics among university students.

Using survey-based data, two independent analyses were conducted:

- Student motivation analysis
- Personality trait prevalence analysis

The objective was to demonstrate how statistical methods can be used to draw conclusions about larger populations using sample data.

**Tools:** R, Statistical Inference, Hypothesis Testing

---

## Research Objective

The analysis focused on two research questions:

### Motivation Analysis

What proportion of Science and Technology students are intrinsically motivated?

### Personality Trait Analysis

Is the prevalence of psychopathic personality traits among university students higher than the reported prevalence in the general adult population?

Both analyses relied on statistical inference techniques to estimate population parameters and evaluate hypotheses.

---

## Analysis 1: Student Motivation

### Research Question

What proportion of Science and Technology students are intrinsically motivated?

### Methodology

Students were classified as intrinsically motivated when their intrinsic motivation score exceeded their extrinsic motivation score.

A confidence interval for a population proportion was constructed using sample data.

### Results

- Sample proportion: 60%
- Confidence level: 98%
- Confidence interval: 48.1% – 70.8%

### Key Insight

The analysis suggests that a majority of Science and Technology students are intrinsically motivated.

While sampling variability exists, the estimated interval indicates that intrinsic motivation is likely common within the broader student population.

---

## Analysis 2: Personality Trait Prevalence

### Research Question

Is the prevalence of psychopathic personality traits among university students higher than the rate reported in the general adult population?

### Methodology

A one-sample proportion hypothesis test was conducted.

Hypotheses:

**H₀:** p = 0.045

**Hₐ:** p > 0.045

The observed sample proportion was compared against the reported population benchmark of 4.5%.

### Results

- Sample proportion: 9.23%
- Population benchmark: 4.5%
- z-statistic: 4.51
- p-value: 3.29 × 10⁻⁶

### Key Insight

The prevalence of psychopathic personality traits observed in the student sample was significantly higher than the reported prevalence in the general population.

The extremely small p-value provides strong statistical evidence against the null hypothesis.

---

## Skills Demonstrated

Throughout this project, the following analytical skills were applied:

- Statistical Inference
- Confidence Interval Estimation
- Hypothesis Testing
- Population Proportion Analysis
- Research Design
- Data Interpretation
- R Programming
- Data Visualization

---

## Sample R Code

The analysis was performed in R using statistical functions for confidence interval estimation and hypothesis testing.

```r
# Confidence interval for population proportion

prop.test(
  x = pos,
  n = nrow(stonly),
  conf.level = 0.98,
  correct = FALSE
)

# One-sample proportion test

prop.test(
  x = psychopathy_count,
  n = sample_size,
  p = 0.045,
  alternative = "greater",
  correct = FALSE
)
```

Complete R code and analysis documentation are available on GitHub.

<!-- Replace with your actual GitHub link --> <a href="https://github.com/kristina-kang" target="_blank"> View Full Analysis on GitHub → </a>

---

## Conclusion

This project demonstrates how statistical inference can be used to draw meaningful conclusions from sample data and support evidence-based decision making.

By applying confidence interval estimation and hypothesis testing in R, the analysis transformed survey responses into interpretable insights about student motivation and behavioral characteristics.

<a href="/" class="back-button">← Back to Home</a>
