# Statistics
Contains questions on statistics required in machine learning based on as asked in interviews


## Covariance and Corrlelation :

Covariance :\
Formaula = ![first equation](https://latex.codecogs.com/gif.latex?%5Cfrac%7B%5Csum%20%28X-%5Cbar%7BX%7D%29%28Y-%5Cbar%7BY%7D%29%7D%7BN%7D)

Assume X  = Height(cms) , Y = Weight(kgs) , Z = Age(Yrs)\

cov(X,Y) = 100 cms-Kgs\
cov(Y,Z) = 150 kgs-Yrs\
However, one can not compare two cavariance results as both has different units.\

Correlation:\
Formaula = ![second equation](https://latex.codecogs.com/gif.latex?%5Cfrac%7Bcov%28X%2CY%29%7D%7Bcov%28X%29cov%28Y%29%7D)                 -1<=cor<=1\
cor(X,Y) = 0.5\            
cor(X,Z) = 1\
Here, it can ne said X,Z covary much more than X,Z 

## Why variance is divided by (n-1)?\
[Khan Academy - Variance](https://www.khanacademy.org/math/ap-statistics/summarizing-quantitative-data-ap/more-standard-deviation/v/another-simulation-giving-evidence-that-n-1-gives-us-an-unbiased-estimate-of-variance)




 



