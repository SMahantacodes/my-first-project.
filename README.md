# Capstone Project- Python
## The Challenge
Three separate datasets — Employee details, Seniority levels, and Project statuses — were given as the starting point. They were messy, incomplete, and disconnected. The mission was clear: clean, integrate, and analyze the data to extract meaningful insights while navigating real-world data challenges.

### The Process
First Step:
Built three separate DataFrames in Python (Employee, Seniority, and Project) and saved them as .csv files — laying the foundation for all further work.

Filling the Gaps:
Noticed missing project costs. Using a for loop, I implemented a running average technique to impute the missing values, ensuring no project was left incomplete.

Name Makeover:
Split the full names into First Name and Last Name, preparing the data for personalized insights — while gracefully dropping the now-redundant Name column.

One Big Picture:
Merged all three dataframes into a unified view called Final, linking employees, their seniority, and project performance.

Rewarding Success:
Introduced a new Bonus column — rewarding employees who successfully completed projects with a 5% bonus of their project costs.

Handling Setbacks:
For those whose projects failed, I wrote logic to demote their designation levels. Any employee slipping below acceptable designation standards (above level 4) was respectfully removed.

Polishing the Profile:
Formal titles (Mr. or Mrs.) were added based on gender, and the gender column was then dropped to create a cleaner, more respectful dataset.

Recognizing Experience:
Employees older than 29 years were recognized for their experience and promoted up a designation level using an if condition.

Measuring Contributions:
Summarized the total project costs handled by each employee into a new dataframe, TotalProjCost, capturing their financial impact.

Local Talent Search:
Filtered and listed employees whose cities contained the letter "o" — highlighting regional trends and potential hotspots.

Tools & Technologies Used
- Python (Jupyter Notebook)
- Libraries: pandas, numpy
