# Growth Mindset: Myth or Reality? - Causal Inference Statistical Analysis

## Project Overview

Conducted comprehensive statistical analysis to investigate whether intellectual ability can be improved through targeted interventions, challenging the traditional belief that intelligence is fixed at birth. Used advanced causal inference methods on large-scale educational data spanning 10,000 students across 76 schools.

## Research Methodology

#### Causal Framework: 
Implemented rigorous identification strategy based on three key assumptions: Consistency, No Unmeasured Confounding, and Positivity to ensure valid causal interpretation.

#### Statistical Techniques:
- Dual estimation approach using Plug-in estimator and Augmented Inverse-Probability-Weighted (AIPW) method
- Propensity score modeling via logistic regression
- Covariate balance assessment and love plot analysis
- Comprehensive descriptive statistics and correlation analysis
  
## Data Analysis

Analyzed multi-level dataset incorporating student-level variables (self-reported scores, race, gender, first-generation status) and school-level factors (urban setting, mindset scores, test performance, poverty levels, school size). Achieved excellent covariate balance with standardized mean differences near zero post-adjustment.

## Key Results

#### Average Treatment Effect:
- Plug-in estimate: 0.412
- AIPW estimate: 0.414 (doubly robust)
- 95% Confidence Interval: [0.382, 0.446]
  
#### Statistical Significance: 
Results demonstrate nudge-like interventions significantly improve student achievement, with confidence interval entirely above zero indicating robust positive effect.

#### Validation: 
Propensity scores ranged [0.18, 0.45] with no positivity violations. Treatment and control groups showed comparable distributions across all covariates.

## Implications & Impact

Provides strong statistical evidence supporting growth mindset theory - intelligence can be meaningfully enhanced through targeted educational interventions. Findings have important implications for educational policy, teaching methods, and student development strategies.

## Technical Skills Demonstrated

Advanced causal inference, propensity score methods, doubly robust estimation, covariate balancing, statistical hypothesis testing, and large-scale educational data analysis.

