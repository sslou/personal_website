---
abstract: <b>Background</b> Accurate estimation of surgical transfusion risk is essential for efficient allocation of blood bank resources and for other aspects of anesthetic planning. This study hypothesized that a machine learning model incorporating both surgery- and patient-specific variables would outperform the traditional approach that uses only procedure-specific information, allowing for more efficient allocation of preoperative type and screen orders. <br/> <b>Methods</b> The American College of Surgeons National Surgical Quality Improvement Program Participant Use File was used to train four machine learning models to predict the likelihood of red cell transfusion using surgery-specific and patient-specific variables. A baseline model using only procedure-specific information was created for comparison. The models were trained on surgical encounters that occurred at 722 hospitals in 2016 through 2018. The models were internally validated on surgical cases that occurred at 719 hospitals in 2019. Generalizability of the best-performing model was assessed by external validation on surgical cases occurring at a single institution in 2020. <br/> <b>Results</b> Transfusion prevalence was 2.4% (73,313 of 3,049,617), 2.2% (23,205 of 1,076,441), and 6.7% (1,104 of 16,053) across the training, internal validation, and external validation cohorts, respectively. The gradient boosting machine outperformed the baseline model and was the best- performing model. At a fixed 96% sensitivity, this model had a positive predictive value of 0.06 and 0.21 and recommended type and screens for 36% and 30% of the patients in internal and external validation, respectively. By comparison, the baseline model at the same sensitivity had a positive predictive value of 0.04 and 0.144 and recommended type and screens for 57% and 45% of the patients in internal and external validation, respectively. The most important predictor variables were overall procedure-specific transfusion rate and preoperative hematocrit. <br/> <b>Conclusions</b>  A personalized transfusion risk prediction model was created using both surgery- and patient-specific variables to guide preoperative type and screen orders and showed better performance compared to the traditional procedure-centric approach.
authors:
- Sunny Lou
- Hanyang Liu
- Chenyang Lu
- Troy Wildes
- Bruce Hall
- Thomas Kannampallil
date: "2022-02-11"
doi: "10.1097/ALN.0000000000004139"
featured: True
image:
  caption: ''
  focal_point: ""
  preview_only: false
publication: "Anesthesiology"
publication_short: "*Anesthesiology*"
publication_types:
- "2"
publishDate: "2022"
slides: 
summary: 20 million patients have surgery in the US every year, and ~ 1 million of those patients require life-saving blood transfusion. Presurgical preparation for transfusion is important to allow for safe and timely transfusion during surgery, but excessive preparation is unfortunately common, costly, and contributes to blood waste. In this paper, we develop a personalized surgical transfusion risk prediction model using a database of 3 million surgical patients, and show that using such a model to guide presurgical type and screen orders can potentially improve patient safety while reducing the number of unnecessary orders. Reproducible code is provided to make predictions for new patients.
tags:
- Anesthesia
- Patient Blood Management
title: Personalized Surgical Transfusion Risk Prediction Using Machine Learning to Guide Preoperative Type and Screen Orders
url_code: 'https://github.com/sslou/publications/tree/main/2021_blood_product'
url_dataset: ''
url_pdf: ""
url_poster: ''
url_project: ""
url_slides: ""
url_source: ''
url_video: ''
---


