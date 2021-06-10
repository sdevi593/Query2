# Query2
For Placement Test Purpose
SELECT 
  Date, 
  SUM(Sales) OVER(PARTITION BY Date) as Sales
FROM Input
Order BY Date;
