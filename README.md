# Optimal-mean-square-error-estimator
The purpose of this simulation is to estimate received BPSK signal. The simulation starts off with gaussian noise and a random bpsk signal. Then the BPSK and noise are added to form a noisy signal that is received at the receiver. Using this information, we imploy the optimal estimation espression E[X|y] = tanh(y). 
We also compare the results of optimal estimator with Suboptimal solution (sign(y)). We conclude that both estimator perform in a similar fashion with same accuracy in our case. 
