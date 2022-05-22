---
abstract: <b>Background</b> Burnout is a significant public health concern affecting more than half of the healthcare workforce; however, passive screening tools to detect burnout are lacking. We investigated the ability of machine learning (ML) techniques to identify burnout using passively collected electronic health record (EHR)-based audit log data. <br/> <b>Methods</b> Physician trainees participated in a longitudinal study where they completed monthly burnout surveys and provided access to their EHR-based audit logs. Using the monthly burnout scores as the target outcome, we trained ML models using combinations of features derived from audit log data-aggregate measures of clinical workload, time series-based temporal measures of EHR use, and the baseline burnout score. Five ML models were constructed to predict burnout as a continuous score -  penalized linear regression, support vector machine, neural network, random forest, and gradient boosting machine. <br/> <b>Results</b> 88 trainee physicians participated and completed 416 surveys; greater than10 million audit log actions were collected (Mean [Standard Deviation] = 25,691 [14,331] actions per month, per physician). The workload feature set predicted burnout score with a mean absolute error (MAE) of 0.602 (95% Confidence Interval (CI), 0.412-0.826), and was able to predict burnout status with an average AUROC of 0.595 (95% CI 0.355-0.808) and average accuracy 0.567 (95% CI 0.393-0.742). The temporal feature set had a similar performance, with MAE 0.596 (95% CI 0.391-0.826), and AUROC 0.581 (95% CI 0.343-0.790). The addition of the baseline burnout score to the workload features improved the model performance to a mean AUROC of 0.829 (95% CI 0.607-0.996) and mean accuracy of 0.781 (95% CI 0.587-0.936); however, this performance was not meaningfully different than using the baseline burnout score alone. <br/> <b>Conclusions</b>  Current findings illustrate the complexities of predicting burnout exclusively based on clinical work activities as captured in the EHR, highlighting its multi-factorial and individualized nature. Future prediction studies of burnout should account for individual factors (e.g., resilience, physiological measurements such as sleep) and associated system-level factors (e.g., leadership).
authors:
- Sunny Lou
- Hanyang Liu
- Benjamin Warner
- Derek Harford
- Chenyang Lu
- Thomas Kannampallil
date: "2022-02-05"
doi: "10.1016/j.jbi.2022.104015"
featured: True
image:
  caption: ''
  focal_point: ""
  preview_only: false
publication: "Journal of Biomedical Informatics"
publication_short: "*JBI*"
publication_types:
- "2"
publishDate: "2022"
slides: 
summary: Physician burnout is widespread, especially during the COVID-19 pandemic, and has serious consequences for the health of physicians and their patients. Burnout needs to be measured before it can be improved, but the current ways to measure burnout involve physicians filling out surveys, a request that engenders little enthusiasm. We set out to develop a model that could identify burnout in physicians from passively collected EHR log data. However, we ran into several challenges; our experiences are described in this manuscript.
tags:
- Burnout
- Audit Log
title: Predicting physician burnout using clinical activity logs - Model performance and lessons learned
url_code: 'https://github.com/sslou/publications/tree/main/2021_burnout_lmm'
url_dataset: ''
url_pdf: ""
url_poster: ''
url_project: ""
url_slides: ""
url_source: ''
url_video: ''
---


