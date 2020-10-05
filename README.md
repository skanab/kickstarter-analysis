# Kickstarting with Excel

## Overview of Project

Visualize Kickstater theater campaign outcomes based on their launch dates and their funding goals. 

### Purpose
Determine the optimal campaign launch dates for theater campaigns and to understand the correlation between funding goals and campaign outcomes.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
I created a pivot table and sorted each project into a range based on the month it launched and captured the project's funding outcomes. I used this data to chart the determine the best months to start a Kickstarter campaign.

![Outcomes vs Goals](https://github.com/skanab/kickstarter-analysis/blob/master/Resources/Outcomes_vs_Goals.png?raw=true)

### Analysis of Outcomes Based on Goals
I crated goal dollar amount ranges and sorted the play projects into their corresponding goal range with the countifs formula. I used the summarized data to visualize the percentage of successful, failed, and canceled plays based on its goal range.

<Insert Graph>

### Challenges and Difficulties Encountered

While Goal amount and launch date give us a baseline to work from there are still many other factors that determine the outcome of a campaign.

A couple of examples:

1) Staff picks have a 90% chance of being funded regardless of launch date or goal amount.
2) How much and the types of marketing a campaign deploys to bring attention to their Kickstarter.
3) Landing Page Hits
4) Conversion Rates


## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
	+ Campaigns launch the highest number of theater projects in May. May may have the most successful Kickstarter campaigns, but it only slightly beats out June and July. September may have fewer projects, but it has the highest percentage of funded projects.
	+ December is the worst month to launch a theater project. The high failure outcome is likely due to holiday and vacation spending taking priority in the family budgets.

- What can you conclude about the Outcomes based on Goals?
	+ The lower the goal amount, the better the chances a campaign has to be funded. Campaigns should strive to keep their budgets < 5,000 dollars based on the data.
		* 76% of successfully funded projects are < $5,000.
		* 90% of successfully funded projects are < $10,000.
	

- What are some limitations of this dataset?
	+ Dataset only includes very high level information regarding location. It is impossible to determine if plays in Los Angeles are funded more often than plays in Nashville.
	+ No donor information.
	 
- What are some other possible tables and/or graphs that we could create?
	+ A graph that shows length of a campaign compared to outcomes.
