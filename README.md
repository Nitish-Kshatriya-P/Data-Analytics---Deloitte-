In the virtual internship from Deloitte Australia provided by Forage platform, we had to create a dashboard representing the unhealthy machines that had taken a minimum of 10 minutes for functioning again. So I created a new column that had values 10 for rows that had column value to be 'unhealthy' and 0 for 'healthy'. 

Then plotted 2 charts to show the number of unhealthy machines in each factory at different locations. Added a filter for seeing how many unhealthy machines were present for each department of the facility at each location.

And the task 2 comprised of generating categorical values based on a numeric column in an excel file using the nested IF() statements.
Below was the criteria: 
Equality Score (integer; ranging between -100 and +100; 0 is ideal)

Create a 4th column (Equality class), classifying the equality score into 3 types:
- Fair (+-10)
- Unfair (<-10 AND >10)
- Highly Discriminative (<-20 AND >20)

Examples:
 - 10 → Fair
 - -9 → Unfair
 - -30 → Highly Discriminative
