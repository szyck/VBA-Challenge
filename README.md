# VBA-Challenge
## Overview
  The purpose of this project was to refactor code used in the analysis of stock trading. The old code used two for loops to iterate through every row for each ticker. The new code uses arrays to store the ticker volumes, starting prices, and ending prices so that only one loop is needed to iterate through the rows. Each method is compared in terms of time it took to run. 
## Results
  Both codes output the exact same values for the entries. However, the refactored code runs many orders of magnitude faster than the old code. This is true for both 2017 and 2018, and the old code does not even format the cell colors.
 
![2017 Refactored Analysis](https://github.com/szyck/VBA-Challenge/blob/main/Resources/VBA_Challenge_2017.png)
![2018 Refactored Analysis](https://github.com/szyck/VBA-Challenge/blob/main/Resources/VBA_Challenge_2018.png)

While the new code runs in a fraction of a second, the old code takes over 3 seconds.

## Summary
  
  Obviously the end result of the refactored code is superior to the old code in terms of speed and efficiency. However, there are other things to consider when thinking about refactoring code. For our purposes and relatively small dataset, the time cost to refactor our code does not outweigh the brief time the run time saved us. If one did happen to need code to analyze large data sets, the time spent to refactor the code would pay itself back many times over. If starting from scratch, one would want to use the refactored method store the variables we used in arrays.
