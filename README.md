# Election_Analysis

## Overview
An election board has provided the data from a recent election to be automated to see the election results. Here is a list of what was needed to complete the audit:

1. Deterime what data to retrieve
2. Number of Votes cast
3. A list of candidates who recieved the votes
4. Number of votes each candidate won
5. Percent of votes each candidate won
6. Winner of the Election

## Resources

Data Source: election_results.cvs

## Summary

The analysis showed that there were 369,711 votes cast.
The three candidates and the number and percentages of votes they recieved were:

Charles Casper Stockham: 23.0% (85,213)

Diana DeGette: 73.8% (272,892)

Raymon Anthony Doane: 3.1% (11,606)

#### And the winner of the election was:
Diana DeGette

Winning Vote Count: 272,892
Winning Percentage: 73.8%

# Challenge Overview of Election Audit
The election audit was designed to look through the data to determine statistics about the election, but now that it is automanted the code can be applied to future elections with their own datasets. The analysis makes it easy to see the candidates name with the percent of the vote that they won with the final vote counts. It also shows how those votes were distributed between the three counties. The analysis uses Python code to import data from a csv and output results to a txt that is simply formatted and easy to read.

## Election-Audit Results:
The results are listed in the table below. The outcomes are supported with code in the text that follows:

![Screen Shot 2022-05-01 at 1 50 11 PM](https://user-images.githubusercontent.com/99676466/166162249-ec4a9f5a-8ba2-4698-8d58-485fae8df033.png)

* How many votes were cast in this congressional election? 
    Total votes in the election: 369,711
    The code loops through the rows to determine a vote tally for each candidate and county and adds them together for          totals.
* Provide a breakdown of the number of votes and the percentage of total votes for each county in the precinct.
    Jefferson:  10.5% (38,855)
    Denver:  82.8% (306,055)
    Arapahoe:  6.7% (24,801)
    
    ![Screen Shot 2022-05-01 at 1 54 25 PM](https://user-images.githubusercontent.com/99676466/166162371-0aea847b-fcdd-4dd8-b9d7-242519abd1c0.png)

    
* Which county had the largest number of votes?
    Denver had the most votes as the most densely populated of the three counties and 306,055 or 82.8% of the vote.
    
* Which candidate won the election, what was their vote count, and what was their percentage of the total votes?
    Diana DeGette won the election with a winning vote count of 272,892 votes or 73.8% of the total votes.

## Election-Audit Summary: 
This code is set up to extract data from the current election and provide the specified results. With a few modifications though, the code could be used to automate all future election results. As the analyst, I would be happy to provide those minor modifications to the code so that the election board can easily audit all elections in the future saving time and giving the board the ability to quickly confirm election results. 

The script modifications include modifying which data needs to be read by importing that csv or whichever file form the data comes in. And a second modification would depend on the format of the data; for example, if the columns on the new data set had the candidates name and the county name in different rows, the code would need to be modified to include a different row index in that for loop:

   ![Screen Shot 2022-05-01 at 2 23 40 PM](https://user-images.githubusercontent.com/99676466/166163254-678a2f44-3a59-4a94-9aa5-f5c2b4cb372b.png)

These modifciations are easy to make and it there was additional results needed a few more lines of code could be added to claculate that as well.

