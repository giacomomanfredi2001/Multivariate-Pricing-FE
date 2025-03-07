# Multivariate-Pricing-FE: The Big Levy

This is the final project of the Financial Engineering course (May-June 2024). This project focuses on calibrating the parameters of an exponential Lévy model and pricing an exotic derivative, as outlined in project2_MultivariatePricing.pdf. The primary objective is to develop a robust methodology for multivariate Lévy processes, emphasizing the dependence structure between components to enhance financial derivative modeling.

The study is grounded in the theoretical frameworks of L. Ballotta and E. Bonfiglioli (2014) and extends to the practical implementation of pricing models, ensuring calibration aligns with market data.

Methodologies
Calibration of Lévy Processes: The project involves estimating the parameters of Lévy processes with Normal Inverse Gaussian (NIG) marginals, specifically for the S&P 500 and EURO STOXX 50 indices. Parameter estimation is conducted using optimization techniques such as RMSE and weighted RMSE minimization.
Derivative Pricing: Using the calibrated Lévy models, an exotic derivative is priced and compared against alternative models, including a Variance Gamma (VG) subordinator and the traditional Black model, to assess their relative performance.
Files and Resources
MATLAB Code: Scripts for calibrating Lévy processes, handling data, and optimizing parameters.
Python Code: Supplementary scripts for analyzing and validating the results obtained from MATLAB.
Project Report: A comprehensive document covering the theoretical background, methodologies, results, and discussion.
A brief project pitch is available at the following link:

[Pitch Presentation](https://onedrive.live.com/?redeem=aHR0cHM6Ly8xZHJ2Lm1zL2YvcyFBckFvMnBzVFc3N2RnWjRrSHdXUnlpM29nUFgyYmc%5FZT1QdWgxR2I&id=DDBE5B139BDA28B0%2120260&cid=DDBE5B139BDA28B0)
