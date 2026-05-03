# Final-Data-Mining-Project
# Clinical Diagnostic Intelligence and Fairness
UNC Charlotte ITSC 3162 Team Documentation

## Project Overview
This project focuses on building a heart disease prediction pipeline using KNIME. Our primary objective was to move beyond global accuracy and address gender based diagnostic fairness. By identifying a recall gap in female patients we implemented fairness corrected strategies to ensure equitable clinical outcomes.

## Technical Achievements
* Improved female recall to point eight seven nine
* Built a parallel stream KNIME workflow for cohort specific optimizations
* Successfully insulated the target variable during normalization to prevent data leakage

## The Pipeline
* Data Cleaning: Median imputation for clinical outliers
* Preprocessing: Target insulated normalization and one to many encoding
* Modeling: Parallel Naive Bayes learners for male and female cohorts
* Correction Strategies: SMOTE for synthetic oversampling and a Rule Engine for threshold adjustments


## Contribution Log
* Week Two: Set up GitHub and initial data audit
* Week Three: Implemented median imputation and normalization
* Week Four: Baseline model setup and performance scoring
* Week Five: Integrated SMOTE and Rule Engine thresholding
* Week Six: Final report drafting and workflow documentation

## Repository Structure
* Data: UCI Heart Disease dataset
* Workflow: Final knwf file, along with previous editions of file

## Key Findings
This project showed that achieving ethical healthcare models requires intentional trade-offs. We prioritized recall to ensure no patient is left undiagnosed even if it means managing a higher rate of false positives. We learned that as analysts we must actively hunt for disparities in the data before they become part of the model.
