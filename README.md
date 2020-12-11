# School_District_Analysis

## Overview of the Analysis
The reason that we performed the analysis on the school district for this challenege was because it was found out that there might have been Academic dishonesty at Thomas High School for the ninth grade reading and math scores. We originally performed the school district analyis to see which schools were performing the best, how the types of schools compared to one another, how the size of schools effected performance, and many other metrics. For this challenge we performed the analysis on the same metrics, but we took out the math and reading scores for the ninth graders at Thomas high. This was to make sure our results and analyis would not be tainted by academic dishonesty. 

## Analysis: 
### District Summary Effects
- By taking out the ninth grade Thomas High reading and math scores the District did see a decrease in % passing math, % passing reading, and % overall passing. Although there was a decrease it was very minor. For example the % overall passing dropped from 65.17% to 64.9%. To see all of the original District dataframe metrics please look [here](https://github.com/jmerenstein/School_District_Analysis/blob/main/Resources/Original%20District%20Summary%20Dataframe.png). To see the updated  District dataframe metrics please look [here](https://github.com/jmerenstein/School_District_Analysis/blob/main/Resources/New%20District%20Summary%20DataFrame.png).

### School Summary and Thomas High Effects
- The school summary dataframe and Thomas High's results were both minorly affected by taking out the ninth grade test scores. Overall Thomas High school was trhe second highest performing school in terms of % overall passing and still remained second highest overall once the ninth grade scores were taken out. The % overall passing for Thomas did decrease from 90.94% to 90.63%, but this change is very minor. Overall taking out the ninth grade scores for Thomas High had very little effect on the summary dataframe overall and how Thomas High performed overall. Click [here](https://github.com/jmerenstein/School_District_Analysis/blob/main/Resources/Original%20School%20Summary.png) to see the original top performing school and click [here](https://github.com/jmerenstein/School_District_Analysis/blob/main/Resources/New%20School%20Summary.png) to see the new top performing schools. 

### Challenges and Difficulties Encountered
The main challenge of the initial Pivot Table analysis was to decide if I should just look at theater Kickstarter campaign or Kickstarter campaigns overall. Since, Louise is looking to fund her play I decided it would be best to just look at theater campaigns. The main challeneges I faced in the second part of the analysis of the anaylsis was correctly formatting the COUNTIFS function in Excel. It took me a couple of tries, but then I was able to accomplish it successfully.

## Results
- The main conclusions that I can draw from the analysis of the Theater Outcomes based on Launch Dates is that May and June have the most successful launches and December has the least amount of successful launches. So, I would advise Louise to start her campiagn in May or June. 

- Based off of looking at the analysis from the Outcomes based off of Goals it suggests that the higher the goal amount, the lower the chance the campagin has to succeed. It is much easier to succeed keeping the capaign goal to anywhere between Less than $1000 to around $15,000. I would suggest to Louise that, if possible, she should keep her campaign ask for $15,000 or lower. The higher the ask is from $15,000 there is more of a chance the campaign will fail. 

- Some limitations of the dataset are that there are a lot of Kickstarter campaigns that might be totally unrelated to theater campaigns so the analysis done on those campaigns may not be as useful. What would possibly be more helpful would be to have a larger amount of theater campaigns and less types of campaigns that are unrelated to theater and plays.

- One other possible table and graph I would create is to look at successes of other types of entertainment, possibly like the subcategories of documentaries and tv shows. I would take a look at those and see if there is any relationship between the data I am seeing with what makes a theater campaign successful. If there was a relationship then I could expand my dataset from just theaters and plays to give Louise more accurate advice. 

