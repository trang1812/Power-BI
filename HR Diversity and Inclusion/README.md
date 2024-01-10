# HR DIVERSITY AND INCLUSION

## Problem
Human Resources at a telecom company is highly into diversity and inclusion. They’ve been working hard to improve gender balance at the executive management level, but they’re not seeing any progress. To them, diversity and inclusion are business imperatives, not just nice-to-haves. But actually achieving this and unlocking its potential involves a whole set of practical challenges. To improve Diversity and Inclusion, HR reaches out to analysis team to seek support with comprehensive insights into workforce, presented visually for easy comprehension by management.

## Purpose
The purpose of this analysis is to create a dashboard in Power BI for the HR department that reflects relevant Key Performance Indicators (KPIs) in hiring, promotion, performance, and turnover. Besides, analysis would identify and discuss potential root causes for the slow progress in achieving gender balance at the executive management level. 

## Dataset
The table below shows the metadata:
| | |
| --- | --- |
| File name | 03 Diversity-Inclusion-Dataset |
| Format | .xlsx |
| Size | 176 KB |
| Fields | 32 |
| Entities | 500 |

The table below shows field's names and their description:
| Fields | Description |
| --- | --- |
| Employee ID | Unique number of the employee in the dataset |
| Gender | Gender of the employee |
| Job Level after FY20 promotions | Job level of the employee after being promoted in FY20 |
| New hire FY20 | If the employee is a new hire in FY20 |
| FY20 Performance Rating | Performance rating in FY20 |
| Promotion in FY21 | If the employee is promoted in FY21 |
| In base group for Promotion FY21 | If the employee is selected for promotion in FY21 |
| Target hire balance | Target hire balance of employees |
| FY20 leaver | If the employee leaves the company in FY20 |
| In base group for turnover FY20 | If the employee is in a group for turnover in FY20 |
| Department | The department each employee belongs to as of January 7, 2020 |
| Leaver FY | If the employee leaves in an FY |
| Job Level after FY21 promotions | Job level of the employee after being promoted in FY21 |
| Last Department in FY20 | Last department each employee belongs in FY20 |
| FTE group | If the employee belongs to an FTE group |
| Time type	| Contract type employee |
| Department & JL group PRA status | The department and JL group PRA status of the employee |
| Department & JL group for PRA | Department and JL group PRA of the employee |
| Job Level group PRA status | Job level group PRA status of the employee |
| Job Level group for PRA | Job level group PRA of the employee |
| Time in Job Level | Time in job level of the employee |
| Job Level before FY20 promotions | Job level of the employee before being promoted in FY20 |
| Promotion in FY20 | If the employee is promoted in FY20 |
| FY19 Performance Rating |	Performance rating of the employee in FY19 |
| Age group | Age group of the employee |
| Age | Age of the employee as of January 07, 2020 |
| Nationality |	Nationality of the employee at the state level |
| Region group: nationality | Nationality of the employee at the country level |
| Broad region group: nationality | Nationality of the employee at the regional level |
| Last hire date | Last hire date of the employee |
| Years since the last hire | Number of years since the last hire of the employee |
| Rand | A random number for each entry in the dataset |

## Analysis
![Dashboard](https://github.com/trang1812/Power-BI/assets/126154468/c2e5b343-663f-4bc2-a0d1-59389374c615)

### Overview
* There were 500 employees from 2019, 41% of which is female. Employees are mainly at young age groups (20-39)
* The average tenure of employees is 3.86 years. HR and Strategy departments have longer tenures. The observed gender disparity in tenure (4.2 years for male employees vs. 3.38 years for female employees) is a critical point of consideration. Potential factors contributing to this disparity might include gender biases, differences in career development opportunities, work-life balance challenges, or other gender-specific issues.
* The majority of employees, accounting for 88%, work in the Operations, Sales & Marketing, and Internal Services departments. The Operations department has achieved gender balance, with 49% of its workforce being female. The HR is the only department where females outnumber males, constituting 71% of the staff. Conversely, the remaining departments show a noticeable skew towards male employees, with more than 65% of their workforce being male.
* Higher-level job profiles have a greater representation of male employees, with over 80% of individuals holding roles such as Senior Manager, Director, and Executive being male. This suggests the possibility of systemic obstacles or insufficient support for female employees into leadership roles.
### Hire	
* Currently (2020), there are 453 employees, 66 of them being new hires. The gender balance among the new hires is close to the target value of 0.5, showing the effort of HR department to improve gender balance.
* New hires are often in young age group, from Europe countries.
* Most new candidates are recruited for the Officer-level positions.
### Turnover
* Turnover rate is 9%, out of which 26 are males & 21 are females.
* Majority of employees leaving the company were within the age group of 40-49, having an average tenure of 5.38 years with the company. The reasons behind this trend could stem from various factors. Career Stagnation is one of the reasons. Employees may perceive a lack of opportunities for career growth within the company. If they feel that their skills and experience are not being adequately recognized, they might seek new challenges and advancement elsewhere. Additionally, competitive salary and comprehensive benefits are vital factors in retaining experienced employees. If the company is not keeping pace with industry standards in terms of compensation packages or fails to address concerns related to benefits, employees may be inclined to explore opportunities where their financial needs are better met.
* All resigning employees are from European countries, with a significant portion (57%) being Swiss. Cultural differences between the company's work environment and the expectations of employees may contribute to the resignations from European employees. Besides, if the company is unable to match the competitive employment packages offered by other EU organizations, employees might opt for positions that provide better financial incentives and job security.
### Promotion
* A notable portion of employees seems to have remained at their current job level for over two years. Promotions have been slow and female directors, in particular, require more time to be considered for executive positions compared to their male counterparts.
* There is a higher rate of promotions for female Junior Officers, the promotion rate decreases at the senior level. This discrepancy could be linked to factors such as performance evaluations, insufficient support, and a need for enhanced training to boost overall performance.
* Even though females generally outperform males on average, they face a lower likelihood of being promoted to higher positions, with promotion rates at 9% for females compared to 11% for males. The problem is pronounced at executive management level. One possible reason for the slow progress towards gender balance at high job levels is that performance evaluations for promotions may lack complete objectivity and honesty. This situation could lead to qualified female candidates being disregarded, even when they outperform their male counterparts.
