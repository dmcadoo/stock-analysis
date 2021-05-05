# Module 2 VBA Stock Challenge
## Project Overview: Refactoring Stock Analysis VBA Script for efficiency.

## Purpose
### The document works to compare different years (2017 & 2018) stock volume and annual return. The Purpose of this challenge was refactoring a previous working VBA macro, which we measured in time. 

## Analysis/Results
### Our document included: Stock symbol, Date	Open, High, Low, Close, Adj Close and Volume. Using our custom VBA macros, we were able to calculate the Total Daily Voulme and Percent Return for the twelve different stock symbols, for two separate year intervals. By creating a tickerindex variable in our loops, we were able to save four tenths of a second (.4s) in run time. [Original 2017 Run Time](https://github.com/dmcadoo/stock-analysis/blob/main/Resources/All%20Stocks%202017%20time.png) [Original 2018 Run Time](https://github.com/dmcadoo/stock-analysis/blob/main/Resources/All%20Stocks%202018%20time.png) [2017 Reformatted](https://github.com/dmcadoo/stock-analysis/blob/main/Resources/All%20Stocks%20reformatted%202017%20time.png) [2018 Reformatted](https://github.com/dmcadoo/stock-analysis/blob/main/Resources/All%20Stocks%20reformatted%202018%20time.png)

##Summary

###Refactoring code can be a good tool for maintainability, speed, and ability to understand. It can often lead to code that is easier to read and less complex. Well refactored code can also serve as a starting point or template for other projects. 
###While refactoring code is usually a sign of diligence and foresight, sometimes the ends do not justify the means. The time and resources devoted to refactoring may not be cost beneficial and may lead to other unintended consequences. While our process did cut the overall time of execution, four tenths of a second(.4s), it was quite insignificant compared to the time to plan, test, and execute the new code. Refactoring code over a larger project or dataset may result in larger implantation time and end in broke code, new bugs, or create even more complex problems.
