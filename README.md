# Election-Analysis

## Project Overview
An assistant to a Colorado Board of Elections employee was given the following tasks to complete an election audit of a local congressional election.

1. Calculate the total number of votes cast.
2. Get a complete list of candidates who received votes.
3. Calculate the total number of votes each candidate received.
4. Calculate the percentage of votes each candidate won.
5. Determine the winner of the election based on popular vote.

## Resources
- Data Source: election_results.csv
- Software: Python 3.7.6, Visual Studio Code 1.58.0

## Summary 
The analysis of the election shows that:
- There were 369,711 votes cast in the election.
- The candidates were:
-- Charles Casper Stockham
-- Diana DeGette
-- Raymon Anthony Doane
-  The candidate results were:
-- Charles Casper Stockham received 23.0% of the vote and 85,213 number of votes.
-- Diana DeGette received 73.8% of the vote and 272,892 number of votes.
-- Raymon Anthony Doane received 3.1% of the vote and 11,606 number of votes.
-  The winner of the election was:
-- Diana DeGette, who received 73.8% of the vote and 272,892 number of votes.

![Election_results.png](https://github.com/KimberlyCrawford/Election-Analysis/blob/main/Election_results.png)
    
## Challenge Overview 
The election commission requested the following additional data to complete the audit:
- The voter turnout for each county.
- The percentage of votes from each county out of the total count.
- The county with the highest turnout.

## Challenge Summary 
The additional analysis of the election shows that:
- The voter turnout and percentage of votes from each county included:
-- Jefferson County had 10.5% votes and 38,855 number of votes.
-- Denver County had 82.8% votes and 306,055 number of votes.
-- Arapahoe County had 6.7% votes and 24,801 number of votes.
- The county with the highest turnout was Denver.

![County_Election_results.png](https://github.com/KimberlyCrawford/Election-Analysis/blob/main/County_Election_results.png)

See the following election results for county and candidates:

![Final_election_results.png](https://github.com/KimberlyCrawford/Election-Analysis/blob/main/Final_election_results.png)

## Business Proposal to Election Commission
This script can be used—with some modifications—for any election. Currently, our data set consists of three columms: (1) Ballot ID, (2) County, and (3) Candidate. See the sample data below:

![Election%20data.png](https://github.com/KimberlyCrawford/Election-Analysis/blob/main/Election%20data.png)

Two examples of how this script can be modified to be used for other elections includes the following:
1. Updated information in the data file with new candidate names and ballot IDs - The counties in the district will stay the same; however, the candidates will change along with the ballot IDs for each election. Changing the data file being read would be your only change if you want the same results for a different election. For example, the name of the data file might be more specific to each election, i.e. Sheriff_2021_election_data. The name of the files to load to and save to would need to be modified in the script.
![Variable%20to%20Load.png](https://github.com/KimberlyCrawford/Election-Analysis/blob/main/Variable%20to%20Load.png)

2. Updated information in the data file with political party instead of county, candidate names and ballot IDs - Again, updates to the data file names in the first part of the script as shown in the first example above would need to be made. Then, updates to the variables names will need to be changed throughout the script. For instance, county_options would need to be changed to political_party_options and so on.
![Variable%20to%20Load.png](https://github.com/KimberlyCrawford/Election-Analysis/blob/main/Variable%20to%20Load.png)
