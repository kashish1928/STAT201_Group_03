# STAT 201 PROJECT

## Members
- Kashish Joshipura
- Alex Haddon
- Nusaibah Hossain
- Euna Ao

## Project Description
The 1973 Berkeley Dataset contains 12.763 applicants who applied to UC-Berkeley graduate programs and their respective major, gender, and admission status.
This dataset is part of ongoing discourse regarding gender bias in university admissions. A 2002 study conducted in Israel found that admissions scores were a fair, unbiased predictor of first year performance (Azen et al., 2002). Similarly, a 2017 study found that there was equal probability of admittance across all genders (Bhattacharya et al., 2017).
Dataset Size: 12,763 rows × 4 columns
Dataset Variables:
As our population is all applicants, our parameter of interest is the difference of proportion for the proportions of male and female students admitted. Our research question is: **"is there indication of gender-based discrimination for UC-Berekely admissions in 1973?"**

We will perform two two-tailed hypothesis tests for difference on proportions - one being theory based and the other using bootstrap distribution. 
We are investigating whether there existed gender discrimination in graduate admissions between male and female applicants. Our null hypothesis would be that there existed no such discrimination and that the proportions are equal.
H0 : pm - pf = 0
Our alternative hypothesis is that a difference exists and therefore the difference in proportions would be non-zero.
Ha : pm - pf ≠ 0
For this question we will test three different levels of significance: 10%, 5%, and 1%.
Our observed difference in proportions is : 0.0970327718040209
Theory Based Hypothesis Test
We verify that our data meets the sample size condition such that 𝑛𝑝̂ ≥10 and 𝑛(1−𝑝̂ )≥10. This ensures that our sampling distribution under 𝐻0 of the test statistic 𝑍 is approximately 𝑁(0,1).
To ensure the normally distributed null model, we will calculate the pooled proportion.
We can then calculate the Z test statistic as our null model is approximately normal. 

We will then compare the prop.test p values with the varying significance levels and either reject or fail to reject the null hypothesis. 

95% confidence interval centered around the observed difference in proportions will be constructed and then compared to the null hypothesis. 


## Dataset Reference
https://discovery.cs.illinois.edu/dataset/berkeley/

## Project Proposal
https://docs.google.com/document/d/1afPh7QVXkeraJ82jvYv2fBdImOKBRsY33u1EI3v8ZVQ/edit?usp=sharing
