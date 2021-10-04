# Kickstarter Analysis for Theatres and Plays

## Purpose
The purpose of this analysis is to review the outcome of fund raising for entertainment around the world. More specifically, we are reviewing fund raising for theaters and plays worldwide; the rate of success was based on seasonal launch dates and the amount of fundraising requested.
## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
I used a pivot table to filter the data for the subcategory ‘theater’ and combined the years so we could view the monthly data in a condensed format. This allowed us to view the data seasonally and identify any potential trends between the successes and failures of the shows.  

### Analysis of Outcomes Based on Goals
I created different ranges for goals to condense findings to a condensed and easy to read format. This analysis included plays that were successful, failed, or cancelled while excluding plays that were currently live. According to the data, there were no cancelled plays, which I went back and confirmed with the data on the original sheet.

### Challenges and Difficulties Encountered
One of the main challenges I faced was on the ‘outcomes based on goals’ tab. The formula had to be heavily modified based on the brackets. The first issue was not including the exact ending number and some of the formulas ended up overlapping, which threw off the total counts. The second problem was when I attempted to copy over the formula, this was quickly fixed by using absolute values and then copying the formula. I later added conditional formatting to the charts to improve readability.
## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
	The theatre productions with the highest successes and midrange of failures were January through March; however, the average number of cancelled productions was highest in January. It seems as if the safest months to start a new production were February and March because they had the highest success rate and the lowest failures.
- What can you conclude about the Outcomes based on Goals?
	The highest failure rate was anything over $45,000. The range between $5,000 and $25,000 had a 50% chance at success or failure. The highest rate of success had less than a $5,000 goal. Shows between $35,000 and $45,000 goals had a high success rate as well, this could be due to the show type, the seasonality, or the location of the production.
- What are some limitations of this dataset?
	We’re not looking at the same subcategory for the outcomes and taking multiple factors into consideration. We analyzed two different reasons for two different subcategories and the data does not provide a full picture. We also considered a worldwide entertainment instead of condensing it down by region; it's highly unlikely that you would be able to launch any entertainment worldwide, for less than $50,000.
- What are some other possible tables and/or graphs that we could create?
	As stated above, we could breakdown entertainment categories by geographic location to determine the high success rates. Then determine why they succeeded by using the goals or the seasonality of the productions. We could also review categories with high failure rates, so you know exactly what to avoid. Additionally, I would recommend using correlations to find data that relates prior to running an analysis on each column for example: does the success rate truly relate to the month it was released?