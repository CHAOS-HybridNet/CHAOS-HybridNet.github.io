---
title: "A stacked heterogeneous ensemble learning model"

date: 2025-02


paperurl: 'http://academicpages.github.io/files/2512735.pdf'

---
 Thenumberanddistribution of Olympic medals are influenced byavariety of factors, including
 a country’s geographical location, economiclevel, population size, and national physical fitness. By
 building a mathematical model to explore the patterns influencing Olympic medal distribution, this
 study not only helps countries scientifically improve their medal performance in future Olympics
 but also contributes to the global spread and development of the Olympic spirit.
 Question 1 focuses on predicting the 2028 Los Angeles Olympics. Due to the high uncertainty
 of the Olympic events , data preprocessing involved statistical analysis of medal counts by country
 and event in each Olympic Games, serving as influencing factors for training the model. Through
 multiple experiments, it was found that traditional time series forecasting models do not adapt
 well to this problem. Thus, the data was stacked over time giving more weight to years closer
 to the event. LangChain technology was used to collect background information on athletes’
 retirement times, quantifying the impact of their past performances on current outcomes. In
 terms of model selection, this study used a heterogeneous ensemble stacking model, combining
 base models including Ridge Regression, Lasso Regression, Decision Trees, XGBoost, Neural
 Networks, and Multi-linear Regression with strong anti-overfitting capabilities. To address the
 data imbalance caused by a small number of winning countries, over-sampling techniques were
 introduced into the ensemble model. The model’s performance, stability, and generalization ability
 were quantitatively evaluated using metrics like R² and MAPE, and the confidence interval for total
 medal counts was calculated using MSE and accuracy. For the first and second subquestions,
 the study performed a set difference between the predicted data and historical medal data provided
 in the problem and selected countries with a probability greater than 55% as potential first-time
 medalists. The evaluation of each country’s performance was based on ranking changes and
 medal count changes. Five countries were predicted to win medals for the first time, with an odds
 ratio of 31.75, and the five countries with the most significant improvements and declines were
 identified. For the third subquestion, the study assigned different weights to the gold, silver, and
 bronze medals of each country and event to measure the importance of each event to the country.
 Question 2 focuses on the ”Great Coach Effect.” To find evidence for this effect, the study
 began by examining changes in the number of medals, defining a mutation effect function f(x)
 that quantifies the extent of medal mutations in a given year compared to an initial reference year.
 The function f(x) considers both the total number of medals and the time interval, revealing the
 mutation in medal performance. The coefficient m controls the intensity of the mutation effect. The
 model suggests that when the value of f(x) is large, the mutation is significant, and the likelihood
 of the ”Great Coach Effect” influencing athlete performance is higher. For each country, the study
 calculates the projects and years when f(x) reaches its maximum, checking whether there was a
 coaching change in that year to further verify the Great Coach Effect. Specifically, for China in
 football, Kenyainathletics, andJapanintabletennis, thecoachingeffectmaywarrantinvestment
 consideration.
 Question 3 focuses on the model’s insights into the underlying factors affecting Olympic medal
 counts. It discusses three aspects: historical status, national economic level, and the cultural
 identity and bias towards sports events.
