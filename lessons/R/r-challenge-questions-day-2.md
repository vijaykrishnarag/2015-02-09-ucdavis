R Challenge Questions, Day 2
========================================================

Start-up challenge
====================
To refresh our memories from yesterday, let's all begin with an exercise:

1.  Load the "survey" data into R as a `data.frame`
2.  Print the first 20 values of the column named "species"
3.  Print the last 20 values of the column names "sex"

Challenge
=========

1. What does the following do?

  
  ```r
  surveys_DO$month[2] <- 8
  ```
 
2. Use the function `subset` twice to create a `data.frame` that contains all
individuals of the species "DM" that were collected in 2002.
  * How many individuals of the species "DM" were collected in 2002?
  
Challenge
=========

Use the same approach we used to add genera to add a column of species names in the `surveys` data
frame.

Challenge
=========

Construct a new `data.frame` that only includes data
for the years 2000 and 2001.

Challenge
=========

1. To determine the number of elements found in a vector, we can use
use the function `length()` (e.g., `length(surveys$wgt)`). Using `length()`, how
many animals have not had their weights recorded?

2. What is the median weight for the males?

3. What is the range (minimum and maximum) weight?

4. Bonus question: what is the standard error for the weight? (hints: there is
   no built-in function to compute standard errors, and the function for the
   square root is `sqrt()`).
   
Challenge
=========

1. Create new objects to store: the standard deviation, the maximum and minimum
   values for the weight of each species
1. How many species do you have these statistics for?
1. Create a new data frame (called `surveys_summary`) that contains as columns:
   * `species` the 2 letter code for the species names
   * `mean_wgt` the mean weight for each species
   * `sd_wgt` the standard deviation for each species
   * `min_wgt`  the minimum weight for each species
   * `max_wgt`  the maximum weight for each species
   
Challenge
=========

1. Create a new plot showing the standard deviation for each species.
