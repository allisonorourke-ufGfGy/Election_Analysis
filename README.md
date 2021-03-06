# Election Analysis
## Overview of Election Audit
### Intorduction
#### We were asked to help our friend Tom with analysing the results of a local election. The challenge was to use python, the command line, VS Code, and git Bash to run the analysis to determine the candidate winner and which county had the highest turnout. There were 3 candidates in the race and the vote were gathered from 3 different counties. The candidates in the election were
1. Charles Casper Stockham
2. Diana DeGette
3. Raymon Anthony Doane
#### The 3 counties that the results were gathered from were
1. Arapahoe
2. Denver
3. Jefferson
#### There were a total of 369,711 votes in total and we wanted to analyze all of the redults for a number of different metrics. This analysis will help to determine the winner of the election.
## Election-Audit Results
* How many votes were cast in this congressional election?
  * 369,711
* Provide a breakdown of the number of votes and the percentage of total votes for each county in the precinct.
  * Jefferson: 10.5% (38,855)
  * Denver: 82.8% (306,055)
  * Arapahoe: 6.7% (24,801)
* Which county had the largest number of votes?
  *  Denver with 306,055 votes
* Provide a breakdown of the number of votes and the percentage of the total votes each candidate received.
  * Charles Casper Stockham: 23.0% (85,213)
  * Diana DeGette: 73.8% (272,892)
  * Raymon Anthony Doane: 3.1% (11,606) 
* Which candidate won the election, what was their vote count, and what was their percentage of the total votes?
  * Winner: Diana DeGette
  * Winning Vote Count: 272,892
  * Winning Percentage: 73.8% 
 #### The results can be seen in the following lines of code
 ![code image](https://github.com/allisonorourke-ufGfGy/Election_Analysis/blob/main/Pypoll.png)
 
## Election- Audit Summary
### Business Proposal
#### This code can be used to analyze multiple different elections. This code is written to read off of a csv file and pull in information to analyze it. In the following code you can see where the code pulls in the county names and the candidate names. This part of the code can be changed to read different rows depending on the structure of the csv with the information on the election.
![candidate name](https://github.com/allisonorourke-ufGfGy/Election_Analysis/blob/main/Pulling%20candidate.png)
#### This part of the code can be changed to pull in different csv files which could then be used to analyze different election results. In conjunction with changing the rows it is reading above then you can get a similar output but with different votes.
![import code](https://github.com/allisonorourke-ufGfGy/Election_Analysis/blob/main/import%20code.png)
#### This code would be able to allow people to analyze the results of any election quickly and correctly. This code allows for hundreds of thousands of lines to be analyzed in a matter of seconds. This can give you an immediate and correct answer without having to worry about human error that comes with physically counting each of the lines. 
