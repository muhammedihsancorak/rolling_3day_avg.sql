# Rolling 3-Day Average of Automation Runs (MySQL 5.7)
# rolling_3day_avg.sql

## Problem
Calculate the rolling 3-day average of total automation runs per day for March 15.

## Data Observation
The provided dataset only contains records from January 2021.
There is no data available for March, so a direct calculation for March 15 is not possible.

## Solution Approach
To demonstrate the correct logic, the rolling 3-day average was calculated for
January 15, 2021, using data from January 13–15.

Each of those days contains 4 automation runs, resulting in:

**Rolling 3-day average: 4.0 runs/day**

## SQL Compatibility
- MySQL 5.7 compatible
- No window functions
- Uses aggregated subqueries and date range joins

## Files
- `rolling_3day_avg.sql` — SQL solution
