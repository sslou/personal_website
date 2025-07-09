---
abstract: <b>Background</b> Accurate estimation of surgical transfusion risk is important for perioperative planning and effective resource allocation. Most machine learning models in health care are not validated or perform poorly in external settings. To externally validate a publicly available machine learning algorithm [(Surgical Personalized Anticipation of Transfusion Hazard [S-PATH])](https://doi.org/10.1097/ALN.0000000000004139) to estimate red cell transfusion during surgery within a national sample of hospitals. <br/> <b>Methods</b> This retrospective cohort study evaluated all surgical cases performed in 2020 or 2021 at 45 US hospitals participating in the Multicenter Perioperative Outcomes Group. Obstetric and nonoperative cases were excluded. Data analysis was performed from February 2023 to March 2025. At each hospital, S-PATH was used to estimate surgical transfusion risk using patient- and procedure-specific characteristics without local retraining. A baseline model representing the standard-of-care maximum surgical blood ordering schedule (MSBOS) approach, which omits patient factors, was used for comparison. Risk thresholds above which a type and screen would be recommended were set for 96% sensitivity. Performance was evaluated at each hospital separately. The primary outcome was the difference in the percentage of patients with type and screen order recommendations between S-PATH and MSBOS at each hospital. The secondary outcome was area under the receiver operating characteristic curve (AUROC).<br/> <b>Results</b> In this cohort study of 3 275 956 surgical cases (median [IQR] age, 57 [40-69] years; 53.1% female) performed at 45 hospitals (28 of 45 academic [62.2%]), S-PATH recommended type and screen orders for a median (IQR) of 32.5% (25.8%-42.0%) of cases, whereas the MSBOS approach recommended type and screens for a median (IQR) of 51.6% (46.9%-61.1%) of cases for the same sensitivity (median [IQR] difference, 17.9 [14.8-24.9] absolute percentage points). The median (IQR) S-PATH AUROC was 0.929 (0.915-0.946), whereas the median (IQR) MSBOS AUROC was 0.857 (0.822-0.884). <br/> <b>Conclusions</b>  In this cohort study of 45 hospitals, a personalized surgical transfusion risk prediction algorithm demonstrated external validity and discrimination. S-PATH was consistently more effective than standard care, suggesting its potential for use as a perioperative clinical decision support tool.
authors:
- Sunny Lou
- Sayantan Kumar
- Charles Goss
- Michael Avidan
- Sachin Kheterpal
- Thomas Kannampallil
date: "2025-06-02"
doi: "10.1001/jamanetworkopen.2025.17760"
featured: True
image:
  caption: ''
  focal_point: ""
  preview_only: false
publication: "JAMA Network Open"
publication_short: "*JAMA Network Open*"
publication_types:
- "2"
publishDate: "2025"
slides: 
summary: We previously developed a personalized AI model to predict surgical transfusion risk. Here we simulated using it for preop T&S decisions at 45 US hospitals. Our model (S-PATH) did better than the standard of care approach (MSBOS). We also measured performance using a clinically meaningful benchmark, the number of T&S ordered. S-PATH needed ~ 1/3 fewer while maintaining 96% sensitivity for finding patients who need blood. Importantly, we used S-PATH out of the box. No retraining or fine tuning on individual hospitals. Nonetheless, it still performed well. This kind of robustness is rare among AI models, and suggests S-PATH could be immediately useful for many hospital systems.
tags:
- Anesthesia
- Patient Blood Management
- Machine Learning
title: Multicenter Validation of a Machine Learning Model for Surgical Transfusion Risk at 45 US Hospitals
url_code: 'https://github.com/sslou/publications/tree/main/2021_blood_product'
url_dataset: ''
url_pdf: ""
url_poster: ''
url_project: ""
url_slides: ""
url_source: ''
url_video: ''
---


