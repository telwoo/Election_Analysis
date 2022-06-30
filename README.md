# Election_Analysis

## Project Overview
A Colorado Board of Elections employee has given the task to compete the election audit of a recent local congressional election. The overall goal is to outline how the eleciton results were and to outline the following tasks:

1. Calculate the total number of votes cast.
2. Get a complete list of candidates who received votes.
3. Calculate the total number of votes each candidate won.
4. Calculate the percentage of votes each candidate won.
5. Determine the winner of the election based on popular vote.

## Resources
- Data Source: election_results.csv
- Software: Python 3.10.5, Visual Code, 1.38.1

## Election Audit Results
The analysis of the eleciton show that:
- Overall, there were 369,711 total votes in this congressional election.
- The folllowing counties and their percentage of total votes were:
  - Jefferson with 10.5% of total votes and 38,855 number of votes.
  - Denver with 82.8% of total votes and 306,055 number of votes.
  - Arapahoe with 6.7% of total votes and 24,801 number of votes.
- 'Denver' had the largest number of votes.
- The candidates were:
  - Charles  Casper Stockham
  - Diana DeGette
  - Raymon Anthony Doane
- The candidate results were:
  - Charles Casper Stockham received 23.0% of the vote and 85,213 number of votes.
  - Diana DeGette received 73.8% of the vote and 272,892 number of votes.
  - Raymon Anthony Doane received 3.1% of the vote and 11,606 number of votes.
- The winner of the election was:
  - 'Diana DeGette', who received the winning percentage of 73.8% of the vote and 272,892 number of total votes. Diana DeGette was the winner of the overall election.

Below is the overall results:

![Screen Shot 2022-06-30 at 2 36 31 PM](https://user-images.githubusercontent.com/106715923/176753076-b8aa1d8a-dbbf-45c5-9e8c-533b98b2246d.png)


Below is the code used to run analysis for County Votes and Largest County:
![Screen Shot 2022-06-30 at 2 39 35 PM](https://user-images.githubusercontent.com/106715923/176753497-cbb3abe4-c5c6-4fbb-ad75-f056f0a9d86c.png)


Below is the code used to run analysis for Winning Candidate and candidate percentages:
![Screen Shot 2022-06-30 at 2 41 06 PM](https://user-images.githubusercontent.com/106715923/176753937-e09b5b83-893b-45f7-8eb0-fd69966f3025.png)


## Election Audit Summary
After reviewing the results from the election, one can conclude that using Python to outline and audit election results was a great decision! Running the details of any election through this system would gain the election commission futher needs to focus on other marketing for an eleciton instead of worrying about how the votes will be analyzed. There are a couple different ways in which this script written in Python can be modified to be used for other elections:
1. Update the "Largest County Turnout" to show the "Least County Turnout". That way, the election commission would be able to determine how they can market to have the county produce more votes.
2. Add in the "Cty" within the election. This would be beneficial, in case the election commission wanted to pass this script on to a state-wide count.
