# Employee_Experience_Survey_Analysis

## Project Overview
This project provides a comprehensive analysis of an employee experience survey conducted at a fictional nonprofit organization. The analysis examines various factors such as Overall Engagement, Job Satisfaction, Work-Life Balance, Compensation Satisfaction, and the impact of demographics (age, gender, ethnicity) on these factors. Both descriptive and inferential statistical methods are used to derive key insights and provide actionable recommendations.

## Table of Contents
- Project Overview
- Data Description
- Analysis Summary
  - Descriptive Statistics
  - Inferential Statistics
  - Correlation Analysis
- Key Findings
- Recommendations
- Conclusion
- How to Run the Analysis
- Dependencies

## Data Description
The dataset contains responses to various questions on employee engagement and job satisfaction, covering areas such as:
- **Overall Engagement**: How engaged the employee feels.
- **Job Satisfaction**: The employee's overall satisfaction with their job.
- **Work-Life Balance**: The extent to which the employee feels they have a good work-life balance.
- **Demographic Information**: Includes age, gender, ethnicity, and department.

## Analysis Summary

### Descriptive Statistics
- **Mean, Median, Mode, Standard Deviation** were calculated for key metrics such as Overall Engagement and Job Satisfaction.
- Trends were identified based on age, gender, ethnicity, and department.
  - **Example Insight**: Employees in the 45-54 age group reported lower satisfaction with work-life balance than other age groups.

### Inferential Statistics
1. **Hypothesis Test**:
   - A **two-sample t-test** was conducted to examine whether there is a statistically significant difference in **Job Satisfaction** between employees in the IT and HR departments.
   - **Null Hypothesis**: There is no difference in Job Satisfaction between IT and HR departments.
   - **Results**: The test found a significant difference, indicating that the IT department reports lower job satisfaction than HR.

2. **Correlation Analysis**:
   - A **correlation analysis** was performed to determine if there is a relationship between **Work-Life Balance** and **Overall Engagement**.
   - **Correlation Coefficient (r)**: The analysis found a strong positive correlation (r = 0.75), suggesting that better work-life balance is strongly associated with higher overall engagement.

### Key Findings
- Significant differences in **Job Satisfaction** were found between departments, especially in IT vs. other departments like HR and Design.
- **Work-Life Balance** is a key driver of **Overall Engagement**.
- Differences in satisfaction levels were observed across **age groups** and **genders**, highlighting areas that need attention.

## Recommendations
Based on the findings, the following actions are recommended:
1. **Enhance Job Satisfaction in IT**: Conduct focus groups to identify specific issues and create targeted interventions.
2. **Implement Age-Specific Initiatives**: Address the unique needs of different age groups, particularly employees aged 45-54, who report lower satisfaction.
3. **Promote Work-Life Balance**: Offer flexible work arrangements, especially for employees in the 45-54 age bracket.
4. **Address Gender Disparities**: Review and adjust workplace policies to ensure equitable support and flexibility for all genders.
5. **Foster Inclusivity**: Implement initiatives that promote equity across all ethnicities, focusing on those reporting lower satisfaction.

## Conclusion
The analysis revealed critical insights into the organization’s workforce dynamics, emphasizing the importance of addressing departmental and demographic differences in job satisfaction. The strong correlation between **Work-Life Balance** and **Overall Engagement** highlights areas for immediate action to improve employee experience.

## How to Run the Analysis
To replicate the analysis on your machine:
1. Clone this repository:
   ```bash
   git clone https://github.com/VasuGadde0203/employee-survey-analysis.git

## Dependencies
- **Python 3.x**
- **Pandas**
- **NumPy**
- **SciPy**
- **Matplotlib/Seaborn for visualizations**
- **Jupyter Notebook (optional)**
