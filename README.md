# EXCEL_HW
Kickstart Campaign for Theaters/Play Analysis

## Overview of Project
Louise wanted to produce her play, Fever. Unfortunately, she did not have enough funds to produce it, so she decided to launch a kickstart campaign for her play. Kickstarter campaigns are like a GoFundMe account, but instead of funding individuals, it is set up to accept donations to fund projects. Louise set up her account on June 13, 2016, 28 days ahead of her deadline and unfortunately, only reached 85% of her funding goal. Hence, she did not have a successful campaign. So, she now wants to research how other theater kickstarters fared in their funding goals and how they did so in relation to their launch dates. 
### Purpose
Provide a visual story and analysis of “outcomes based on their launch dates and funding goals” so that Louise can understand what she could have done differently to reach her funding goals.
## Analysis and Challenges
### Analysis & Results of Outcomes Based on Launch Date
The most successful campaigns launched in May, overall, where there is seen a 66.8% success rate. Louise launched her campaign the next month where there is still a fairly high success rate of 65.3%. Without further analysis, it is impossible to say why May is more successful compared to other months. It is wise to stay clear of launching new theater campaigns in December where the lowest success rate at 49%. Without further analysis, it is hard to say why this is the case. One hypothesis is that during the holiday season, there may be fewer people willing to donate and those that do contribute may not have as much money at their disposal. 

![TheaterOutcomesvLaunch](https://github.com/ChristineMitchell/EXCEL_HW/blob/main/HW%20Challenge/Resources/Theater_Outcomes_vs_Launch.png)
 
So at first glance, you might think Louise should have considered launching in May. However, if you dive deeper into the data year over year, you will see that historically June, 2009-2015, had the highest success rate of 70%, but this was just not the case for 2016 where it dropped to 51% and the more successful campaigns were in July and August respectively that year. So, if we went with the logic that she should have launched in the month where they had seen the greatest success historically, she did choose the correct month from her mark in time. It just signifies how important it is to dive deeper into the data to root cause why Louise was not as successful as her June kickstart predecessors.
 
![SuccessfulOutcomes2009-2015v2016](https://github.com/ChristineMitchell/EXCEL_HW/blob/main/HW%20Challenge/Resources/Successful_Theater_Outcomes_2009-2015_vs_2016.png)

### Analysis & Results of Outcomes Based on Goals
Once again, looking at the play outcomes based on goals it appears that Louise had a better chance of reaching her goals based on the kickstarter results from 2009-2017. The less money that is needed for a campaign the better chances of it succeeding as seen in the chart below. Basically, when setting goals 76% are successful if they set their goal to less than $1000. While those who set their goals between $1000-$4999 are typically 73% successful. Then, the success rate continues to decline from $5,000-$35,000. Since Louise set her goal in the $1000-$4999 range she may have been successful if she asked for less money, after all, she did reach 86% of her goal. 

![PlayOutcomesvGoals](https://github.com/ChristineMitchell/EXCEL_HW/blob/main/HW%20Challenge/Resources/Outcomes_vs_Goals.png)
 
Now, the success rate appears to improve when the goal bucket is between $35,000-$50,000, so this indicates that it is not just how much you are asking for. It also needs to account for other items like the average donation and the number of donors. I dove into the data a bit more and noticed that the average donation for successful plays in the $1000-$4999 goal bucket $60.71. Louise’s play average donation was $248.50; that is 4x the amount for the average donation for this bucket. This is a red flag that Louise did not have many donors. Louise had only 10 donors. The average number of donors of successful play kickstarters in her range was 44. That is less than a fourth of the average number of donors for successful plays. In fact, it looks like the average number of donors for failed campaigns across all buckets is 8, while successful plays have an average of 56 donors. Hence, the fewer number of donors there are for the plays in any of the bucket range, the greater the chances they will fail.

![Table](https://github.com/ChristineMitchell/EXCEL_HW/blob/main/HW%20Challenge/Resources/AveDonation%26AveDonor_vs_Goal_Table.png)
 
### Challenges and Difficulties Encountered
The greatest challenge I encountered was how to create a pivot table that compared the kickstart success rate for multiple years to a specific year for each month. So, I chose to create two different pivot tables. One that pulled multiple years, and the other one a specific year for each month. I changed each of these pivots ‘show the value as’ view to ‘% of Row Totals’ to get the percent of successful outcomes. Then, I created a table consolidating the data with the vlookup formula to be able to display the information in a chart. The visualization told the story that I was looking for, however it took creative thought and multiple steps to manipulate the data.  
I was also able to utilize the sumifs formula, along with the countifs formula, when I created a table to calculate the total number of donors and pledges per bucket group to calculate the average number of donations and donations per outcome per bucket group. The formula and table were fairly simple to create and I did not think I needed a chart, however I could not manage to save the table as a picture to insert it into the document. So, I copied and pasted it to power point to create the png file that I wanted to use. It did not look pretty, but it has the data.

## Results
Based on the analysis above that June had been the most successful campaign month for plays from 2009-2015 and the campaigns set below $5000 were 73-76% successful which are higher than other bucket goals, it could be said that Louise had set herself up for success. The fact that she reached 86% of her goal indicates just how close she was to being successful. Her campaign duration of 28 days was near to the average of successful play campaigns of 28.96 days. However, she did set her goal above the average median ($2,500) for successful play campaigns at $2,885, this was 15% higher than the average median. If she had been more realistic with her goal, she would have been categorized as successful. Yet, the biggest red flag was that Louise simply did not drive enough donors, the few donors she had averaged paying $248.50 which is quite high for a modest goal of $2885, indicating that she had significantly fewer donors compared to the average. She only had 10 people pledge which is less than 25% of the average for successful plays in this $1000-$4999 bucket. 
- What are some limitations of this dataset?
We do not know how people communicated and marketed their needs prior and during their play kickstart campaigns it is interesting to me just how many more people donated to successful campaigns compared to how many Louise received for her play, Fever. Also, I would be interested in who set up the kickstart, for example is it an individual or company or non-profit.
- What are some other possible tables and/or graphs that we could create?
I really should have analyzed the outliers with the box and whiskers chart to see if that skewed any of my data. As well, it would have been a nice touch to provide a visual to tell the story of the average donor and the average donation of the play campaigns in comparison to Louise’s play, Fever, since I think the number of donors was the critical difference when comparing her project to the average successful campaign.

