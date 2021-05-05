# Stock Analysis
## Overview of Project
This project analyzes the annual performance of 12 stocks. One will be able to input either year 2017 or 2018 to be able to pull the total daily volume. Additionally, the ananlysis will output the annual return for each of the stocks for the inputted year so one could easily see whether the stock was succesful throughout the year. This analysis will help review the performance and may help one make investment decisions in the future. 

## Results 
### 2017 Analysis
Based on the 2017 analysis, one can see that overall the stocks performed well. All stocks but one (TERP) had positive returns. Specifically DQ, ENPH, FLSR and SEDG had over 100% in their annual returns. Based on this, we can conclude that the year 2017 was a successful year for the majority of these companies. The analysis was able to be sped up by approximately 0.01 seconds by refactoring the code. 
Following is the analysis ran with the original code
![coderuntime_2017_original](https://github.com/juliacho22/stock-analysis/blob/main/Resources/coderuntime_2017_original.PNG)
Following is the analsys ran with the refactored code
![coderuntime_2017_refactored](https://github.com/juliacho22/stock-analysis/blob/main/Resources/coderuntime_2017_refactored.PNG)


### 2018 Analysis
Based on the 2018 analysis, one can see that overall the stocks did not peform well. All stocks but two (ENPH and RUN) had negative numbers. ENPH had a return of 81.9% and RUN had a return of 84%. Based on this we can conclude that the year 2018 was an unsuccessful year for the majority of these companies. This analysis was also sped by up approximately 0.01 seconds by refactoring the code. 
Following is the analysis ran with the original code
![coderuntime_2018_original](https://github.com/juliacho22/stock-analysis/blob/main/Resources/coderuntime_2018_original.PNG)
Following is the analsys ran with the refactored code
![coderuntime_2018_refactored](https://github.com/juliacho22/stock-analysis/blob/main/Resources/coderuntime_2018_refactored.PNG)

### Recommendation
Based on the analysis of the two years, A recommendation of investing in ENPH and RUN can be made. 
[VBA_Challenge](https://github.com/juliacho22/stock-analysis/blob/main/VBA_Challenge.xlsm).

## Summary 
- What are the advantages of disadvantages of refactoring code? 
Refactoring can be advantageous because it can make the code more efficient reducing the run time and chances of error. If the code takes a lot of time for the user to run, it is worth while to refactor it so the user can save time. Furthermore, it is a great way to organize your code for additional changes. However, some disadvantages of refactoring can be that it takes additional time to refactor a code. If a project has a strict deadline, it may not be the best case to refactor before testing. Additionally, according to Stack Overflow, refactoring can cause a higher chance of risk if the application is to big (source: https://stackoverflow.com/questions/43983284/what-are-the-advantages-and-disadvantages-of-refactoring-code-smell-in-software) 

- How do these pros and cons apply to refactoring the original VBA script? 
In our specific VBA script, we were able to reduce run time. If we were running a larger set of data, this would have been a more significant amount of time as well. The cons that translated were the struggling with prioritization. Because it took me longer to refactor the code, I had to put learning the next modules on hold leading to feeling a little behind in class. However, this is a good reminder to check in on my priorities and study hours. 
