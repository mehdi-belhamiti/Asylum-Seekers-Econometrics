# Econometric Analysis of Asylum Seekers Destination Choices 🌍

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


### Methodology :
* **Gravity Model** : Estimation using high-dimensional fixed effects on Origin, Destination, and Year to control for unobserved multilateral resistance
* **Variables** : Diaspora size, geographic distance, common language, colonial ties, GDP per capita, HDI, and a custom Political Instability Index.
* **Robustness** : Clustered standard errors, multicollinearity checks, and residual analysis.
* **Limits** : We used a Multiple Linear Regression Model, which might not be as efficient for this situation. Endogeneity, Selection Bias

### Key Findings :
* **Push Factor** : Political repression and lack of freedom in the origin country are strong drivers of exile.
* **Pull Factor** : The pre-existing **diaspora network** is the most robust determinant of the chosen destination, strongly amplified by a shared common language
* **Non-significant Factors** : Once networks and fixed effects are controlled for, geographic distance and economic wealth (GDP and HDI) do not significantly dictate the final destination.

##  Technologies and Libraries
* **R**
* `fixest`, `feols`
* `tidyverse`, `ggplot2`
* `modelsummary`, `corrplot`
