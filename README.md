# An Analysis of Kickstarter Campaigns.
Kickstarter is a website that allows individuals to finance creative ideas. This study looks at global Kickstarter campaigns from 2009 to 2017 and attempts to identify patterns in the theater field, particularly plays.
### Purpose
This project is designed to investigate how different play campaigns performed in terms of their launch dates and financial objectives, as well as providing insight into how such plays fared. 
### Analysis of Outcomes Based on Launch Date
Throughout the study, we discovered patterns that were responsible for the success of many plays in the United States. We also included data visualization to help Louise understand it and make the most of this information.

After learning that Louise was starting a theatre campaign in the United States, we filtered the data to show results for all US theater fundraisers. We also used conditional formatting to highlight the information by color-coding successful, failed, and abandoned efforts.

Since we discovered that the month of a campaign's inception is linked to its success, we built a pivot table to assist Louise choose the most successful date to start her fundraiser.

When it comes to her fundraising objective, we utilized descriptive statistics to assist Louise determine an attainable amount.
### Analysis of Outcomes Based on Launch Date
We used the pivot table to filter by successful, failed, and canceled theatrical fundraiser based on the month. After creating the chart, we learned that campaigns sponsored during the summer months had a higher success rate than those sponsored throughout the rest of the year. The line graph may be found below:
![Outcomes Based on Launched Date](https://github.com/damienfranco/kickstarter-analysis/blob/main/Resources/Theater_Outcomes_vs_Launch.png "Outcomes Based on Launched Date")
### Analysis of Outcomes Based on Goals
For the study on Outcomes Based on Goals, we discovered that when the goal amount is less than $1,000 and up to $14,999, success rates are better and the number of failed fundraisers is low. Please see the line graph below for further details:
![Outcomes Based on Goal](https://github.com/damienfranco/kickstarter-analysis/blob/main/Resources/Outcomes_vs_Goals.png "Outcomes Based on Goal")
### Challenges
The first data was unreadable because they were timestamped in UNIX format. To fix this problem, the data was changed to utilize a normal date format so that it could be read and understood more easily. 
Pivot tables can be a bit difficult to grasp at first, but they offer a lot of functionality. They're not always straightforward to use, though. Pivot tables are sometimes difficult to understand since you have so many options. The process of creating and formatting pivot table columns and rows may be daunting for new users and it took several attempts with settings and options to find the right adjustments for our data.
## Results
We can infer the following conclusions from our analysis of outcomes based on launch date:

* For a play, the most successful month to launch a Kickstarter campaign is May. 
* The least successful months to start a campaign are September through March.
We can come to the following conclusions based on outcomes that are derived from goals:

* The greatest success rate is achieved when the fundraising goal is set at less than $1,000.
* Factors other than the goal amount, such as high success rates of $35,000 to $45,000 are significant.
There are a few flaws with this data set. The data set is simply a sample from a small number of countries and may not be an accurate reflection of the Kickstarter campaign data. Goal and Pledged amounts in various currencies are included in the data set, but currency exchange rate adjustments must be made to provide a more realistic picture.

We can calculate central tendency measures such as mean, mode, and median, as well as the range of data through variance and standard deviation to better comprehend the link between fundraising objectives and successful campaigns. We may then run a linear regression to determine in full how much the launch date affects campaign success.
