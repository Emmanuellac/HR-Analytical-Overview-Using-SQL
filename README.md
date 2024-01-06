# HR-Analytical-Overview-Using-SQL

A Human Resources (HR) dataset typically encompasses a comprehensive collection of information related to an organization's workforce. This dataset is designed to facilitate the management and analysis of various aspects of employee-related data. The dataset often includes structured information about individual employees, such as personal details, job roles, compensation, performance evaluations, and other relevant metrics.
This dataset was extracted from Kaggle.com 
i took so much time to clean and replace some missing values using statistics and the nesseacry formula.
I went forward to load this dataset in Mysql serve which took not upto 15mins to be imported into sql.  i went ahead to create a database and automatical got acess to the dataset in sql.
Below is a general description of the components you might find in a typical HR dataset:
Employee Information:

Personal Details: Name, employee ID, gender, date of birth, contact information.
Employment Details: Hire date, termination date (if applicable), employment status.
Organizational Details: Department, team, manager, location.

Job Details:
Job Title: The position or role within the organization.
Job Level: Indicates the hierarchical level of the position.
Job Responsibilities: A description of the employee's responsibilities and duties.
Salary Information: Compensation details, including base salary, bonuses, and benefits.

Performance Metrics:
Performance Ratings: Scores or evaluations reflecting an employee's performance.
Training and Development: Information about training programs, certifications, or skill development activities.

Time and Attendance:
Attendance Records: Time and attendance data, including clock-in and clock-out times.
Leave Records: Information about vacation days, sick leave, and other types of leaves.

Employee Surveys:
Feedback and Satisfaction: Responses from employee surveys measuring job satisfaction and engagement.
Suggestions and Comments: Employee feedback and comments on various aspects of the workplace.

Employee Relations:
Incidents and Disciplinary Actions: Records of workplace incidents, disciplinary actions, and resolutions.
Grievances: Information related to employee complaints and resolutions.

Diversity and Inclusion:
Diversity Metrics: Data on the diversity of the workforce, including gender, ethnicity, and other demographics.
Inclusion Initiatives: Programs or initiatives aimed at fostering an inclusive workplace.

Succession Planning:
Potential Talent: Identification of employees with high potential for leadership or advancement.
Career Development: Information about career development plans and opportunities.

Exit Interviews: Feedback provided by employees leaving the organization.
Termination Reasons: Reasons for employee terminations, whether voluntary or involuntary.

i did some analysis by taking my time to studie the dataset again, i was able to get alot of ideas on how to improve the Hr demand for job offers i wan also able to figure out that some Hr have a higher number of employees than the rest.

-- SOME QUESTION EXPLORED.
1.Top five(5) most paid Employees AND Position?
2.Employees with terminated contracts and reason for termination?
3.predicting who is going to retire next?
4.BEST Recruitment source if we want to ensure a diverse organisation?
5.State with the highesr Employee? 
6.oldest Employee in the company?
7.Most recruiting managers?
8.Employee marital status AND Position

__SKILLS APLLIED
-Data Cleaning and Preprocessing.
-Statistical Analysis.
-Programming Skills.
-Database Management.
-Critical Thinking.
-Business Acumen.
-Communication Skills.
-Prloblem_solving.
-Attention to Detail.
-Time Management.
-Continuous Learning.

-SOME INTERESTING QUERIES.
-predicting who is going to retire next? 
    This is quite an interesting and trikish question.Here is a reason why, i was able to tell who is leaving next among the Employess using the abesnce field and lowest earners,i used the absence field to tell how frequently an employee has been absent from the office, i also figured out that most of the frequently absent employees have the lowest earning in the company,hence why they're likely to quite soon.
    
-BEST Recruitment source if we want to ensure a diverse organisation?    
looking at the data set you can tell that most of the employees got hired from one source or the other(different media) i was able to perform an analysis with the REcuriment source column and the analysis shows that most of the employes where hired through most through this order 
"INDEED" followed by
"LINKEDIN"
"GOOGLE SEARCH"
"EMPLOYEE REFFERAL"
and "DIVERSITY JOB FAIR".

-INSIGHTS.
-MA has the highes number of employess with a NO of 268 Employees.
-'Zima, Colleen', 'Production Technician might be quiting next with '2' absence record and the lowest earning salary with payment of '$4,5046'
-'King, Janet' is the most paid employee with payment of  $25,0000', position as 'President & CEO'
-'Driver, Elle' is the oldest employee hied on '1/10/2011'



