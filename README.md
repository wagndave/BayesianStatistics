# Bayesian Statistics






Resources

https://people.stat.sc.edu/Hitchcock/stat535slidesday18.pdf

Bayesian Inference for Beta-Bernoulli Models: https://gregorygundersen.com/blog/2020/08/19/bernoulli-beta/




Whereas non-Bayesian approaches consider a probability model only, the hallmark characteristic of Bayesian models is that they specify a joint probability distribution for both data and parameters. 

This allows us to use the laws of conditional probability to describe our updated information about parameters given the data.

likelihood: $p(y|\theta)$

prior: $p(\theta)$

posterior: $p(\theta|y) = \frac{p(\theta,y)}{p(y)} = \frac{p(\theta,y)}{\int{p(\theta,y)d\theta}} = \frac{p(y|\theta)p(\theta)}{\int{p(y|\theta)p(\theta)d\theta}}$
