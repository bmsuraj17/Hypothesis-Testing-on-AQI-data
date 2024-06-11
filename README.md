# Hypothesis Testing Project: Improving Air Quality in America

## Overview

This project was conducted for an environmental think tank, Repair Our Air (ROA). The goal is to leverage the Environmental Protection Agency's Air Quality Index (AQI) data to guide policy recommendations for improving air quality in America. The AQI value ranges from 0 (indicating little to no public health concern) to higher values that are associated with increased health risks.

## Hypotheses

ROA is considering the following decisions. For each, we construct a hypothesis test to make a recommendation:

1. **Metropolitan-Focused Approach in California:**
    - **Objective:** Determine if the mean AQI in Los Angeles County is statistically different from the rest of California.
    - **Hypothesis:**
        - Null Hypothesis (H0): The mean AQI in Los Angeles County is equal to the mean AQI in the rest of California.
        - Alternative Hypothesis (H1): The mean AQI in Los Angeles County is different from the mean AQI in the rest of California.
        
2. **Choosing Between New York and Ohio for a Regional Office:**
    - **Objective:** Determine if New York has a lower AQI than Ohio.
    - **Hypothesis:**
        - Null Hypothesis (H0): The mean AQI in New York is greater than or equal to the mean AQI in Ohio.
        - Alternative Hypothesis (H1): The mean AQI in New York is less than the mean AQI in Ohio.
        
3. **New Policy Impact on Michigan:**
    - **Objective:** Determine if Michigan would be affected by a new policy targeting states with a mean AQI of 10 or greater.
    - **Hypothesis:**
        - Null Hypothesis (H0): The mean AQI in Michigan is less than 10.
        - Alternative Hypothesis (H1): The mean AQI in Michigan is 10 or greater.

## Methodology

### Data Collection
- The AQI data was sourced from the Environmental Protection Agency.

### Statistical Tests
- A 5% level of significance was used for all hypothesis tests.
- Welch’s t-test was applied for two-sample t-tests to account for possibly unequal variances between the comparison groups.

## Results

1. **Los Angeles vs. Rest of California:**
    - The AQI in Los Angeles County was found to be statistically different from the rest of California.

2. **New York vs. Ohio:**
    - At a 5% significance level, New York was found to have a lower AQI than Ohio.

3. **Michigan and the New Policy:**
    - The tests indicated that Michigan's mean AQI is less than 10, meaning it is unlikely to be affected by the new policy.

## Conclusion

- **Key Takeaways:**
    - Even with small sample sizes, significant conclusions can be drawn due to the variation within the data.
    - The mean AQI in Los Angeles County is statistically different from the rest of California.
    - New York has a statistically lower mean AQI than Ohio.
    - Michigan's mean AQI is less than 10, hence, it is unlikely to be affected by the new policy.

- **Presentation to Manager:**
    - Present the null and alternative hypotheses for each test.
    - Describe the conclusion and the resulting p-value.
    - Specify the type of test, whether it was one-tailed or two-tailed, and the method used.

- **Conveying to External Stakeholders:**
    - Provide the level of significance (5%) and the conclusions.
    - Include sample statistics for context.

