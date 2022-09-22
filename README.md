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

for a two-tailed test, we define H0: µ1 = µ2 and Ha: µ1≠µ2

for a one-tailed test, we define H0: µ1 = µ2 and Ha: µ1 > µ2 or Ha: µ1 < µ2

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

Start with specifying Null and Alternative Hypotheses about a population parameter
Set the level of significance (α)
Collect Sample data and calculate the Test Statistic and P-value by running a Hypothesis test that well suits our data
Make Conclusion: Reject or Fail to Reject Null Hypothesis
