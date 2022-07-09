# Overview of Project 

This project was completed with the goal of analyzing stocks from green energy companies in 2017 and 2018 to find the volume traded and rate of return for 12 companies. 

## Results

The code created for this analysis loops through all 12 stocks, finding the volume traded, the starting price, and the ending price. A simple calculation is also included to find the rate of return for each stock to show the yearly performance. Based on the rates of return that are found for 2017 vs. 2018, as shown below, it is clear that the stocks performed better in 2017 than in 2018. The inital stock that was examined, "DQ" did very poorly in 2018 as compared to 2017.

![VBA_Challenge_2017](https://user-images.githubusercontent.com/105682444/178123509-94a09e01-ec92-4ad1-9ebc-a89e63a0ee20.png)
![VBA_Challenge_2018](https://user-images.githubusercontent.com/105682444/178123510-b41ed8f9-ea66-415d-9076-819df392a86e.png)

The code was also refactored in the VBA_Challenge file to remove a nested loop and allow for faster results from the macro. I have included screenshots comparing the Green Stocks run time to the refactored VBA Challenge code below for 2017. The runtime difference is similar when running 2017 or 2018.

![Green_Stocks_2017](https://user-images.githubusercontent.com/105682444/178123543-629320b4-ee50-49f1-8257-757891bb5591.png)
![VBA_Challenge_2017](https://user-images.githubusercontent.com/105682444/178123545-50b2a4a4-13e3-4740-970c-b901fe498aec.png)

## Summary

####Advantages and Disadvantages of Refactoring Code

A clear advantage of refactoring this code was improving the runtime, it also simplifies the code to be used in different projects as it is less specific to one workbook or analysis. A disadvantage could be losing functionality while refactoring, so it is always important to have your original code saved for backup or reference.

These pros and cons apply to refactoring this specific VBA script. Without a strong grasp of the syntax, refactoring already working code could also be a con.
