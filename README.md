# Fully-Bayesian-Conjugate-Analysis

The project has been done during the Spring semester 2022, for the Bayesian Statistics course.

It's divided in two parts:

## Analysis of the daily accidents in the city of Rome
The analysis is based on a dataframe which contains the number of daily accidents happened during 2016 in Rome.
The initial statistical model is modelled as a Poisson (remind: the Poisson distribution reflects the number of events occurred during a certain amount of time) and it's conjugated with a Gamma model, in order to obtain a posterior distribution Gamma.

The covered topics in this analysis are:
- Data visualization
- Point estimation
- Interval estimation
- Posterior uncertainty
- Posterior predictive distribution

## Analysis of the lifetime of an hypothetic innovative bulb
Let's suppose you have created an innovative bulb and you want to know as most as possible information on its lifetime. In this case, you have only 20 observations and you need to study statistically the behaviour of the bulbs.

The initial statistical model is Exponential (remind: the Exponential distribution reflects the average lifetime of a phenomena and it has the property of "memory loss"). It's conjugated with a Gamma model in order to obtain **the parameters of a Gamma**, but it will be studied as an Inverse Gamma.

The covered topics in this analysis are:
- Invertibility of a Gamma random variable
- Point estimation
- Interval estimation
- Prediction on the average lifetime of the bulb by using the Inverse Gamma
