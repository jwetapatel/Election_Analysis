# Election_Analysis

# Project Overview

A Colorado Board of Elections employee assigned the following tasks to complete the election audit of a recent local congressional election.

1. Calculate the total number of votes cast.
2. Get a complete list of candidates who received votes.
3. Calculate the total number of votes for each candidate received.
4. Calculate the percentage of votes each candidate won.
5. Determine the winner of the election based on popular vote.
6. Determine the county with the highest turnout.
7. Calculate the percentage of votes from each county out of the total.

## Resources

Data Source: election_results.csv
Software: Python 3.7.6, Visual Studio Code 1.64




## Deliverable 1 Analysis

The election commission has requested some additional data to complete the audit so we upadated our PyPoll code as per below requirements:

Total Votes in the election are printed to the terminal.

Each candidate’s total votes and percentage of votes are printed to the terminal.

The winner of the election, winning vote count, and winning percentage of votes are printed to the terminal.

Here we can see the some updated code image :

![Screenshot (67)](https://user-images.githubusercontent.com/96400887/167004984-f28aaeee-955b-4d9f-952d-0372f9414289.png)


## Deliverable 2 Analysis

In this deliverable we need to writing data to a text file, write the winning candidate results and the county election results text file to be saved following data.

Each county and its total vote count 

Each county and its percentage of the total votes 

The county with the largest number of voters 

Upadated code Shown as below :

![Deliverable 2 updated code](https://user-images.githubusercontent.com/96400887/167008572-a78b4013-503c-48d2-a3ca-ffe3b302b66c.png)

![Deliverable 2  1 updated code](https://user-images.githubusercontent.com/96400887/167008767-59cf4ccd-6a1e-4889-99cc-8fa0cf55b01c.png)

#Election-Audit Results

As per above analysis of the election results shows that:

There were 369,711 votes cast in the election.

The candidates were:

Charles Casper Stockham
Diana DeGette
Raymon Anthony Doane

The candidate results were:

Charles Casper Stockham received 23.0% of the vote, for a total of 85,213 votes.
Diana DeGette received 73.8% of the vote, for a total of 272,892 votes.
Raymon Anthony Doane received 3.1% of the vote, for a total of 11,606 votes.

               
The winner of the election was:

Diana DeGette, who received 73.8% of the vote for a total of 272,892 votes.

The voter turnout for each county was:

Jefferson produced 10.5% of voters, for a total of 38,855 voters.
Denver produced 82.8% of voters, for a total of 306,055 voters.
Arapahoe produced 6.7% of voters, for a total of 24,801 voters.
The county with the largest voter turnout was:

Denver, which produced 82.8% of voters, for a total of 306,055 voters.
And our final election_result Shown as below:

![Election_final result](https://user-images.githubusercontent.com/96400887/167009789-7c8db5fd-d11a-4a93-89e4-734612816989.png)


# Election-Audit Summary

our Uadated script is able to effectively find votes counts, percentage of votes won by each county and candidate it is safe to assume that we can even figure out what the percentages of each county voted for each candidate.

Expanding the Election Audit to include voter turnout by county with candidates results has been a great way to take advantage of the convenience a script provides. The added insight can be a guide for future election performance, so that you may properly allocate resources where turnout is low or demographics are hard to reach.

A little time invested into customizing the script can provide on-demand analysis for years to come.

Modifying the script to produce turnout results by county is just one of many ways that minor adjustments to the code can reveal critical data. For example, we could also dive deeper and determine what percentage of each county voted for each candidate by adding an if-statement to the code. These type of Decision Statements are how the code runs calculations and all we've done is provide it with a data file.

This script we have used for only one state counties of election audit , we could use the same script for change the county to and for other states also.

So, basically this script used to perform the Election Audit can be a valuable resourse for the election board with any number of candidates or counties.
 








