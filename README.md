# Election_Analysis

## Project Overview

The purpose of this election audit was to determine the amount of votes cast in each county, the percentage of total votes cast, each candidate's total votes and percentage of votes and the ultimately the election winner. 
 
## Election-Audit Results

* 369,711 votes were cast in the congressional election
* Jefferson County received 38, 855 votes which accounted for 10.5% of total votes. Denver County received 306,055 votes with 82.8% of the total votes. Arapahoe County received 24,801 votes with 6.7% of total votes. 'Breakdown of the number of votes and the percentage of total votes for each county in the precinct'

Example of code: election_txt = (f"{county}: {vote_percentage: .1f}% ({total_votes})")
        txt_file.write(election_txt)
                # 6f: Write an if statement to determine the winning county and get its vote count.
        if votes > largest_count:
            largest_count = votes
            largest_county = county
            winning_summary = (f"\n-------------------------\n"
            f'Largest County Turnout: {largest_county}, with {largest_count:,} votes.\n'
            f"-------------------------\n")
            
* Denver County had the largest number of votes. 
* Charles Casper Stockham received 85,213 votes which accounted for 23% of total votes. Diana DeGette received 272,892 votes which accounted for 73.8% of total votes. Raymon Anthony Doane received 11,606 votes which accounted for 3.1% of total votes.

Example of code: for candidate_name in candidate_votes:
        votes = candidate_votes.get(candidate_name)
        vote_percentage = float(votes) / float(total_votes) * 100
        candidate_results = (
            f"{candidate_name}: {vote_percentage:.1f}% ({votes:,})\n")
        print(candidate_results)
        
* Diana DeGette won this congressional election.
  * Diana DeGette's total amount of votes was 272,892.
  * She had 73.8% of the total votes.

## Election-Audit Summary
'Provide a business proposal to the election commission on how this script can be used with some modifications for any election.' 'Give 2 examples of how this script can be modified to be used for other elections'
