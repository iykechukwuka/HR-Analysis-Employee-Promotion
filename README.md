# HR-Analysis-Employee-Promotion
The goal of this project is to analyze factors influencing employee promotions and predict whether an employee will be promoted based on several demographic, performance, and training/test-related attributes. The analysis will provide insights into key variables affecting promotions and help develop a predictive model using Power BI.
Dataset Overview:
The dataset contains the following information about employees:
•	employee_id: Unique identifier for each employee.
•	department: The department in which the employee works (e.g., Sales & Marketing, Operations, Technology).
•	region: The geographical region where the employee is based.
•	education: The highest educational qualification (Bachelor’s, master’s & above, etc.).
•	gender: Gender of the employee.
•	recruitment_channel: The source from which the employee was recruited (sourcing, other).
•	no_of_trainings: The number of trainings attended by the employee.
•	age: Age of the employee.
•	previous_year_rating: The employee's performance rating from the previous year.
•	length_of_service: Total number of years the employee has worked in the company.
•	awards_won: Whether the employee has won any awards (1 for yes, 0 for no).
•	avg_training_score: The average score achieved by the employee in training programs.
•	is_promoted: Whether the employee was promoted (1 for yes, 0 for no).
Key Metrics:
1.	Promotion Rate: The percentage of employees who have been promoted.
2.	Age Distribution: Age of employees segmented into ranges.
3.	Training Participation: Average number of trainings attended and its relationship with promotion.
4.	Length of Service: Total years of service and its correlation with promotion likelihood.
5.	Previous Year Rating: The impact of last year’s performance ratings on the promotion decision.
6.	Awards Won: The percentage of employees who won awards and how it relates to their chances of promotion.
7.	Education Level: The impact of education (bachelor’s vs. Master’s) on promotion opportunities.
8.	Departmental Influence: How promotion rates vary across departments.
Analysis Steps:
1.	Data Cleaning and Preprocessing:
a.	Handling missing values for critical columns such as education and previous_year_rating.
b.	Converting categorical variables (e.g., department, recruitment_channel, region) into appropriate dummy variables.
2.	Exploratory Data Analysis (EDA):
a.	Demographics Analysis: Understanding the distribution of employee demographics like age, gender, and education level.
b.	Performance Factors: Exploring relationships between performance indicators (e.g., previous year ratings, training score, awards) and promotions.
c.	Department-wise Promotion Rate: Analyzing the promotion rate across various departments.
3.	Data Modeling:
a.	Using Power BI’s Key Influencers Visual to determine the key factors influencing promotions.
b.	Building a predictive model by evaluating how various factors (age, previous ratings, training, education, etc.) affect the probability of promotion.
4.	Visualization:
a.	KPI Dashboard: To track key metrics such as promotion rate, total awards won, and average training score.
b.	Bar Charts: Display promotion rates by department and Employee by region.
c.	Pie Charts: Promotion rates by Education level, Employee by education.
d.	Slicers: Recruitment channel and Number of trainings.
e.	Column Chart: Showing correlations between continuous variables like age range, training score range, and previous year rating.
Key Insights:
•	Employees with higher previous year ratings tend to have a better chance of getting promoted.
•	Length of service beyond a certain threshold correlates positively with promotions.
•	Employees with a higher number of trainings and better training scores are more likely to be promoted.
•	Awards won are a strong indicator of potential promotion.
•	Education level (master’s & above) provides a slight advantage in promotion likelihood, but the difference isn't substantial.
•	Some departments (e.g., Sales & Marketing, Operations ,Technology) have higher promotion rates compared to others (Finance, HR, R&D, and Legal).
Predictive Modeling:
Using Power BI’s AI Insights and the Key Influencers Visual, we built a model to predict promotions based on several factors. Key variables include:
•	Previous Year Rating: High ratings indicate a higher likelihood of promotion.
•	Length of Service: Employees with a longer tenure are more likely to be promoted.
•	Training Score: Employees with higher training scores tend to have better promotion prospects.
•	Awards Won: Winning an award significantly boosts the chances of promotion.
Conclusion:
By analyzing the dataset, we identified key factors influencing employee promotions. The insights derived from the analysis can help HR departments tailor their training and test programs, evaluate employee performance more effectively, and ensure that deserving candidates are promoted. Furthermore, the predictive model provides a robust framework for making data-driven promotion decisions.
