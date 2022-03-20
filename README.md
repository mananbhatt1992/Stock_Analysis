# Stock_Analysis

## Overview

Steve's parents are passionate about green energy and since Steve holds a degree in finance they want to be his first clients and invest in DAQO stock.
But Steve wants to analyse other stocs as well since the analysis shows that investment in DAQO might not be a good idea.The idea is to perform the analysis in such a way that at a click of a button Steve can analyse how a stock performed over a perid of year 2017 to 2018.

## Results

**Report for year 2017**

![2017 Data](https://user-images.githubusercontent.com/99941484/159154994-5f97b22e-a616-452a-a57f-1092bdb35ff3.png)

**Report for year 2018**

![2018 Data](https://user-images.githubusercontent.com/99941484/159155057-067a9d89-a043-4137-8485-88873a02f5f6.png)

**Code Run time with out refactoring -2017**

![2017 original](https://user-images.githubusercontent.com/99941484/159155159-c39ab722-db04-4cbf-8934-609661e287e0.png)

**Code Run time with out refactoring -2018**

![2018 original](https://user-images.githubusercontent.com/99941484/159155201-74996b40-a1e4-4357-adfe-a6d81ecb17a3.png)

**Run time with Refatored Code - 2017**

![VBA_Challenge_2017](https://user-images.githubusercontent.com/99941484/159155230-1f6ea3f5-ab64-4581-a641-69f8231bf0ab.png)

**Run time with Refatored Code - 2018**

![VBA_Challenge_2018](https://user-images.githubusercontent.com/99941484/159155243-fbd599a5-8d5e-4415-9392-02b6097885a9.png)

### Analysis of Stock Returns

1. Considering the data we have for all the Stocks we can say that all stocks performed poorly over 2017-2018
2. Steve's Parents wanted to invest in DQ which is not a good idea; though the stock performed well in 2017 with a return of 199.4% but over a period of a year the stock dropped heavily with the return dropping to negative 63%
3. Only the ENPH stock and RUN stock have stayed positive from 2017 to 2018

### Analysis of Run Time

Initial run time took longer as we were using a nested for loop therefore the number of iterations were more than 3000 for each stock ticker refactored code helped reduce time as we used arrays. 

## Summary

### Advantages of refactoring the VBA Script

Run time is shorter with the refactored code

### Disadvantages of Refactoring the VBA Script

Complications in understadning the flow of the logic

### Advantages of refactoring 

1.) Refactoring Improves the Design of Software
2.) Refactoring Makes Software Easier to Understand
3.) Refactoring Helps Finding Bugs
4.) Refactoring Helps Programming Faster

https://stackoverflow.com/questions/43983284/what-are-the-advantages-and-disadvantages-of-refactoring-code-smell-in-software

### Disadvantages of refatoring

https://stackoverflow.com/questions/43983284/what-are-the-advantages-and-disadvantages-of-refactoring-code-smell-in-software

1. It's risky when the application is big 
2. It's risky when the existing code doesn't have proper test cases 
3. It's risky when developers do not understand what's all about
