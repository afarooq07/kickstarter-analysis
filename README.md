# Kickstarting with Excel

## Overview of Project
An up and coming play writer Lousie launched a fundraising campaign to fund her play, Fever. The campaign lasted about a month and fell a little short of original goal amount. Now she would like to know how different compaigns compare in relation to their launch dates and funding goals.


The scope of the project is to analyze crowdfunding campaigns in the past years (2009-2017) and determine if there are any specific factors that make campaigns successful. Evaluation will be done in excel using pivot tables and charts to visual campaign outcomes vs launch dates and funding goals to uncover trends.


## Analysis and Challenges

The analysis for this report require two types of charts:
	- Outcomes Based on Launch Date
	- Outcomes Based on Goals
	
### Analysis of Outcomes Based on Launch Date
For this part of the analysis, the chart was created based on a pivot table that provides a breakdown of outcomes by launch date months. Pivot table/chart was created as follows: 
- Launched date as rows, row labels were changed to display months
- Outcomes were represented as columns, blank and 'live' values were ignored for the analysis
- Two filters were provided, 1) Parent Categories and 2) YEAR to provide further drilldown capability
	
![](/resources/Theater_Outcomes_vs_Launch.png)


![](/resources/Outcomes_vs_Categories_Pivot_Table.png)


### Analysis of Outcomes Based on Goals
![](/resources/Outcomes_vs_Goals.png)

### Challenges and Difficulties Encountered

## Results

- **What are two conclusions you can draw about the Outcomes based on Launch Date?**
	- May is the most successful month across all years for launching campaigns, with June as the second succesful month
	- December has the lowest success rate with only 50% campaigns hitting their goals, so not a good month to launch a fund raising campaign

- **What can you conclude about the Outcomes based on Goals?**
	- Compaigns with more than 70% success rate had a goal of $5000 or less, with the mean goal of succesful compaigns at $5049. This implies that campaigns with a goal of $5000 or less have a greater chance of succeeding.

- **What are some limitations of this dataset?**
	- The dataset does not indicate the type of fund raising/marketing strategy employed to draw attention and raise funds. For example, donation based or rewards based etc. 
	- There aren't any details regarding initial captial used to setup the fundraiser 
	- There is no information on cities/regions where the fundraiser was hosted, so it is impossible to guage if there is a correlation between geography and outcomes
	- The spreadsheet does not include economic conditions during the years which could have been a contributing factor in making a compaign successful.
	- The dataset mostly contains information on US compaigns. So it may not be beneficial for someone in Australia to use this data to plan a fundraiser.


- **What are some other possible tables and/or graphs that we could create?**
 
 	- Depending on what we are trying to evaluate, we can visual data in multiple ways such as stacked chart of outcomes by categories. This will help us visual how different categories performed. We can use year filter to further drill down and see stats for a year. (Please refer to Outcomes_vs_Categories chart below)
 	- We can create a similar chart as above with "Outcomes vs Countries" to see where most of the campaigns were held. (Please refer to Outcomes_vs_Countries chart below)
	- We can create a table of stats with mean and median values of goal and pledged amounts. This will be another way to find a correlation between goal amounts and success rate 
	- Another possibility is to create a pie chart to show percentage of successful, failed etc outcomes for given category or sub-category if we want to focus on a specific area.
	- The last chart (please refer to "Yearly Outcomes by Categories") shows how campaigns in different categories performaned over the years. We can see that largest number of theater related compaigns were launched in years 2014, 2015 and 2016. WE acn also change it to 100% stacked chart to see success and failure rates 

![](/resources/Outcomes_vs_Categories.png)


![](/resources/Outcomes_vs_Countries.png)


![](/resources/Yearly_Outcomes_by_Categories.png)
