# Econometric Analysis of Asylum Seekers Destination Choices

This repository contains an applied econometrics project developed in **R** for the module **Bi-disciplinary Project** during my Double Bachelor's Degree in Economics and Mathematics at **University Paris-Saclay**. 

The study shows the bilateral determinants of the destination choices made by asylum seekers in Europe between 2010 and 2016, using a gravity model

 **Grades obtained :**
* **Econometrics module grade :** 17/20
* **Bi-disciplinary project grade :** 16,5/20


[📖 Click here to read the full report in french (PDF)](https://github.com/mehdi-belhamiti/Asylum-Seekers-Econometrics/blob/main/Projet%20demandes%20d%E2%80%99asile%20-%20E%CC%81conome%CC%81trie.pdf)

[📊 Click here to read the presentation in french (PDF)](https://github.com/mehdi-belhamiti/Asylum-Seekers-Econometrics/blob/main/Diapos_soutenance.pdf)

[▶️ Click here to watch our video hook (Youtube Video)](https://youtu.be/VAQV0KUcWC0)

We had an oral with a jury and our class, including a presentation of the results and an question-and-answer session.

This project was done to highlight the differences between the information given by the media and to compare the figures we have on refugees in Europe.

## Project Overview
Why does an asylum seeker choose one country over another? This project evaluates various "push" and "pull" factors using a dyadic dataset (origin x destination x year) with over 39,000 observations.

<img width="1646" height="872" alt="image" src="https://github.com/user-attachments/assets/d3495ed7-69e0-42f5-b740-6408b109ef16" />

<img width="1515" height="950" alt="image" src="https://github.com/user-attachments/assets/3b1bdd12-eb3a-498b-ab1e-72c3ba80d645" />


### Methodology :
* **Gravity Model** : Estimation using high-dimensional fixed effects on Origin, Destination, and Year to control for unobserved multilateral resistance

<img width="1879" height="190" alt="image" src="https://github.com/user-attachments/assets/82e8d705-7dfa-479f-b03d-83f96a0d067f" />

* **Variables** : Diaspora size, geographic distance, common language, colonial ties, GDP per capita, HDI, and a custom Political Instability Index.
* **Robustness** : Clustered standard errors, multicollinearity checks, and residual analysis.

<img width="1327" height="627" alt="image" src="https://github.com/user-attachments/assets/33ce5e9d-d2c5-40ea-ba38-1b882894b606" />

* **Limits** : We used a Multiple Linear Regression Model, which might not be as efficient for this situation. Endogeneity, Selection Bias

### Key Findings :

<img width="1145" height="895" alt="image" src="https://github.com/user-attachments/assets/00c5bc8d-8111-4386-aea3-24d3b7eecfbf" />

<img width="1140" height="596" alt="image" src="https://github.com/user-attachments/assets/66da5c15-102c-4b3d-b89a-a36b051c2139" />

<img width="1290" height="818" alt="image" src="https://github.com/user-attachments/assets/91e21395-fe39-41a8-a2ca-888206233968" />

* **Push Factor** : Political repression and lack of freedom in the origin country are strong drivers of exile.
* **Pull Factor** : The pre-existing **diaspora network** is the most robust determinant of the chosen destination, strongly amplified by a shared common language
* **Non-significant Factors** : Once networks and fixed effects are controlled for, geographic distance and economic wealth (GDP and HDI) do not significantly dictate the final destination. It was unexpected because we can see in some medias that refugees come in Europe for economic reasons.

##  Technologies and Libraries
* **R**
* `fixest`, `feols`
* `tidyverse`, `ggplot2`
* `modelsummary`, `corrplot`
