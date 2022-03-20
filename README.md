# election-analysis

## Election Audit Overview
A Colorado Board of Elections employee has give the following tasks for an election audit for the recent local congressional election.

1. Calculate the total number of votes cast.
    - 369,711 total votes
2. Get a complete list of candidates who received votes.
    - Charles Casper Stockham
    - Diana DeGette
    - Raymond Anthony Doane
3. Calculate the total number of votes each candidate received.
    - Charles Casper Stockham - 85,213 votes.
    - Diana DeGette received - 272,892 votes.
    - Raymond Anthony Doane - 11,606 votes.
4. Calculate the percentage of votes each candidate won.
    - Charles Casper Stockham - 23.0%
    - Diana DeGette received - 73.8% 
    - Raymond Anthony Doane - 3.1%
5. Determine the winner of the election based on popular vote.
    -Diana DeGette - Winner

## Resources:
    - Data Source: election_results.csv
    - Software: Python 3.7, Visual Studio Code 1.65.2

## Election Audit Results Summary
The analysis of the election audit show the following:
    - How many votes were cast in this congressional election: 369,711
    - County breakdown of votes and percentage of votes:
        - Jefferson: 38,855 votes (10.5%)
        - Denver: 306,055 votes (82.8%)
        - Arapahoe: 24,801 votes (6.7%)
    ![example of county code](election-analysis/CountyCode.png)
    - County with the largest number of votes: Denver
    - Candidate breakdown of vote and percentage:
        - Charles Casper Stockham - 85,213 (23.0%)
        - Diana DeGette - 272,892 (72.8%)
        - Raymond Anthony Doane - 11,606 (3.1%)
    -Candidate winner:
        - Diana DeGette won with a landslide number of votes (272,892) totalling 72.8% of the popular vote.
    ![Winning Candidate code](election-analysis/WinningCandidate.png)
    
## Summary Statement: 
We can also utilize this script to find additional information: 
    - candidate vote percentage/total count for each county specifically to find which counties produced the highest votes for each candidate running. 
    - If we pull the population count, we can also use our script to find the percentage of registered voters who cast a vote in the election.

