# Statistics
Contains questions on statistics required in machine learning based on as asked in interviews

[Which hypothesis test to perform?](https://towardsdatascience.com/which-hypothesis-test-to-perform-89d7044d34a1)

## Variance
Variance gives us an idea about the distribution of data around the mean, and thus from this distribution, we can work out where we can expect an unknown data point. 

## Why variance is divided by (n-1)?
[Khan Academy - Variance](https://www.khanacademy.org/math/ap-statistics/summarizing-quantitative-data-ap/more-standard-deviation/v/another-simulation-giving-evidence-that-n-1-gives-us-an-unbiased-estimate-of-variance)

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


## F-tests 

Compares variance of two different population.\
Assumption:  Population from which sample is drawn must be normal.


<img src="https://github.com/Adi1729/Statistics/blob/master/F test.jpg" width = 80%,  height = 80%>

   1. F-test for testing equality of variance is used to test the hypothesis of the equality of two population variances. The height example above requires the use of this test.
   
   2. F-test for testing equality of several means. The test for equality of several means is carried out by the technique called ANOVA.\
   For example, suppose that an experimenter wishes to test the efficacy of a drug at three levels: 100 mg, 250 mg and 500 mg. A test is conducted among fifteen human subjects taken at random, with five subjects being administered each level of the drug.\
To test if there are significant differences among the three levels of the drug in terms of efficacy, the ANOVA technique has to be applied. The test used for this purpose is the F-test.
   
   3. F-test for testing significance of regression is used to test the significance of the regression model. The appropriateness of the multiple regression model as a whole can be tested by this test. A significant F value indicates a linear relationship between Y and at least one of the Xs.

## Z-test and T-test

Both the tests is use to find how mean of a two sample is different from each other. 

Z- test is used when standard deviation of a population is known and t - test is used when standard deviation is now known for population. Instead it is estimated by finding standard deviation of a sample. 

Assumption of a t-test :
1. Random sample i.e each sample must be independant of each other which is assumed if samples size < 30 or 10% of population.
2. Sample follows Normal distribution

Z -test is used when sample size > 30.

## [Multicollinearity and VIF](https://newonlinecourses.science.psu.edu/stat501/node/347/)




 



