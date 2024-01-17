# Statistical-Analysis-of-NYPD-Drug-Related-Arrests-2018-2019
Demographic Disparities in Drug-Related Arrests: An Analytical Study of NYPD Data (2018-2019)

This study delves into the patterns of drug-related arrests in New York City, with a focus
on demographic factors such as race, gender, and age. Utilizing The New York City Police
Department (NYPD) arrest data from 2018-2019, I conducted a detailed analysis using statistical
hypothesis testing and visualizations.

# Introduction

Urban crime and law enforcement embody intricate challenges, especially in the realm of demographic
disparities. In a city as diverse as New York, understanding these disparities is not just
a matter of law enforcement efficiency, but also one of upholding social justice. This project delves
deep into the realm of drug-related arrests within New York City’s multifaceted urban landscape. It
seeks to untangle the complex web of how demographic factors like race, gender, and age influence
these arrest patterns.

# Data

This study employs a subset of the NYPD Arrests Data (Historic), which contains
every arrest made in New York City by the NYPD from January 1, 2018 to December 31, 2019.
It contains a total of 456084 data points collected in this time period. This data-set contains a total of 19 columns. It was compiled through manual
extraction and review processes conducted quarterly by the NYPD’s Office of Management Analysis and Planning.

# Methods

The methodology embraced data cleaning, exploratory
data analysis (EDA), and hypothesis testing, focusing on both two-tailed and one-tailed Z-tests.

# Results

## Visualisations

1. Age Group Distribution of Arrests (Figure 1).
   ![image](https://github.com/varun-crypto/Statistical-Analysis-of-NYPD-Drug-Related-Arrests-2018-2019/assets/69026838/209aa915-0371-4e56-8dfc-949d517777dc)

2. Sex Distribution of Arrests (Figure 2).
   
   ![image](https://github.com/varun-crypto/Statistical-Analysis-of-NYPD-Drug-Related-Arrests-2018-2019/assets/69026838/ca3de2d6-06ea-489e-aec7-a4192f118981)

4. Race Distribution of Arrests (Figure 3).
   ![image](https://github.com/varun-crypto/Statistical-Analysis-of-NYPD-Drug-Related-Arrests-2018-2019/assets/69026838/c076fcd3-457b-4bfe-923f-7c922c1f9488)

5. Temporal Trends in Arrests (Figure 4).
   ![image](https://github.com/varun-crypto/Statistical-Analysis-of-NYPD-Drug-Related-Arrests-2018-2019/assets/69026838/e780b2c4-07f8-4b3d-a07c-72f14605e270)

6. Geographic Distribution of Arrests (Figure 5).
   ![image](https://github.com/varun-crypto/Statistical-Analysis-of-NYPD-Drug-Related-Arrests-2018-2019/assets/69026838/2d24caae-26a9-401c-ab5a-74902694d397)

7. Top Ten Offenses by Frequency (Figure 6).
   ![image](https://github.com/varun-crypto/Statistical-Analysis-of-NYPD-Drug-Related-Arrests-2018-2019/assets/69026838/e11f7546-c9c9-43d7-a4d7-a087c6bd4e93)

 From the results we can see various patterns in the initial analysis of the overall dataset. From Figure
1 we can see that people arrested who are in the age group of 25-44 have the highest percentage
of arrest rate compared to others. From Figure 2 it was observed that Males have significantly
larger arrest rates when compared to Females. Looking at Figure 3 it was observed that Black
individuals had the most number of arrests when compared to other races. From these results we
can see that there are demographic disparities in the arrests with different offense type. From other
visualizations like Figure6 we can observe that ’Assault 3 & Related Offenses’, Dangerous Drugs and
’Petit Larceny’ are three most frequently occurring crimes. Figure 5 shows geographic distribution
of arrests, it was observed that Brooklyn has the most number of arrests when compared to other
borough. Finally temporal trends from Figure 4 show that there was a downward slope in arrests
from Jan 1, 2018 to December 31, 2019.

## Hypothesis Testing

Hypothesis tests were conducted to explore demographic disparities further. Two-tailed and onetailed
Z-tests were applied, appropriate for comparing proportions in large sample sizes. Here Z
test was used because of large sample sizes. The population, sample and significance level defined
for all the hypothesis tests is mentioned below:

Population: All individuals arrested for drug-related offenses in NYC.

Sample: Individuals arrested in 2018-2019 from the dataset.

Significance: 0.05

#### Hypothesis 1: Racial Disparity in Drug-Related Offenses

Null Hypothesis (H0): No difference in drug-related arrests between Black and White individuals.

Alternative Hypothesis (H1): A difference exists in drug-related arrests between Black and White
individuals.

Test Type: Two-tailed Z-test was used due to the non-directional nature of the hypothesis.

#### Hypothesis 2: Gender Differences in Drug-Related Arrests

Null Hypothesis (H0): No difference in the proportion of drug-related arrests between males and
females.

Alternative Hypothesis (H1): A higher rate of drug-related arrests among males than females.

Test Type: A one-tailed Z-test was employed, anticipating a higher arrest rate in males. One-tail
Z-test was used because the hypothesis here is more specific.

#### Age Group Differences in Drug-Related Arrests

Null Hypothesis (H0): The proportion of drug-related arrests is equal for the 45-64 and < 18 age
groups.

Alternative Hypothesis (H1): The 45-64 age group has a higher proportion of drug-related arrests than the <18 group.

Test Type: A one-tailed Z-test was suitable, predicting a higher arrest proportion in the ”45-64”
age group. One-tail Z-test was used because the hypothesis here is more specific.

<img width="374" alt="image" src="https://github.com/varun-crypto/Statistical-Analysis-of-NYPD-Drug-Related-Arrests-2018-2019/assets/69026838/08bdc11c-396c-4453-9bbb-3f4b2c30e1c2">

From the first hypothesis results, a Z statistic of -8.27 shows that the observed proportion difference
between Black and White individuals in drug-related arrests is 8.27 standard deviations away from
the null hypothesis (no difference), which is highly significant. P value < 0.05 and a high Z statistic,
leads us to reject null hypothesis. So, we can say that there exists a difference in drug-related arrests
in NYC between Black and White people.

From the second hypothesis results, a Z-statistic of 34.55 indicates that the proportion of drugrelated
arrests for males is 34.55 standard deviations higher than that of females, again indicating
a significant difference. P value < 0.05 and a high Z statistic, leads us to reject null hypothesis. So
we can say that there is a higher rate of drug-related arrests among males than females in NYC.

From the third hypothesis results, a Z-statistic of 37.42 means the proportion of drug-related arrests
in the 45-64 age group is 37.42 standard deviations higher than in the < 18 group, suggesting a
substantial disparity. P value < 0.05 and a high Z statistic, leads us to reject null hypothesis. So
we can say that there is a higher rate arrests among people in the group ’45-64’ than people in age
group < 18.

# Conclusion

From the findings from the hypothesis tests resonate with the research question, leading us to say
that there is demographic disparities present in the arrests done by NYPD in New York City.
The implications of these findings extend to the realms of social justice, policy making, and law
enforcement. They suggest a need for a closer examination of the factors leading to these disparities,
potentially informing more equitable law enforcement practices.







