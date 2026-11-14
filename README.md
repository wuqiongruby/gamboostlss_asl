This repository contains the functions to implement asymptotic adaptive step length approach for boosting GAMLSS models. Currently supported GAMLSS distributions include
- Gaussian
- Negative Binomial I: $Y \sim  \mathcal{NB}(\mu, \alpha), \mathbb{E}[Y] = \mu, \text{Var}(Y) = \mu + \alpha\mu^2.$
- Negative Binomial II: $Y \sim  \mathcal{NB}(\mu, \alpha), \mathbb{E}[Y] = \mu, \text{Var}(Y) = \mu + \frac{\mu^2}{\alpha}.$
- AFT Weibull

\texttt{example.R} illustrates how to boost GAMLSS models with asymptotic adaptive step lengths. Make sure that following packages have been installed before running the example code:
- MASS
- survival
- mboost
  
