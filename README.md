# Hypothesis-Testing

## What Is Hypothesis Testing?
Hypothesis testing is a common statistical tool used in research and data science to support the certainty of findings. The aim of testing is to answer how probable an apparent effect is detected by chance given a random data sample.

Hypothesis testing is used to assess the plausibility of a hypothesis by using sample data. Such data may come from a larger population, or from a data-generating process

## What is a hypothesis?
A hypothesis is often described as an “educated guess” about a specific parameter or population. Once it is defined, one can collect data to determine whether it provides enough evidence that the hypothesis is true.

## Hypothesis testing
In hypothesis testing, two mutually exclusive statements about a parameter or population (hypotheses) are evaluated to decide which statement is best supported by sample data.

## When do we use it?
It is generally used when we were to compare:

-a single group with an external standard
 
-two or more groups with each other

Note: Don’t be confused between the terms Parameter and Satistic.

A Parameter is a number that describes the data from the population whereas, a Statistic is a number that describes the data from a sample.

## Terminology used
## Null Hypothesis: 
Null hypothesis is a statistical theory that suggests there is no statistical significance exists between the populations.

It is denoted by H0 and read as H-naught.

## Alternative Hypothesis:
An Alternative hypothesis suggests there is a significant difference between the population parameters. It could be greater or smaller. Basically, it is the contrast of the Null Hypothesis.

It is denoted by Ha or H1.

#### Note: 
H0 must always contain equality(=). Ha always contains difference(≠, >, <).

For example, if we were to test the equality of average means (µ) of two groups:

for a two-tailed test-

When the given statistics hypothesis assumes a less than or greater than value, it is called the two-tailed test.

we define H0: µ1 = µ2 and Ha: µ1≠µ2

for a one-tailed test-

When the given statistical hypothesis is one value like H0: μ1 = μ2, it is called the one-tailed test. 

we define H0: µ1 = µ2 and Ha: µ1 > µ2 or Ha: µ1 < µ2

#### Level of significance: 
Denoted by alpha or α. It is a fixed probability of wrongly rejecting a True Null Hypothesis. For example, if α=5%, that means we are okay to take a 5% risk and conclude there exists a difference when there is no actual difference.

#### Critical Value:
Denoted by C and it is a value in the distribution beyond which leads to the rejection of the Null Hypothesis. It is compared to the test statistic.

#### Test Statistic:
It is denoted by t and is dependent on the test that we run. It is deciding factor to reject or accept Null Hypothesis.

The four main test statistics are given in the below table:

![image](https://user-images.githubusercontent.com/109084435/191764143-f59f763a-4145-439e-b5e0-b56858efe284.png)

#### p-value: 
It is the proportion of samples (assuming the Null Hypothesis is true) that would be as extreme as the test statistic. It is denoted by the letter p.

Now, assume we are running a two-tailed Z-Test at 95% confidence. Then, the level of significance (α) = 5% = 0.05. Thus, we will have (1-α) = 0.95 proportion of data at the center, and α = 0.05 proportion will be equally shared to the two tails. Each tail will have (α/2) = 0.025 proportion of data.

The critical value i.e., Z95% or Zα/2 = 1.96 is calculated from the Z-scores table.

Now, take a look at the below figure for a better understanding of critical value, test-statistic, and p-value.
![image](https://user-images.githubusercontent.com/109084435/191764757-613e0d63-3058-4772-9f54-5385c0e3f00e.png)

### Steps of Hypothesis testing
For a given business problem,


-Start with specifying Null and Alternative Hypotheses about a population parameter

-Set the level of significance (α)

-Collect Sample data and calculate the Test Statistic and P-value by running a Hypothesis test that well suits our data

-Make Conclusion: Reject or Fail to Reject Null Hypothesis

### Decision Rules
The two methods of concluding the Hypothesis test are using the Test-statistic value, p-value.

In both methods, we start assuming the Null Hypothesis to be true, and then we reject the Null hypothesis if we find enough evidence.

The decision rule for the Test-statistic method:

if test-statistic (t) > critical Value (C), we reject Null Hypothesis.

If test-statistic (t) ≤ critical value (C), we fail to reject Null Hypothesis.

The decision rule for the p-value method:

if p-value (p) > level of significance (α), we fail to reject Null Hypothesis

if p-value (p) ≤ level of significance (α), we reject Null Hypothesis

In easy terms, we say P High, Null Fly and P low, Null go.

### Confusion Matrix in Hypothesis testing
To plot a confusion matrix, we can take actual values in columns and predicted values in rows or vice versa.
![image](https://user-images.githubusercontent.com/109084435/191788175-e9005fa7-2969-4c81-a9f2-f4318bef6a9c.png)

#### Confidence: 
The probability of accepting a True Null Hypothesis. It is denoted as (1-α)

#### Power of test: 
The probability of rejecting a False Null Hypothesis i.e., the ability of the test to detect a difference. It is denoted as (1-β) and its value lies between 0 and 1.

#### Type I error: 
Occurs when we reject a True Null Hypothesis and is denoted as α.

#### Type II error:
Occurs when we accept a False Null Hypothesis and is denoted as β.

![image](https://user-images.githubusercontent.com/109084435/191795078-ef3364a0-7e48-415d-8fac-32db4618028a.png)


#### Accuracy:  
Number of correct predictions / Total number of cases

The factors that affect the power of the test are sample size, population variability, and the confidence (α).
Confidence and power of test are directly proportional. Increasing the confidence increases the power of the test.

### Types of Hypothesis Tests
Hypothesis tests when the data is Continuous.
![image](https://user-images.githubusercontent.com/109084435/191791916-858cea08-39ce-4069-9637-ec82d2d212d3.png)
IMAGE-Hypothesis tests for continuous data

Hypothesis tests when the data is Discrete
![image](https://user-images.githubusercontent.com/109084435/191793571-b956f7a7-90a2-44b0-803f-17e2d9b0348a.png)

