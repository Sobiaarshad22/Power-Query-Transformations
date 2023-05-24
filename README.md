# Power-Query-Transformations
Create start date and end date columns using #date. These columns should be formatted as dates. Create a column that calculates the number of days between the start and end date columns, using "Number.From" to format the result as a number. 
Create a column that classifies the durations as "short", "medium", or "long" based on the length. There should be no "0" durations. If a duration starts and ends on the same day it should count as 1 day of output. You can account for this by adding 1 to a formula when subtracting two dates from each other. Use your own judgment to determine the appropriate length for each classification.
Create a column to classify the factory output as "low", "medium", "high" based on the value. Use your own judgment to determine the appropriate length for each classification.
Remove all unneeded columns so that only the following remain:
Factory Output
Start Date
End Date
Duration
Duration Classification
Output Classification
