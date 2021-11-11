
# Stock Analysis with VBA

## Overview of Project
The overview of this project was to evaluate the performance of a specific set of stocks and how they performed over a specific year. The analysis from this project can be used to make data-driven decisions regarding which stocks to purchase.  The project was completed uses two separate codes to find and explore how VBA code might be more efficiently.  
### Purpose
The purpose this project was to analyze the total volume and return of a set of stocks over a given year - in this case either 2017 or 2018 but has the flexibility to add in other years of the same stocks, should they become available. The purpose of the project was also to understand how refactoring code has its benefits and challenges.  
## Analysis
The project analyzes two specific parts of the data.  The first analysis sums the total number of stocks traded over the chosen year, by ticker.  This indicates how actively the stocks are traded.  The second analysis calculates the return of the stocks from the first closing cost to the final closing cost, at the ticker level.  

The second part of the analysis was to find the same metrics but to reduce the run time of the code to make it more efficient using different logic, in this case arrays.  Through the screen shots in the resource (https://github.com/julianadvds/stock-analysis/tree/main/Resources) folder, it can be seen that the run time of the refactored code is much faster than when running with the original code. 

  
## Summary

### What are the advantages and disadvantages of refactoring code in general?
    One clear advantage of refactoring the code is the potential to improve run time, which we have proved through the original and refactored code.  By refactoring the code, we are able to find more efficient ways of processing the same information.  Overall, refactoring should improve the overall design of the code.   
    
    A disadvantage of refactoring code is the time investment it takes to prioritize, plan, debug and put the new, refactored code into production.  In some cases, the return on the time investment to refactor the code may not be worthwhile.  In additon, when you are refactoring code, there is always the potential that it will not perform as expected and introduces a certain level of risk, especially for code in production.  The appropriate testing would be required to ensure the there is no impact to the code output.  

### What are the advantages and disadvantages of refactoring code in general?
    With this specific project, the benefit of refactoring code (that we are currently measuring) was a clear benefit in run time.  Rather than having a nested for loop, where the program runs over each row 12 times, the refactored code performs the same output but only runs through the data once.   

    The disadvantage of refactoring this code was the time investment to refactor the code.  For this project,the run time was relatively short (~3).  While the refactored code ran much faster (~0.2s), the overall time savings will likely not be more than the time invested to recode.  In addition, while the code was in process of being refactored, the code was not functional; therefore we were unable to perform the analysis.  

