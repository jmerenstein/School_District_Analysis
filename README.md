# School_District_Analysis

## Overview of the Analysis
The reason that we performed the analysis on the school district for this challenege was because it was found out that there might have been Academic dishonesty at Thomas High School for the ninth grade reading and math scores. We originally performed the school district analyis to see which schools were performing the best, how the types of schools compared to one another, how the size of schools effected performance, and many other metrics. For this challenge we performed the analysis on the same metrics, but we took out the math and reading scores for the ninth graders at Thomas high. This was to make sure our results and analyis would not be tainted by academic dishonesty. 

## Analysis: 
### District Summary Effects
- 

### Analysis of Outcomes Based on Goals
The second part of the analysis consisted of looking at how much money the different Kickstarter play campaigns would have as their fundraising goals and then seeing what different dollar amount goals led to successful, failed, or canceled Kickstarter campaigns. To do this I used the COUNTIFS function in Excel to figure out how many succesful, failed, and canceled campagins asked for certain goal amounts. Then I took the percentages of the succesful, failed, and canceled campaigns for those different goal amounts to see what a good suggestion of a goal amount would be for Louise. The line graph showing those different percentages can be seen [here](https://github.com/jmerenstein/kickstarter-analysis/blob/main/Outcomes_vs_Goals.png).  

### Challenges and Difficulties Encountered
The main challenge of the initial Pivot Table analysis was to decide if I should just look at theater Kickstarter campaign or Kickstarter campaigns overall. Since, Louise is looking to fund her play I decided it would be best to just look at theater campaigns. The main challeneges I faced in the second part of the analysis of the anaylsis was correctly formatting the COUNTIFS function in Excel. It took me a couple of tries, but then I was able to accomplish it successfully.

## Results
- The main conclusions that I can draw from the analysis of the Theater Outcomes based on Launch Dates is that May and June have the most successful launches and December has the least amount of successful launches. So, I would advise Louise to start her campiagn in May or June. 

- Based off of looking at the analysis from the Outcomes based off of Goals it suggests that the higher the goal amount, the lower the chance the campagin has to succeed. It is much easier to succeed keeping the capaign goal to anywhere between Less than $1000 to around $15,000. I would suggest to Louise that, if possible, she should keep her campaign ask for $15,000 or lower. The higher the ask is from $15,000 there is more of a chance the campaign will fail. 

- Some limitations of the dataset are that there are a lot of Kickstarter campaigns that might be totally unrelated to theater campaigns so the analysis done on those campaigns may not be as useful. What would possibly be more helpful would be to have a larger amount of theater campaigns and less types of campaigns that are unrelated to theater and plays.

- One other possible table and graph I would create is to look at successes of other types of entertainment, possibly like the subcategories of documentaries and tv shows. I would take a look at those and see if there is any relationship between the data I am seeing with what makes a theater campaign successful. If there was a relationship then I could expand my dataset from just theaters and plays to give Louise more accurate advice. 

