# A/B Testing Analysis: Website Layout Optimization

## Project Overview
This project evaluates the impact of a new website layout on user conversion rates. By applying statistical rigor to a large-scale A/B test, we determine whether design changes lead to measurable business growth.

## Key Technical Skills Demonstrated
* **Experimental Design:** Conducted Power Analysis to determine required sample size.
* **Data Cleaning:** Handled data inconsistencies by removing users with duplicate assignments.
* **Statistical Inference:** Performed a Two-proportion Z-test to validate hypotheses.
* **Visualization:** Utilized `Seaborn` to visualize conversion rate distributions with 95% Confidence Intervals.

## Methodology
1. **Power Analysis:** Calculated a required sample size of 4,433 users per group to ensure a power of 0.8 at a significance level of 0.05.
2. **Cleaning:** Identified and removed 1,895 users with inconsistent group assignments to ensure data integrity.
3. **Hypothesis Testing:**
   - Null Hypothesis ($H_0$): No difference in conversion rates between the control and treatment groups.
   - P-value result: 0.2394.

## Conclusion & Business Insight
The difference in conversion rates (12.03% vs 11.89%) is **not statistically significant** ($p > 0.05$). We do not have sufficient evidence to suggest the new design negatively impacts performance. 

**Recommendation:** The design change is neutral. We recommend either iterating on the design to test more impactful features or concluding the experiment to focus on other high-impact growth levers.
