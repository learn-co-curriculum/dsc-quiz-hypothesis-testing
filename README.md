# Hypothesis testing

While we recommend using Python to find the answers to these questions, it is not required. You are more than welcome to use a calculator or pencil and paper to solve them, too.

???

# Quiz - Hypothesis testing

?: You are asked to run a hypothesis test to test whether two sample means are different from each other or not. Your null hypothesis is that there is no difference in the sample means. Your alternative hypothesis is that the sample means are different from each other. You run the test and find a p-value of 0.01. Do you reject the null hypothesis?

( ) Yes, since the p-value is less than 0.05.

( ) We do not have enough information to assess whether we have enough evidence to reject the null hypothesis or accept it.

(X) We do not have enough information to assess whether we have enough evidence to reject or fail to reject the null hypothesis. 

( ) No, since it is still likely that the sample means are not different from each other.

?: Consider a sample of 100 athletes who have their blood oxygen levels measured before and after going on a 30 minute run. You want to determine if their mean blood oxygen levels are significantly different after the half-hour run compared to the mean blood oxygen levels before the run. What kind of hypothesis test do you need to perform? 

( ) unpaired two-tailed two-sample t-test 

( ) unpaired upper-tailed two-sample t-test 

( ) two-tailed two-sample z-test 

(X) paired two-sample t-test 


?: A teacher wants to know if her students have a good grasp of basic statistics. Seven students are chosen at random from her class and given a statistics proficiency test. The teacher wants the class to score above 75 on her test. 

What are the null and alternative hypotheses that the teacher needs to test to have 95% confidence that the mean score for the class on the test would be greater than 75? 

( ) $H_0: \mu = 75$, $H_A: \mu \lt 75$ 

( ) $H_0: \mu \neq 75$, $H_A: \mu = 75$

(X) $H_0: \mu = 75$, $H_A: \mu \gt 75$

( ) $H_0: \mu \neq 75$, $H_A: \mu \gt 75$

?: Consider the weight loss of 20 healthy individuals between 25-34 years of age. 

10 individuals followed a high-protein diet and 10 individuals followed a high fat diet. 

`high_protein = [11.2, 11.4, 7.4, 10.9, 9.8, 8.7, 11.0, 9.3, 8.4, 10.9]`

`high_fat = [15.6, 14.4, 13.0, 14.1, 13.2, 13.5, 13.0, 15.6, 12.9, 12.4]`

How would you use Python to test if the mean weight loss of the two groups was different or not?  You can assume that both distributions have equal variances.

( ) Use `scipy.stats.ttest_ind_from_stats(high_protein, high_fat)`

(X) Use `scipy.stats.ttest_ind(high_protein, high_fat)` 

( ) Use `scipy.stats.ttest_1samp(high_protein, high_fat)`


?: Select all true statements from the choices below: 

[X] A larger value of the significance threshold $\alpha$ increases the chances of rejecting the null hypothesis.

[X] Larger values of $\alpha$ increase Type I error and decrease Type II error.

[ ] Smaller values of $\alpha$ increase Type I error and decrease Type II error.

[X] Using small values of $\alpha$ decreases the chances of incorrectly rejecting the null hypothesis given it is actually true.


???