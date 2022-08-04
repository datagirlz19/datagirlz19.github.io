---
layout: post
title: ICU Admissions Rate
description: Research shows that ICUs can put people with chronic illnesses in worse conditions than when they entered. Though it may not be immediately apparent, some studies have shown that the ICU can have a negative effect on patients later. We want to see if this applies to the different conditions in this dataset.
summary: Does gender impact ICUs admission rates and the likelihood of re-admittance for individuals with different Chronic Illnesses?
tags: [tableau]
---


Completed by Luke Pritchard & Sarah Wright

![header](https://capsule-render.vercel.app/api?type=rect&color=gradient&height=1)

# Executive Summary 
#### I. Research Question 
1. We want to answer the question: Does gender impact ICUs admission rates and the likelihood of  re-admittance for individuals with different Chronic Illnesses? 

2. Research shows that ICUs can put people with chronic illnesses in worse conditions than when  they entered. Though it may not be immediately apparent, some studies have shown that the ICU  can have a negative effect on patients later, such as the findings of Zorio et al: “Increase in  mortality and in recurrent infections in the year following ICU discharge continues in survivors of  septic shock, even after total clinical recovery from the initial septic event and its complications.” 
3. Research also suggests that there are no gender readmittance differences for cardiac  arrhythmia, chronic obstructive airways disease, asthma, self-poisoning, and seizures. We want  to see if this applies to the different conditions in this dataset. 
#### II. Dataset, Variables, & Process 
1. Our dataset is from the WiDS Datathon, which uses data from Global Open-Source Severity of  Illness Score from MIT. The competition focused on Diabetes, but since there are over 100  variables, the information found here can be used to answer many questions.  
2. The chronic illnesses present in the dataset, and used in analysis, as well as other variables, are:  AIDS, Cirrhosis, Hepatic Failure, Immunosuppression, Leukemia, Lymphoma, Solid Tumor,  Diabetes, Birth Year, ICU Stay Type, & Gender. 
3. An additional binary variable, named “Chronic”, was made to denote if an individual had any one  of the chronic illnesses. 

#### III. Findings 
1. It seems to be more likely that a patient has a chronic condition if they are in the baby boomer  generation. This is shown in the first visualization.
2. We compared the admittance types to ICUs between those with chronic illnesses and those  without. Thought almost all people in the dataset were in the “admitted” category, meaning this is  their first time, those with chronic illnesses were readmitted at a noticeably higher rate. This is  demonstrated in Visualization 3. 
3. Having seen that having a chronic illness does in fact influence readmittance, we looked more  closely at each disease. Here, we compared the remittance rates of each disease for both men and  women. Generally, men are readmitted at higher rates than women, especially for AIDS,  Lymphoma, and Cirrhosis. This can be seen in Visualization 4. 
  * According to research by the NCBI, men are more likely to get Lymphoma and respond  worse to treatment when compared to women. 
  * According to IHME, 2/3 of those who die due to Cirrhosis are men. 
  * There are no women with AIDS in our dataset that are readmitted, and there are far more  men than women with AIDS.  

#### IV. Conclusion 
1. It appear that gender makes a difference in terms of readmittance, with men being readmitted  more often. For all chronic conditions here it makes some measure of difference, but for certain  ones, like AIDS, Cirrhosis, and Lymphoma there is a large difference. 
2. This information can be used by hospitals to better prepare themselves in terms of ICU capacity  depending on the types of patients they have.


![header](https://capsule-render.vercel.app/api?type=rect&color=gradient&height=1)

## Work Cited 
Raine, R. “Influence of Patient Gender on Admission to Intensive Care.” Journal of Epidemiology & Community  Health, vol. 56, no. 6, 1 June 2002, pp. 418–423, jech.bmj.com/content/56/6/418, 10.1136/jech.56.6.418.  Accessed 29 Mar. 2021. 
Son, Youn-Jung, et al. “Gender Differences in the Impact of Frailty on 90-Day Hospital Readmission in Heart  Failure Patients: A Retrospective Cohort Study.” European Journal of Cardiovascular Nursing, 6 Jan.  2021, academic.oup.com/eurjcn/advance-article/doi/10.1093/eurjcn/zvaa028/6066592,  10.1093/eurjcn/zvaa028. Accessed 29 Mar. 2021. 
Horesh, Nurit, and Netanel A. Horowitz. “Does Gender Matter in Non-Hodgkin Lymphoma? Differences in  Epidemiology, Clinical Behavior, and Therapy.” Rambam Maimonides Medical Journal, vol. 5, no. 4, 29  Oct. 2014, p. e0038, www.ncbi.nlm.nih.gov/pmc/articles/PMC4222427/, 10.5041/rmmj.10172. Accessed  29 Mar. 2021. 
“Men Twice as Likely as Women to Die of Liver Cirrhosis.” Institute for Health Metrics and Evaluation, 24 Jan.  2020, www.healthdata.org/news-release/men-twice-likely-women-die-liver-cirrhosis. Accessed 29 Mar.  2021. 
Horesh, Nurit, and Netanel A. Horowitz. “Does Gender Matter in Non-Hodgkin Lymphoma? Differences in  Epidemiology, Clinical Behavior, and Therapy.” Rambam Maimonides Medical Journal, vol. 5, no. 4, 29  Oct. 2014, p. e0038, www.ncbi.nlm.nih.gov/pmc/articles/PMC4222427/, 10.5041/rmmj.10172. Accessed  29 Mar. 2021. 
Zorio, Violette, et al. “Assessment of Sepsis-Induced Immunosuppression at ICU Discharge and 6 Months after  ICU Discharge.” Annals of Intensive Care, vol. 7, no. 1, 2 Aug. 
Lai, Chih-Cheng, et al. “Outcome of Liver Cirrhosis Patients Requiring Prolonged Mechanical Ventilation.”  Scientific Reports, vol. 10, no. 1, 18 Mar. 2020, , 10.1038/s41598-020-61601-2. Accessed 12 Mar. 2021. 
Vaz, A, et al. “Mortality in Patients with Cirrhosis Admitted to the ICU: Time to Rethink Strategies?” Critical  Care, vol. 19, no. Suppl 1, 2015, p. P385, https://ccforum.biomedcentral.com/articles/10.1186/cc14465 ,  10.1186/cc14465. Accessed 12 Mar. 2021.

# Presentation
![header](https://capsule-render.vercel.app/api?type=rect&color=gradient&height=1)
![0001](https://user-images.githubusercontent.com/45902684/182749061-9b9943d2-dd95-4a4d-b6a3-c695880edf9a.jpg)
![0002](https://user-images.githubusercontent.com/45902684/182749065-60281e25-6b98-48ca-acb0-028a3c8721dc.jpg)
![0003](https://user-images.githubusercontent.com/45902684/182749066-74006761-c08a-48e8-a55d-e22134e3b862.jpg)
![0004](https://user-images.githubusercontent.com/45902684/182749068-164a88dc-549d-4991-b9f5-281812a9fae9.jpg)
![0005](https://user-images.githubusercontent.com/45902684/182749070-93fb6775-b6ec-4e6e-a533-c999ea674a58.jpg)
![0006](https://user-images.githubusercontent.com/45902684/182749072-913b3d13-5650-42d7-973b-da71162efa09.jpg)
![0007](https://user-images.githubusercontent.com/45902684/182749073-4e891240-a407-4a67-b978-9125d80c19be.jpg)
![0008](https://user-images.githubusercontent.com/45902684/182749074-4ea58875-43f2-44e0-9e6b-ca67ce192107.jpg)


