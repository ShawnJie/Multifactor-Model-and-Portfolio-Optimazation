# Multifactor-Model-and-Portfolio-Optimazation
Construct multi-factor model and build Markowitz portfolio, Black-Litterman portfolio and improve by appling ED algorithm to solve LME model
This project is an individual final project of Active Portfolio Management course in NYU Tandon.

In this project, I:
1. Use history data of 4000days and 2000 stocks to build a multi factor model with style factors (BETA, MOMENTUM, SIZE, VOL),Industry factors(one-hot coding) and Alpha factors (TD, TIR) by both OLS and WLS regression.
2. Solve Markowitz Portfolio Optimazition without using 2000*2000 memory (which is stock correlation matrix) and plot P/L with and without transaction cost (assuming quadratic).
3. Solve Black-Litterman Portfolio with benchmark portfolio cap-weighted (equilibrium) and compare P/L with Markowitz.
4. Futhermore, estimate parameters under LME(linear mixed-effects) model using EM algorithm. Rebuild a Markowitz-LME portfolio and compare P/L with initial Markowitz portfolio.
