# Election_Analysis

## Project Overview

The purpose of this election audit was to determine the amount of votes cast in each county, the percentage of total votes cast, each candidate's total votes and percentage of votes and the ultimately the election winner. 
 
## Election-Audit Results

* 369,711 votes were cast in the congressional election
* Jefferson County received 38, 855 votes which accounted for 10.5% of total votes. Denver County received 306,055 votes with 82.8% of the total votes. Arapahoe County received 24,801 votes with 6.7% of total votes. 

![Vote_Count_Code.png](path/to/Vote_Count_Code.png)
            
* Denver County had the largest number of votes. 
* Charles Casper Stockham received 85,213 votes which accounted for 23% of total votes. Diana DeGette received 272,892 votes which accounted for 73.8% of total votes. Raymon Anthony Doane received 11,606 votes which accounted for 3.1% of total votes.

![Election_Analysis_Text.png](path/to/Election_Analysis_Text.png)

* Diana DeGette won this congressional election.
  * Diana DeGette's total amount of votes was 272,892.
  * She had 73.8% of the total votes.

## Election-Audit Summary
In summary, this audit successfully revealed the winner of this congressional election in Colorado within these three counties. With slight modifications, this same script could be used in any other county, state or country wide elections. For example one could track the voter turnout within each state for a presidental election by adding a 4th column to the original csv file. Originally creating an empty list to store "States" in and include the appropriate index after row.

![Row.png](path/to/Row.png)

When looking for the popular vote in a presidental election additional conditional loops would be added for that candidate to be known. In the exmple below, adding another if statement to retrieve popular vote.

![Pop_Vote.png](path/to/Pop_Vote.png)
