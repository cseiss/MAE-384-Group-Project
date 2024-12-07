Final project for MAE384

For part one, through the use of ODE equations and parameters given in the form of recovery and infection rates we are able to predict how disease will spread, and how fast people will recover. The ODE solver essentially simulates diseases, which are given in the form of differential equations, and how fast the population will recover with the parameter values. 
For part two, through the use of interpolation we were able to 'recover' data that initially was not there. Then we could compare it to data from the actual model that is accurate. It produces a table with errors, and shows how the quadratic interpolation has smaller errors.
For part three, the method of least squares was used to estimate the value of k and I(0) of the originally nonlinear SIR model. The equation was simplified and used the natural log to be able to use this method. After taking the natural log it finds the slope and y-intercept, a1 and a0. It runs the program for 30 and then 10 days. 
For part four, fourier analysis is on S(t), I(t), and R(t) and observe the peaks of the frequency. It plots the infected cases versus the frequency with two differnt frequency values. 
