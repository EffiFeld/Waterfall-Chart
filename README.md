# Waterfall-Chart
Small workflow for making a waterfall chart.
A lot of the code here is attributed to kind citizens on stackoverflow and elsewhere.


Often I want to show a comparison of budgets or incremental from a model FY-to-FY or Q-to-Q.
Often charts like:

![](all_others.png)

Some people love waterfall charts for this task - these are annoying charts to make.
Essentially you are plotting the differences between groups leading to the new total.  
So:  
  - If an item increases YoY - it is represented by a box with height of 0 - growth  
  - And if an item decreases - it is represented by a box with 0 - minus(growth)  
  - And the start of each box relies on the next as it "flows" towards the new total  
  
![](waterfall.png)

Also - needed the following abilities:  
  - Quickly decide on which quarters and years are included
  - Maintain colors
  - Easily add a new category or switch level of granualarity

