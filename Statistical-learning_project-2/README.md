# Statistical Learning

This machine learning project was part of the [Statistical Learning](https://studiegids.universiteitleiden.nl/en/courses/122141/statistical-learning) module.
<br>
The project's goal is to predict and understand the factors contributing to the depressive severity score over time.
<br>
<br>
This project achieved **near-perfect grades** for both the report and code.

## AI explains factors leading to depression

<img src="../img/sl_2_ctree.png" width=75%, alt = "Algorithm Preview">

- **Please open:**
  - [Project report (PDF)](https://github.com/ValentinK214/leiden_public/blob/main/Statistical-learning_project-2/report.pdf) - main file
  - [Bonus question (code)](https://github.com/ValentinK214/leiden_public/blob/main/Statistical-learning_project-2/report.pdf)

- **Description:**
  - Choose 3 machine learning models
  - Balance ease of interpretation, predictive power and statistical robustness
  - Justify your choices
  - For detailed information, see the [assignment questions](https://github.com/ValentinK214/leiden_public/blob/main/Statistical-learning_project-2/Q4_bonus_code_as_it_takes_super_long.Rmd). 


- **Achievements:**
  - Received **near-perfect grades** for both the report and code
  - Correctly interpreted model outputs and explained factors leading to depressive severity 
  -  Fitted a highly predctive model correctly
  - Showcased deep understanding of the model selection process
  - Successfully compared all models using advanced statistical simulations
  - Ran all machine learning models effectively in R

- **Key Learnings (Technical) :**
    - **Model Selection Process**: For supervised learning consider:
        - Dataset dimensionality and noise
        - Goal of the analysis: Interpretability, statistical inference, predictive power
        - Selecting both low and high bias models for a balanced analysis
    - **Model parameters**: Only tune a limited number of model parameters that you actually understand to avoid overfit
    - **Bootstrapping**: To analysise the pairwise difference in predctive performance between models use a bootstrap confidence interval 
    - **No perfect model**: A model that predicts exceptionally well is usually not easy to interpret, good for inference and vice versa
    - **Model interpretation**: Consider all outputs from both your primary analysis and your secondary analysis for a well rounded conclusion
    - **R Libraries**: Learned how to fit a conditional inference tree, generalised additive model and a boosted ensemble model.

- **Interesting Sections from the Report**
    - Q1: Model selection
    - Q4: Advanced simulation
    - Q5: Results
    - Q6: Individual prediction
