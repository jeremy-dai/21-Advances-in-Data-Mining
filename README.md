# 21-Advances-in-Data-Mining
Assignments for the course of "Advances in Data Mining"

TA notes
## Assignment 1
- implementation of naive methods good
- good doing both GD and ALS

what I'm missing / could be improved:
- short explanation of the linear regression model
- your use of error metrics is inconsistent:
- you're supposed to use the root mean square error (RMSE)
- in your intro you talk about the mean absolute error (MAE)
- in your code for the naive methods you say you use the mean square error (MSE) (also "Mean MSE" is a redundant acronym), but the actual implementation implements the RMSE...
- in your code for the matrix factorization you are actually using the MSE
- "Because the optimization of the hyperparametres is time-consuming and there is limited time, we did not finish the optimization of the hyperparametres number of latent factors and learning rate." One thing you could do is to optimize the parameters on a smaller dataset
minor remarks:
- you used a different dataset than the assignment pointed to, which required me to do some work before I would get your code to run
- "Too few iterations can lead to underfitting and too many can lead to overfitting." While a limited number of iterations can indeed prevent overfitting, it is better to prevent overfitting with other parameters of the model (like the number of latent factors)
