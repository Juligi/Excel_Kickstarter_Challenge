# ***Kickstarting with Excel***

## **Overview of Project**
This analysis reviews how various plays funding campaigns fared in relation to their launch dates and their funding goals.

### **This Project's Purpose**
This analysis will visualize the campaign outcomes based on their launch date and their funding goals.  

## ***Analysis and Challenges***
 
### **Analysis of Outcomes Based on Launch Date**
**Outcomes based on launch Date**:
1. To visualize all campaign outcomes based on 1) Successful, 2)failed or 3) cancelled based on launch classifications the full data was analyzed by creating a pivot table. 
2. A narrow view of theater campaigns was then created by filtering theathers only from the parent category.
3. A count of outcomes by month for all years was created 
4. This allowed for a final pivot view to create a linear chart visualization of the relationship between theater outcomes based on its launch month.

### ***Analysis of Outcomes Based on Goals***
An analysis of "play" outcomes based on dollar goal was requested that visualized the percentage of success, fail, or cancellation percentages.

To complete the analysis, 
1. the full data set was used to separate the data into dollar-amount ranges to associated based on their amount that ranged from $1000 to 50000, in 5000 increments.
2. Countifs functions were primarily used to populate the number of successful, number failed, and number of cancelled plays.
3. This allowed to calculate and graphically visualize the total number of play projects and the associated % of successful, failed or cancelled.

### Challenges and Difficulties Encountered
The biggest challenge was how to appropriately create the function(s) such as countifs to appropriately accept and corrrectly calculate based on several criteria. 

## **Results**

- **Conclusions: Outcomes based on Launch Date**
	1. May, June, and July respectively had the most successful and failed launches
	2. January had the most cancelled theater projects.  

- **Conclusions: Outcomes based on Goals**
	1. 74% plays campaings with less than $1000 pledges were most successful
	2. The more was pledged towards a play project or higher the $ contribution, the more likely the project was to fail

- **Limitations of this dataset**
	- No data to make conclusions for how long a project ran to determine if project launch correlates to actual performance success or other attributes for success, failure or cancellation. 

- **Gaps:** possible tables and/or graphs to gain additional insights recommended
	1. There is an opportunity to review the numbers of backers and outcome based on goals, pledges and backers count.
	2. Were staff picks more likely to be successful, fail or be cancelled in any given year.  

