# Pewlett-Hackard-Analysis

## Overview
The purpose of this analysis was to retrieve the titles of all employees at Pewlett Hackard expected to retire in the near future. Those qualified for retirement at this time must have been born between the years of 1952 and 1955. The data originally showed duplicate entries (a total of 443,308) because some/many of these employees may have held various titles throughout their career at Pewlett Hackard. To remove duplicate entires, the data was further filtered to show the latest/most recent title held by these retiring employees. After the filter, it was determined there are 300,024 actual total employees at Pewlett Hackard.

Additionally, employees eligible for participating in the mentorship program were identified. Qualifications for the mentorship program included current employees who were born in the year of 1965. Those eligible would be mentored by those who are retiring.

## Results
The results of the analysis determined that:
- There are 90,398 employees with impending retirement out of the 300,024 total amount of unique employees at Pewlett Hackard. This encompasses around 30.1% of the total amount of employees. Below shows the query codes for both those who are retiring and the total amount of employees.

![expecting_retirement_code](expecting_retirement_code.png)
![total_employees](total_employees.png)

- The job title with the highest number of employees with forthcoming retirement is "Senior Engineer". There are 29,414 Senior Engineers eligible for retirement. This covers around 32.5% of titles of those who are retiring soon. Senior Staff represent around 31.3% of those retiring, those with the title "Engineer" represent around 15.7%, 13.5% are Staff, Technique Leaders comprise about 5%, and Managers are very miniscule.

![title_retiring](title_retiring.png)

- There are 1,549 employees eligible for the mentorship program. This number represents the number of *mentorees* who will be mentored by the 90,398 retiring employees, the mentors.
- This would mean that there is around a 58:1 ratio of mentors to mentorees.  

![mentorship](mentorship.png)

## Summary
Since there are 90,398 employees expected to retire soon, Pewlett Hackard should highly consider beginning to interview applicants to usher in the next generation of employees to accomodate for those retiring. As these employees retire, existing employees may be promoted into those roles, or perhaps Pewlett Hackard may decide to hire externally to fill roles. However, the mass exodus may not happen all in the same year. The current age for those eligible to reitre in the US is 66 and 2 months for those born in 1955 and earlier. It is not always guaranteed that employees will retire once immmediately eligible. Nonetheless, this is still a significant number of roles to fill. Therefore, Pewlett Hackard should assess the positions of those with forthcoming retirement to decide on which roles they will need to fill. It is natural for exisiting employees to move up and take on vacancies left by those who retire. An additonal query that could be run is to find the titles of existing employees who are not retiring soon. This way, it can be analyzed how many senior positions could be filled by exisitn gemployees and thus, we can determine how many junior position vacancies will open that Pewlett hackard can hire externally from.

Assuming that every employee who is eligible for the mentorship program agrees to join, that would mean there are 1549 mentorees. This means that for every mentoree, there are 58 available mentors. If this is the case, then there is more than enough mentors able to conduct training, but far less mentorees available to be trained. This might not be ideal for Pewlett Hackard. Pewlett Hackard should consider expanding the eligibility requirements for the mentorship program so that there are more mentorees to train. Because if not enough mentorees are trained, then Pewlett Hackard might face an issue of insufficient and capable senior staff to lead the new hires, which will trickle down as the generations of employees continues. Currently, the mentorship program only allows for those born in the year of 1965 to participate in. It would be recommended to expand this requirement to include more years. However, it should be a balanced number between mentors and mentorees. Therefore, additional queries can be ran to expand and filter through the years until a query returns a comparable number to the 90,398 retiring employee mentors. Not every retiring employee may agree to be a mentor, but not every eligible mentoree may want to be mentored either. Therefore, it is important that the numbers are at least within the same comparable range to balance training and minimize negative impact to business to due to incompetent employees.
