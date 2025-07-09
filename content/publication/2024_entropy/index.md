---
abstract: <b>Objective</b> To develop and validate a novel measure, action entropy, for assessing the cognitive effort associated with electronic health record (EHR)-based work activities. <br/> <b>Methods</b> EHR-based audit logs of attending physicians and advanced practice providers (APPs) from four surgical intensive care units in 2019 were included. Neural language models (LMs) were trained and validated separately for attendings’ and APPs’ action sequences. Action entropy was calculated as the cross-entropy associated with the predicted probability of the next action, based on prior actions. To validate the measure, a matched pairs study was conducted to assess the difference in action entropy during known high cognitive effort scenarios, namely, attention switching between patients and to or from the EHR inbox. <br/> <b>Results</b> Sixty-five clinicians performing 5 904 429 EHR-based audit log actions on 8956 unique patients were included. All attention switching scenarios were associated with a higher action entropy compared to non-switching scenarios, except for the from-inbox switching scenario among APPs. The highest difference among attendings was for the from-inbox attention switching. Action entropy was 1.288 (95% CI, 1.256-1.320) standard deviations (SDs) higher for switching compared to non-switching scenarios. For APPs, the highest difference was for the to-inbox switching, where action entropy was 2.354 (95% CI, 2.311-2.397) SDs higher for switching compared to non-switching scenarios. <br/> <b>Conclusions</b>  We developed a LM-based metric, action entropy, for assessing cognitive burden associated with EHR-based actions. The metric showed discriminant validity and statistical significance when evaluated against known situations of high cognitive effort (ie, attention switching). With additional validation, this metric can potentially be used as a screening tool for assessing behavioral action phenotypes that are associated with higher cognitive burden.
author_notes:
-
-
-
- co-senior author
- co-senior author
authors:
- Seunghwan Kim
- Ben Warner
- Daphne Lew
- Sunny Lou
- Thomas Kannampallil
date: "2024-10-01"
doi: "10.1093/jamia/ocae171"
featured: False
image:
  caption: ''
  focal_point: ""
  preview_only: false
publication: "Journal of the American Medical Informatics Association"
publication_short: "*JAMIA*"
publication_types:
- "2"
publishDate: "2024"
slides: 
summary: Many studies have suggested that higher cognitive burden is associated with increased burnout and risk for errors. However, it has been challenging to measure the cognitive load associated with clinician work within the electronic health record. Here we developed a novel scalable method to measure cognitive load using audit log data and demonstrate its validity.
tags:
- Audit Log
- Machine Learning
title: Measuring cognitive effort using tabular transformer-based language models of electronic health record-based audit log action sequences
url_code: 'https://github.com/bcwarner/audit-log-lm'
url_dataset: ''
url_pdf: ""
url_poster: ''
url_project: ""
url_slides: ""
url_source: ''
url_video: ''
---


