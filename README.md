## Data Analyst task (The Code Challenge)

  - Identify reasons of profit declining in last few months
  - Using Adventure Works Cycles csv file

### Logical approach
	*	Establish the reasons for the reduced profit
	*	Identify bad regions
	*	Calculate negative margin products
	*	Identify bad performance sellers
	*	Track products with week orders

### Solution analysis
If I had access to SQL Server Management Studio (and this data base) I would finish this task in 1 hour max (including potential optimization).
This analysis could be done in several ways, using:
- Nested queries
- Stored Procedures
- Temp tables
- CTE

No need for creating covering Index (for better performance) since we have only 42k rows.
  
Since this is the **first** time that I am using Jupyter Notebook and Python (virtual enviroments as well), I've used simple groupby logic to get what I need for this task. At the end of previosly agreed 6th hour, I've started to format the output in Python.
Kindly note that I've learned this on the way (during this task only).
I am sure that (similar to SQL approach) this task can be done in several ways in Python, but I didn't want to spend more than 6 hours on this solution.

### Tools
  - Jupyter Notebook for calculation
  - LibreOffice for Presentation

### Usage
1. clone repo under desired directory
2. cd adventure_works_task
3. python3 -m venv .venv
4. source .venv/bin/activate
5. pip install -r requirements.txt
6. jupyter notebook 
