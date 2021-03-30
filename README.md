## Data Analyst task (The Code Challenge)

  - Identify reasons of profit declining in last few months
  - Using Adventure Works Cycles csv file

### Logical approach
  - Find Sales Regons with small amount of orders
  - Identify "lazy" Sales Persons
  - Identify "bad guys" in Products and track their movement during year 

### Tools
  - Jupyter Notebook for calculation
  - LibreOffice for Presentation

### Solution
If I had access to SQL Server Management Studio (and this data base) I would finish this task in 1 hour max (including potencial optimization).
This analysis could be done in several ways, using:
- Neseted queries
- Stored Procedures
- Temp tables
- CTE

If needed I would create covering Index for better performanse.
  
Since this is the **first** time that I am using Jupyter Notebook and Python, I've used simple groupby logic to get what I need for this task.
I am sure that (similar to SQL approach) this task can be done in several ways in Python, but I din't want to spend more than 6 hours on this solution.

### Usage
1. clone repo under desired directory
2. cd adventure_works_task
3. python3 -m venv .venv
4. source .venv/bin/activate
5. pip install -r requirements.txt
6. jupiter notebook 
