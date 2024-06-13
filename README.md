# HR Analytics in Power BI

## Project Overview
This project aimed to build a comprehensive HR analytics report for Atlas Labs' HR team using Power BI. The report helps track key HR metrics and factors impacting employee attrition.

## Goals and Objectives
- **Primary Goal:** Monitor key HR metrics on employees.
- **Secondary Goal:** Understand what factors impact employee attrition.

## Scope of Work
Using the Kimball model approach, I worked with facts and dimensions to build a data model. A date dimension table will was added, followed by the analysis.

## Target Audience
Atlas Labs HR team

## Data Sources
- `Employee.csv`
- `EducationLevel.csv`
- `PerformanceRating.csv`
- `RatingLevel.csv`
- `SatisfiedLevel.csv`

The dataset includes a fact table storing performance ratings and five dimension tables: Employee, EducationLevel, RatingLevel, SatisfiedLevel, and Date. The final data model follows a snowflake schema.

## Metrics and KPIs
Key metrics and KPIs used to measure success include:
- Attrition rate
- Employee demographics
- Performance ratings
- Job role distribution
- Departmental metrics

## Overarching Insights

![HR Analytics Overview]()
### Attrition Rate
- **Overall Attrition Rate:** 16.1%
- **Department and Job Role with Highest Attrition Rate:** Sales and Sales Representative (39.8%)
- **Frequent Travelers' Attrition Rate:** 24.9%

### Employee Growth
- The biggest growth in new employees was in Q1 2022, with 130 new hires.

### Department Distribution
- Over half of the active employees work in the technology department.
- Most common job roles: Software Engineer and Data Scientist.

### Demographics

![HR Analytics Demographics]()
- Majority of employees are aged 20-29.
- Employees identifying as white have the highest average salary.
- Employees identifying as mixed or multiple ethnicities have the lowest average salary ($106K).
- Women make up only 2.7% of the organization.
- 
![HR Analytics Performance Tracker]()

- Managerial rating level and self-performance level often don't align.

![HR Analytics Attrition]()

## Recommendations
1. **Support Employee Growth:**
   - Organize individual meetings to discuss needs and create improvement plans.
   - Implement regular training and development programs to upskill employees.
2. **Review Travel Policies:**
   - Survey employees on feelings about travel frequency and adjust policies accordingly.
3. **Improve Hiring Strategies:**
   - Focus on diversity hiring to increase the representation of women and other underrepresented groups in the organization.
   - Enhance onboarding processes to ensure new employees are well-integrated and supported from the start.
4. **Monitor and Adjust Compensation:**
   - Regularly review and adjust salaries to ensure competitiveness and fairness.

## Conclusion
The Atlas Labs HR team can now easily navigate key metrics related to company employees, enabling more informed decisions on hiring, monitoring diversity and inclusion, and tracking employee performance and attrition.

## How to Run the Project

1. **Clone the repository:**
    ```bash
    git clone https://github.com/yourusername/data-analyst-portfolio.git
    cd data-analyst-portfolio/hr-analytics
    ```
    
2. **Open the Power BI Report:**
    - Open the `HR Analytics Report.pbix` file in Power BI Desktop.
    - Review and interact with the dashboards to explore the analysis.

3. **Review the Analysis and Findings:**
    - Examine the visualizations and insights provided in the Power BI report.
    - Consider the recommendations and how they can be applied to improve HR metrics.

## Contact Information

For any questions or further information, please feel free to contact me:

- **LinkedIn:** [My LinkedIn Profile](https://www.linkedin.com/in/krystalbrantley)

Thank you for reviewing this project!
