# Kickstarter_Challenge
## Project Overview
Louise is planning to start a crowdfunding campaign with a budget of $10,000, to kickstart her theater production of “Fever.” She also wants to understand how to approach campaigns for future plays as she is also planning a musical in Great Britain and has a L4,000 budget to do so. The following analysis was conducted to support her success in these two goals.
## Analysis and Challenges
### Analysis
#### Analysis Overview
The analysis looks at previous and current crowdfunding campaigns across several countries filtered for the category Theater. There are two subcategories under Theater. They are musicals and plays, The focus of our analysis. At a high level the analysis primarily looks at the outcome of the campaigns based on financial goals and the amount pledged. It also looks at the timing of campaigns.
#### Analysis of Outcomes Based on Goal and Outcomes Based on launch Date
The analysis was conducted across 1,369 campaigns (N-1369) and 19 countries focused on theaters and its musical and plays subcategories. See the Excel data file, [Kickstarter_Challenge.zip] (https://github.com/davidmcbee/Kickstarter_Challenge/blob/master/Kickstarter_Challenge.zip) You will need to download and unzip the file due to its size. Financial pledges were compared to the financial goals of the campaigns to determine if they were successful.
##### Analysis Based on Goal
The financial goal amounts were grouped into ascending amount categories. The goal of this analysis was to determine how success or failure compared to the goal amount and goal amount categories. This is dependent on pledged amount, which needs to meet or exceed goal amount to be successful. Please refer to the Outcomes Based on Goals worksheet in the Kickstarter_Challenge xlsx file. This worksheet contains the specific financial groupings that are hsown graphicaly in the Outcomes_vs_Goals chart. ![Theater_Outcomes_Based_on_Launch_Date.png] (https://github.com/davidmcbee/Kickstarter_Challenge/blob/master/Resources/Theater_Outcomes_Based_on_Launch_Date.png) Note in the chart that the highest success rates occur for campaigns under $1,000 with the second highest success rate within the $1,000 to $4,999 goal amounts. This seems fairly intuitive as the goal amounts are fairly modest. A second and somewhat more interesting point shows a spike in success rates at the $35,000 to $39,999 goal amounts. Success is contrasted against failure rates. Again, it is fairly intuitive that the higher goal amounts would have higher failure rates, which the chart shows for the $45,000 to $49,999 goal category. They do not, however, follow in increasing failure rates in a linear fashion. Two points of interest are that the failure rate drops from 100% to 87% at the highest goal amount and there is a spike of failure rates in the $25,000 to $29,999 goal category.
#### Analysis Based on Launch Date
Analysis was also conducted to determine the timing of successful and failed campaigns. This was to determine when is the best time to launch a campaign. Successful, failed and canceled campaigns were charted over months across the time frame of the data, which was 2010 to 2017. Analysis of the outcomes and the timing can be seen in the figure 2. https://github.com/davidmcbee/Kickstarter_Challenge/blob/master/Resources/Theater_Outcomes_Based_on_Launch_Date.png Again, focusing on the Theater category, one can see that the May/June timeframe are the best months to launch a campaign. Referring the tabular data found in the Theater Outcomes Based on Launch Date, found here xxx, May had the most successful campaigns with 111 successful campaigns followed by June with 100. It is also noted that May had the most failures, 52.
### Challenges
One of the challenges with the data is that though all campaigns had financial goals, some of them did not have any backers. To obtain the average amount of pledges one divides pledge amount by number of backers. If there are no backers, this violates the divide by 0 mathematical law. For those cases, the average amount pledged is $0.
Another challenge with both goal and pledge amounts are that they are all listed in U.S. dollars. A number of countries are included in the analysis which use other than U.S. Dollars; most notably, GB where her goals are listed in pounds. U.S. Dollars were used as no currency conversions over the timeframes was available.
## Conclusions based on Outcomes Based on launch Date and Outcomes Based on Goal 
### Conlusions based on Outcomes Based on launch Date
o	The first conclusion in looking Theater Outcomes Based on Launch Date is that May is the best month to start a theater campaign. It shows a 113.5 percent difference between successes and failures; the largest gap between any of the months.
o	There is a small spike of successes in October over September, 65 vs 59 but there is a larger increase in failures in October, 50 vs 34, a 68% jump in failures. The conclusion is that one should especially avoid October to start a campaign. The fall months, in general should be avoided.
### Conclusion based on Outcomes Based on Goal
o	Given the $10,000 budget requirement success rates are only 54.1%. A conclusion of this is that she should either lower the budget to gain a higher probability of success or raise it to the $35,00 to $39,999 range.
o	Module one stated it quite nicely. It said “Louise is asking for more than twice the average successful Kickstarter goal, so this isn't great news for her. In addition, the mean and median pledged amounts are much lower than the successful pledges, which indicates that failed Kickstarter campaigns are unsuccessful for reasons other than asking for too much money. In other words, if the failed projects were also getting a median pledge amount of around $3,000, it is possible that those that failed just asked for too high of a price. Since the median is much lower, there must be another factor keeping people from pledging to those unsuccessful projects.” These statistics were adjusted to only theaters and are consistent with the inclusion of other categories.
## Limitations of Dataset
o	The data is insufficient to explore what the reasons are, in addition to goal and pledge amount, for success and failure. Experience levels of those running the campaigns and the grouping of campaigns that belong to the same individual could help. I would also think that popularity, or at least perceived popularity of a particular play has a strong correlation to success. A corollary to this would be how the campaign is marketed. This could also include data relating to who are the biggest pledgers to enable better targeting. 
o	 Having mixed currencies skews the results. One can convert Pounds to U.S. Dollars, but the timing of those conversions based on fluctuating rates would need to be considered.
o	Understanding the incentives for different pledge amounts could also be helpful.
## Other Possible Tables and/or graphs That We Could Create
o	I believe tracking the success vs failure rates across time to indicate the different ratios would provide valuable information.
o	A graphic comparing goal vs pledge amounts with indicators of success and failure would provide insight into relative differences and their success vs failures. This could also be done across a time axis.
