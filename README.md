### Maximum Likelihood Estimation:

used to estimate parameters of a probability distribution

### MLE steps:
- import required library: 
    - from scipy.optimize import minimize
- define the likelihood function and negative likelihood function
- implement MLE Algorithm:
    - minimize(neg_lklh,[guess value][,args=(data),method=])
- check result:
    - res.x
- evaluate the model:
    - MSE, ect.

### MLE exercise:
|No.| Project |
|---|---------|
|1|[Estimate params of Linear Regression](https://github.com/Notrew/Maximum-Likelihood-Estimation-exercise/blob/main/scr/MLE-estimate%20params%20of%20linear%20regression.ipynb)|
|1|[Estimate params of Normal Distribution-1](https://github.com/Notrew/Maximum-Likelihood-Estimation-exercise/blob/main/scr/MLE-estimate%20params%20of%20normal%20distribution.ipynb)|
|1|[Estimate params of Normal Distribution-2](https://github.com/Notrew/Maximum-Likelihood-Estimation-exercise/blob/main/scr/MLE-estimate%20params%20of%20normal%20distribution-2.ipynb)|
|1|[Estimate params of Poisson Distribution](https://github.com/Notrew/Maximum-Likelihood-Estimation-exercise/blob/main/scr/MLE-estimate%20params%20of%20poisson%20distribution.ipynb)|
