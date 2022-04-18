# Short-Term Influences on Personality

This project is associated with the Experiments and Causal Inference Course through UC Berkeley's Master of Information & Data Science (MIDS) program. For this project, my group and I designed and implemented a surey experiment with a placebo design on Qualtrics to measure the sensitivity of [Five-Factor Personality Test](https://openpsychometrics.org/tests/IPIP-BFFM/) results to short-term influences from external stimuli.

In our experiment, we exposed a treatment group to a short video that we thought would elicit negative emotions. After watching this video, our respondents completed a 50-question personality test. The Five-Factor Personality Test determines an individual's level of agreeableness, extraversion, neuroticism, conscientiousness, and openness. Our experiment found that our treatment video had a statistically significant (⍺=0.01) impact for our 504 survey respondents on three factors: agreeableness, extraversion, and neuroticism. Each of these factors had a significantly lower value in our treatment group than control group.

## Repo Structure

This repo includes:
1. Our final report as an R markdown file and PDF: final_report.Rmd, final_report.pdf
2. Our raw and cleaned data: full_data.csv, W241_Survey_Results_Clean.csv
3. Code to convert our raw data to cleaned data: survey_data_clean_final.Rmd
4. Additional scratch work, including EDA and Power Analysis: initial_work_JC.Rmd, initial_work_TJ.Rmd, power analysis.R


## Tools & Skills
- R: ggplot2, linear regression for causal analysis
- Experiment design: randomization, placebo design, covariate identification and balance checks, survey experiment creation with Qualtrics, survey experiment deployment with Lucid Theorem
- Statistics: power analysis, hypothesis testing, Bonferroni corrections
- R markdown files, LaTeX

## Team Members
Alphabetically by last name: Jenny Conde, Trevor Johnson, Allison Rozich, Allison Schlissel, Andy Tertzakian
