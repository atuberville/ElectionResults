# Election Audit

## Overview of Election Audit
The purpose of this election audit was to verify all ballots cast in Jefferson, Denver, and Arapahoe counties in order to determine the winner of the election. Candidates were as follows:
 - Charles Casper Stockholm
 - Diana DeGette
 - Raymon Anthony Doane

## Results
There was a total of 369,711 votes cast in the election.
 - Denver: 306,055 (82.8%)
 - Jefferson: 38,855 (10.5%)
 - Arapahoe: 24,801 (6.7%).

The winner of the election was Diana DeGette with 73.8% and a total of 272,892 votes.
![image](https://user-images.githubusercontent.com/89363928/135785287-64ff5895-00ae-42cc-a696-e8d52f035022.png)

## Summary
The script attached can be used to evaluate any election with some minor adjustments to the code. I would suggest creating a new section where all participants can be ranked in order of their votes. This could be achieved with a sort() function on the variable of your choosing. I would also recommend reviewing the ballot ID lists for duplicates - an audit isn't a true audit unless all the variables have been reviewed. This would be accomplished by using pandas and creating a data frame for the Ballot ID's. Then you would use the string pd.unique() in order to return and compare any duplicates.
