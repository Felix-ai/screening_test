## EVALUATING SCREENING TESTS

### Introduction

Screening tests are often used in clinical practice to assess the likelihood that a person has a particular medical condition. The rationale is that, if disease is identified early (before the manifestation of symptoms), then earlier treatment may lead to cure or improved survival or quality of life.

Screening tests are often laboratory tests that detect particular markers of a specific disease. Many medical evaluations and tests may be thought of as screening procedures as well.

If the screening test is to be useful clinically two conditions must be met.

* First, the test has to provide an advantage in distinguishing between, for example, men with and without prostate cancer. 

* Second, one needs to demonstrate that early identification and treatment of the disease results in some improvement: a decreased probability of dying of the disease, or increased survival, or some measurable improvement in outcome.


### Screening for Down Syndrome

Suppose that a population of `N=4,810` pregnant women undergo the screening test and are scored as either positive or negative depending on the levels of hormones in the blood. In addition, suppose that each woman is followed to birth to determine whether the fetus was, in fact, affected with Down Syndrome.

The data are often organized as follows with the results of the screening test shown in the rows and results of the diagnostic test are shown in the columns.

| Screening Test | Down Syndrome | No Down Syndrome | Total |
|:--|:--:|:--:|:--:|
| Positive | 9 | 351 | 360 |
| Negative | 1 | 4,449 | 4,450 |
| Total | 10 | 4,800 |4,810 |


#### Sensitivity and Specificity

Screening tests are not diagnostic, but instead may identify individuals more likely to have a certain condition. There are two measures that are commonly used to evaluate the performance of screening tests: the sensitivity and specificity of the test. The sensitivity of the test reflects the probability that the screening test will be positive among those who are diseased. In contrast, the specificity of the test reflects the probability that the screening test will be negative among those who, in fact, do not have the disease

The false positive fraction is `1 - specificity` and the false negative fraction is `1 - sensitivity`.

* Sensitivity = Recall = True Positive Fraction = P(Screen Positive | Affected Fetus) = $\frac{9}{10} = 0.900$

* False Negative Fraction = P(Screen Negative | Affected Fetus) = $\frac{1}{10} = 0.100$

* Specificity = True Negative Fraction = P(Screen Negative | Unaffected Fetus) = $\frac{4,449}{4,800} = 0.927$

* False Positive Fraction = P(Screen Positive | Unaffected Fetus) = $\frac{351}{4,800} = 0.073$

**Interpretation:**

* If a woman is carrying an affected fetus, there is a `90.0%` probability that the screening test will be positive.

* If the woman is carrying an unaffected fetus, there is a `92.7%` probability that the screening test will be negative.

However, the false positive and false negative fractions quantify errors in the test. The errors are often of greatest concern.

* If a woman is carrying an unaffected fetus, there is a `7.3%` probability that the screening test will be positive. (If a woman is carrying an unaffected fetus, there is a `7.3%` probability that the test will incorrectly come back positive. This is potentially a serious problem as a positive test result would likely produce great anxiety for the woman and her family.)

* And if the woman is carrying an affected fetus there is a `10.0%` probability that the test will be negative. (A false negative result is also problematic. If a woman is carrying an affected fetus, there is a `10.0%` probability that the test will come back negative, and the woman and her family might feel a false sense of assurance that the fetus is not affected when, in fact, the screening test missed the abnormality.

The sensitivity and false positive fractions are often reported for screening tests. However, for some tests, the specificity and false negative fractions might be the most important. The most important characteristics of any screening test depend on the implications of an error.

#### Positive and Negative Predictive Value

Consider the results of a screening test from the patient's perspective! If the screening test is positive, the patient wants to know "What is the probability that I actually have the disease?" And if the test is negative, astute patients may ask, "What is the probability that I do not actually have disease if my test comes back negative?"

* Positive Predictive Value = Precision = P(Affected Fetus | Screen Positive) = $\frac{9}{360} = 0.025$

* Negative Predictive Value = P(Unaffected | Screen Negative) = $\frac{4,449}{4,450} = 0.999$

**Interpretation:**

* If a woman screens positive, there is a `2.5%` probability that she is carrying an affected fetus.

* If a woman screens negative, there is a `99.9%` probability that she is carrying an unaffected fetus.

**Positive Predictive Value (Yield) Depends on the Prevalence of Disease**

The sensitivity and specificity of a screening test are characteristics of the test's performance at a given cut-off point (criterion of positivity). However, the positive predictive value of a screening test will be influenced not only by the sensitivity and specificity of the test, but also by the prevalence of the disease in the population that is being screened. This is due to the fact that as the disease becomes more prevalent, subjects are more frequently in the "affected" or "diseased" column, so the probability of disease among subjects with positive tests will be higher.

In this example, the prevalence of Down Syndrome in the population of `N=4,810` women is $\frac{10}{4,810} = 0.002$ (i.e., in this population Down Syndrome affects `2 per 1,000 fetuses`). While this screening test has good performance characteristics (sensitivity of `90.0%` and specificity of `92.7%`), the prevalence of the condition is low, so even a test with a high sensitivity and specificity has a low positive predictive value.
