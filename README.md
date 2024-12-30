# Computational-Statistics

This repository hosts two separate assignments for the STA380H5 course, focusing on advanced topics in Probability, Simulation, and Monte Carlo methods.

# Assignment 1

**FOCUS:** Methods for Generating Random Variables (Inverse Transform Method, Acceptance–Rejection Method)


**Overview:**

Weibull Distribution

* Derive the CDF, inverse CDF, expected value.
* Implement the inverse transform method to generate samples in R.
* Compare theoretical vs. empirical statistics (mean, histogram).

Cauchy Distribution

* Derive the CDF, inverse CDF, and show 𝐸(𝑋) does not exist.
* Generate multiple  large samples in R and discuss behavior of sample means/variances.

Distribution with 𝑓(𝑥) = 2/𝑥^3 for 𝑥 > 1

* Derive CDF, inverse CDF, mean, variance.
* Simulate using inverse transform; compare empirical mean/variance to theoretical values.

Discrete Distribution (pmf given via a recursive formula)

* Prove recursion, design a sampling algorithm.
* Generate large samples in R; report mean and variance.

Acceptance–Rejection Sampling

* Target  𝑓(𝑥)=1 − ∣1 − 𝑥 ∣ on [0,2]; trial distribution Uniform (0,2).
* Find the constant 𝑐 = max 𝑓(𝑥)/𝑔(𝑥)
* Generate and compare simulated distribution to the true density.


# Assignment 2

**FOCUS:** Monte Carlo Integration and Variance Reduction

**Overview:**

Empirical CDF (ECDF)

- Prove unbiasedness and derive the variance/covariance of the ECDF.
- Visual comparison of the empirical vs. theoretical CDF using R (Exponential distribution).

Estimating a Normalizing Constant via Monte Carlo

- Given a complicated density 𝑓(𝑥) up to a constant 𝑘.
- Construct and implement a Monte Carlo estimator 𝑘 by sampling from an auxiliary distribution (e.g., Normal).
- Compute the estimate in R.

Estimating 𝜋 and Related Integrals

- Show that 𝜃 = ∫ 1/(1 + 𝑥^2) 𝑑𝑥 = 𝜋/4
- Construct Monte Carlo estimators and 𝜋 us-ing Uniform(0, 1).
- Explore an alternative estimator using a different distribution (e.g., Exponential).
- Compare simulation results and theoretical values.

Antithetic Variates

- Compute a target integral θ=∫ x/(1+x^2)*e^−2x dx via Monte Carlo.
- Derive a standard Monte Carlo estimator and an antithetic variate estimator.
- Compare variances and compute the variance reduction percentage.

Monte Carlo Integration with 𝑓(𝑥) = 𝑒^𝑥

- Construct a Monte Carlo estimator for ∫ 𝑒^𝑥 𝑑𝑥 using i.i.d. uniform samples.
- Prove unbiasedness, compute exact values, and discuss variance.
- Derive and implement an antithetic variate estimator.
- Compare results and explain why antithetic variates can reduce variance.





