# Final-Data-Mining-Project
Project for ITCS 3162
This project focuses on building a Data-to-Decision pipeline for heart disease prediction using KNIME. Our primary objective was to move beyond global accuracy and address Gender-Based Diagnostic Fairness. By identifying a significant recall gap in female patients, we implemented fairness-corrected strategies to ensure equitable clinical outcomes.
Key Technical Achievements
  Fairness Optimization: Improved Female Recall from 0.667 to 0.879.
  Pipeline Infrastructure: Built a parallel-stream KNIME workflow to optimize cohort-specific models.
  Leakage Prevention: Successfully insulated the target variable during normalization and restricted correlation analysis to training data.
