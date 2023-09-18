This repository is my note from 2 week learning at SQL Crash Course from [Uplimit (Formerly CoRise)](https://uplimit.com).  There is 2 .IPYNB file of the project that can be access inside week 1 and week 2 folder. Key learning from this course is
- filtering and sorting data
- aggregations
- complex filtering logic and built-in date/string predicates
- GROUP BY and HAVING clause
Last but not least I put query structure of a simple aggregation below
```SQL
SELECT 
	[* OR column(s)] 
FROM [table] 
WHERE [conditions]
GROUP BY [columns] 
ORDER BY [columns] 
LIMIT [number];
```