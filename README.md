# Pewlett-Hackard-Analysis

# Module 7 Challenge - SQL

# Overview of the Analysis:

The purpose of the analysis is to provide company Pewlett Hackard with data that identifies
employees eligible for retirement and corresponding data which lists the positions that will
need to be filled. Retirement eligible employees will need to meet certain criteria for the
company to offer packages. Also included in the analysis is a list of employees eligible for
the Mentorship program.

# Results:

Provide a bulleted list with four major points from the two analysis deliverables. 
Use images as support where needed.

- Retirement eligible employees
	1. Large number of employees eligible for retirement. 
  2. There are seven departments impacted with two department titles
	Senior Engineer (29414) and Senior Staff (28254) having the largest numbers.
  
![Retiring_Titles_Summary](/Data/Retiring_Titles_Summary.png)

- Open positions to be filled
	1.  It's a major impact to the entire company if all retirement eligible employees retire.
	2. Pewlett Hackard would need to evaluate by department, the necessity to fill positions.

- Employees eligible for Mentorship Program
	1. There are 1549 employees eligible
	
![Mentorship_Eligibility](/Data/Mentorship_Eligibility.png)

# Summary:

Provide high-level responses to the following questions, then provide two additional queries or tables that 
may provide more insight into the upcoming "silver tsunami."

How many roles will need to be filled as the "silver tsunami" begins to make an impact?
- Further analysis is required to determine which departments have the most impact to the company.
Evalution of current business objectives such as any active, funded projects with deliverables that 
require priority to engineers or general staff to support recent releases of software or hardware.

Are there enough qualified, retirement-ready employees in the departments to mentor the next
generation of Pewlett Hackard employees?
- Employees will need to be hired quickly in order to allow time for mentoring / training. Examine 
the list of employees eligible for the Mentorship program to step in earlier rather than waiting for new hires.

Running two additional queries selecting only active employees, reduces the number of retirees
from 90398 to 72458

![Upd-RetirementCount](/Data/Upd-RetirementCount.png)

![Upd-RetirementEmp](/Data/Upd-RetirementEmp.png)

