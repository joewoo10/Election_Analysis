# Election_Analysis
## Overview
### A Colorado Board of Elections official requested assistance with an election audit of the tabulated results from a U.S. Congressional precinct in Colorado. I was tasked with reporting the following:
1.	Calculate the total number of votes cast in the election.
2.	Provide a complete list of all candidates who received votes.
3.	Calculate the total number of votes each candidate received.
4.	Calculate the percentage of votes received by each candidate.
5.	Determine the winner of the election based on popular vote.
6.	Calculate the voter turnout for each county.
7.	Calculate the percentage of votes each county received from the total cast.
8.	Determine the county with the highest voter turnout.
## Audit Results
### The analysis of the election (*see election_results.txt*) shows that:

#### There were 369,711 votes cast in the election.

#### There were three candidates:

    Charles Casper Stockham

    Diana DeGette

    Raymon Anthony Doane


#### The candidate results as shown with total votes received and percentage of total cast:

    Charles Casper Stockham received 85,213 votes (23.0%).

    Diana DeGette received 272,892 votes (73.8%).

    Raymon Anthony Doane received 11,606 votes (3.1%).
    

#### The winner of the election was:

    Diana DeGette, who received 272,892 votes (73.8%).
    

#### The voter turnout for each county was:

    Jefferson County produced 38,855 voters (10.5%).

    Denver County produced 306,055 voters (82.8%).

    Arapahoe County produced 24,801 voters (6.7%).
    

#### The county with the largest voter turnout was:

    Denver, which produced 82.8% of voters, for a total of 306,055 voters.
    
    

## Audit Summary
By expanding the previous script to include voter turnout by county, the election audit now provides a more clearly defined picture of the election results and possible insight into what that means for this congressional district moving forward. Modifying the script to produce turnout results by county (*see PyPoll_Challenge.py*) is just one of many ways that small adjustments to the code revealed critical data.  Additional modifications could look at county turnout statewide for a gubernatorial or national election. Data from past elections could be incorporated to uncover trends that may be utilized in future election efforts and/or to predict voter turnout. This could be especially important in areas where turnout is historically low, or demographics are challenging to reach. As such, the script used for analyzing this election data could be further employed as a template by making modest adjustments to extract the specific data needed to answer questions and address election issues. I believe it goes without saying, this could be a valuable tool for the Board of Elections for many years to come.
