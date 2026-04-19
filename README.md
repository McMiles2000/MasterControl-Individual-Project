# MasterControl-Individual-Project
# MasterControl Sales Analytics Portfolio

## Overview

This repository showcases my individual analytics work completed as part of an MSBA capstone project with **MasterControl**, a B2B SaaS company focused on quality and manufacturing software solutions.

The project centered on a key commercial challenge: **why manufacturing-related qualified leads were underperforming compared with quality-related leads, and how sales teams could better prioritize opportunities most likely to progress.**

My work focused on exploratory analysis, lead progression modeling, threshold evaluation, and business-facing visualizations that translated statistical results into practical sales recommendations.

---

## Business Problem

MasterControl generates a large volume of qualified account leads across two major solution areas:

- **Qx (Quality)** — a more established product area
- **Mx (Manufacturing)** — a newer and lower-performing product area

A central business question was:

> How can MasterControl better identify which leads are most likely to progress, especially within Mx, so that sales resources can be focused where they will have the greatest impact?

Without a data-driven approach, sales teams risk spending time on lower-value opportunities, missing high-potential accounts, and reinforcing the performance gap between Qx and Mx.

---

## My Role and Contributions

This repository reflects my **individual contribution** to the broader team project. My work included:

- Framing the business problem in a way that connected analytics to sales execution
- Conducting exploratory data analysis on lead, account, and contact-level variables
- Investigating progression gaps across solution areas, industries, and other segments
- Building and interpreting predictive models, especially logistic and LASSO-based approaches
- Evaluating classification thresholds beyond the default 0.50 cutoff
- Creating business-ready visuals for gains, confusion matrices, and sensitivity/specificity tradeoffs
- Translating modeling results into practical recommendations for lead prioritization

---

## Analytical Approach

My individual workflow followed a structured analytics process:

1. **Business understanding**
   - Clarified the commercial objective and progression outcome of interest
   - Focused the analysis on lead prioritization and Mx underperformance

2. **Exploratory data analysis**
   - Profiled lead progression patterns across solutions and customer/account dimensions
   - Assessed class imbalance and missingness across categorical predictors
   - Identified differences between Qx and Mx progression rates

3. **Predictive modeling**
   - Built baseline classification models to estimate lead progression likelihood
   - Used regularized logistic regression (LASSO) to improve interpretability and feature selection
   - Compared model behavior through ROC/AUC and threshold-based performance metrics

4. **Decision support analysis**
   - Evaluated confusion matrices at multiple thresholds
   - Examined tradeoffs between sensitivity, specificity, precision, and capture rate
   - Created gains-style views to show how many conversions could be captured by targeting top-ranked leads

---

## Key Insights

A few of the main takeaways from my work were:

- **Mx leads progressed at a meaningfully lower rate than Qx leads**, confirming the core business concern.
- The default classification threshold of **0.50 was too conservative** for this business setting because it captured too few true progressing leads.
- Lower thresholds improved the share of actual progressing leads identified, which is often more useful in a sales prioritization context.
- A ranked lead scoring approach was more actionable than a simple yes/no prediction because it allowed the business to target the highest-probability opportunities first.
- Segment-level exploration suggested that some industries, account characteristics, and contact roles were more aligned with successful progression than others.

---

## Business Value

This work supports a more efficient and targeted go-to-market strategy by helping MasterControl:

- prioritize higher-probability leads
- improve sales resource allocation
- better understand where Mx underperforms relative to Qx
- move from intuition-based lead handling toward data-informed decision making
- use threshold selection as a business decision rather than relying on a default modeling convention

In practice, this kind of workflow can help sales leaders decide not only **who to target**, but also **how aggressively to target leads based on capacity and business objectives**.

---

## Tools and Methods

- **R**
- **Quarto**
- **tidyverse**
- **caret**
- **glmnet**
- **ggplot2**
- Classification modeling
- ROC/AUC evaluation
- Threshold optimization
- Confusion matrix analysis
- Business-facing data visualization

---

## Repository Contents

- `notebooks/` — my individual Quarto notebooks and analysis files
- `outputs/` — rendered outputs for selected notebooks
- `images/` — visuals used in the project and README
- `data/` — placeholder only; no confidential project data are included

---

## Notes on Data Confidentiality

The underlying project data were provided for academic use and are **not included** in this repository.  
All code and documentation are shared for portfolio purposes without exposing confidential business data.

---

## Interview Talking Points

If discussing this project in an interview, I would highlight:

- how I translated a broad business problem into a measurable analytics objective
- how I handled an imbalanced classification problem in a business context
- why threshold selection matters just as much as model accuracy
- how I turned model output into a lead prioritization framework
- how I communicated technical findings through clear visuals and business recommendations

---

## Author

**Miles McCunniff**  
MS in Business Analytics  
University of Utah
