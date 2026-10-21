# Mental-Health-and-Lifestyle-Analysis
This project explores mental health indicators and lifestyle habits using a dataset of 2,000 respondents. The analysis focuses on stress levels, sleep categories, daily screen time, social media usage categories, work or study hours categories, age categories, caffeine intake, alcohol consumption, smoking status, gender, and occupation status.

Using Microsoft Power BI, the project transforms raw data into interactive visualizations to identify patterns, compare demographic groups, and understand the distribution of lifestyle behaviours associated with mental well-being.

#  Objectives

Analyse the distribution of stress levels and sleep categories.

Examine daily screen time and social media usage patterns.

Compare work or study hours across categories.

Explore lifestyle indicators across age categories.

Analyse caffeine intake, alcohol consumption, and smoking status.

Present key findings through an interactive Power BI dashboard.

# Tools Used

Microsoft Power BI — dashboard creation and visualization.

Power Query — data cleaning and transformation.

DAX — measures and calculations, where applicable.

Excel or CSV — data storage and preparation, depending on the source format.

# Dataset Description

The dataset contains 2,000 respondents and includes the following variables:

Demographics: Age categories and gender.

Mental Health: Stress levels and sleep categories.

Screen Time: Daily screen time categories.

Social Media: Social media usage categories.

Work or Study: Reported work or study hours categories.

Lifestyle Habits: Caffeine intake, alcohol consumption, and smoking status.

Occupation: Student, employed, and unemployed categories.


 # Step-by-Step Methodology

Step 1: Data Import

Imported the dataset into Power BI and reviewed its columns, data types, and relevant variables.

Step 2: Data Cleaning

Used Power Query to check for missing values, duplicate records, inconsistent category names, and incorrect data types. Any corrections should be documented according to the actual cleaning performed.

Step 3: Data Transformation

Prepared the variables for analysis, ensuring that categorical fields were suitable for grouping and numerical fields were correctly formatted for aggregation.

Step 4: Data Analysis

Compared respondent counts across lifestyle, mental health, age, gender, and occupation categories. Appropriate measures were used to summarize the data.

Step 5: Dashboard Development

Created KPI cards, bar charts, a pie chart, and a doughnut chart to present the findings clearly.

Step 6: Insight Generation

Reviewed the visualizations to identify dominant categories and differences between groups without assuming that observed patterns establish cause and effect.


# Dashboard Visualizations and Key Findings
<img width="1606" height="915" alt="Image" src="https://github.com/user-attachments/assets/fc97f0de-0f90-49a4-8de5-339e0a185d41" />

Gender Distribution

The dashboard contains 992 male respondents (49.6%) and 1,008 female respondents (50.4%), giving a total of 2,000 respondents.

Daily Screen Time

Very high screen time is the largest category, with 1,164 respondents, followed by high screen time with 626. Moderate screen time accounts for 204 respondents, while low screen time accounts for 6.

Sleep Categories

Moderate sleep is the largest displayed category, with 695 respondents. The recommended sleep range has 366 respondents, short sleep has 336, longer sleep has 311, and very short sleep has 292.

Social Media Usage

Moderate usage is the largest category, with 604 respondents (30.2%), followed by high usage, with 524 respondents (26.2%). The chart also presents low, very low, and very high usage categories.

Stress Levels

The dashboard displays 487 respondents in the high-stress category, 290 in moderate stress, and 221 in low stress. These figures describe the categories shown and may not represent the complete distribution if additional categories exist.

Work or Study Hours

The very high category contains 577 respondents, high contains 434, low contains 412, moderate contains 384, and very low contains 193. This comparison highlights the distribution of respondents across the reported work or study hour categories.

Caffeine Intake and Alcohol Consumption

A clustered column chart compares caffeine intake and alcohol consumption across five age categories: 16–19, 20–29, 30–39, 40–49, and 50–59. This helps identify differences in the displayed measures between age groups.

Smoking Status by Age Category

The chart displays counts of 253 for ages 40–49, 233 for ages 50–59, 211 for ages 20–29, 200 for ages 30–39, and 87 for ages 16–19. These counts should not be interpreted as smoking rates without the total population of each age group.

Occupation Status

The dashboard displays 677 students, 677 employed respondents, and 646 unemployed respondents, providing an overview of occupation status in the dataset.

## In-depth insights from the Mental Health Dataset

The most important findings are:
- Stress is associated with the depression indicator: the correlation is approximately (r=0.225), a modest positive relationship.
- Night-time device usage is associated with higher anxiety and burnout indicator rates in this dataset.
- Screen time has a modest positive relationship with the depression indicator, while sleep duration has a small negative relationship.


Age distribution
- Mean age: 37.7 years
- Median age: 38 years
- Middle 50% of ages: approximately 27–49 years
- Minimum and maximum ages: 16 and 59 years
The sample covers teenagers through late-middle adulthood, with its center around the late thirties. 

The linear correlation between age and the depression indicator is close to zero ((r\approx-0.007)). 
Interpretation: Age may still matter in particular age bands or through interactions with occupation, sleep, or workload. A near-zero overall correlation does not rule out more complex age-related patterns.

3. Stress and mental-health indicators
Stress is one of the most informative variables in this dataset because it has the strongest observed linear associations with all three mental-health indicators among the numeric lifestyle variables examined.
Correlation between stress and mental-health indicators
Pearson correlation between Stress_Level and each binary indicator. Larger positive values indicate a stronger positive linear association.

# Key Insights

High and very high screen time account for most respondents.

Moderate sleep is the largest displayed sleep category.

Moderate social media usage is more common than any other individual usage category.

High stress is the largest of the three stress categories displayed.

Work or study hours vary across the five reported categories.

The gender distribution is almost evenly balanced.


# Recommendations
## Based on the Mental Health and Lifestyle Analysis, the following recommendations are proposed:

1. Promote Healthy Screen Time Habits: Since most respondents fall into the high and very high screen time categories, encourage balanced digital habits, regular screen breaks, and reduced unnecessary screen use.

2. Improve Sleep Habits: Encourage consistent sleep schedules and healthy sleep routines. Further analysis should investigate whether sleep categories are associated with respondents’ stress levels and screen time.

3. Strengthen Stress Management: The high-stress category contains 487 respondents. Consider promoting stress-management education, relaxation techniques, healthy work-life balance, and access to appropriate mental health support.

4. Encourage Balanced Social Media Use: Promote mindful social media engagement and offline activities. Analyse whether higher social media usage categories correspond with different stress or sleep patterns.

5. Promote Healthy Work and Study Routines: Explore the relationship between work or study hours and stress levels. Encourage regular breaks, manageable workloads, and adequate rest where appropriate.

6. Support Healthy Lifestyle Choices: Provide general awareness about caffeine consumption, alcohol use, and smoking. Examine differences across age categories to identify areas for further research and targeted health education.

7. Conduct Further Data Analysis: Use Power BI filters, cross-tabulations, and appropriate statistical tests to examine relationships among stress, sleep, screen time, social media usage, and work or study hours.


# Conclusion

This project demonstrates how Power BI can be used to transform mental health and lifestyle data into meaningful visual insights. By analysing stress levels, sleep, screen time, social media usage, work or study hours, age categories, and other lifestyle indicators, the dashboard provides a foundation for further exploratory analysis and data-driven research.


# AUTHOR: ADEPELUMI
