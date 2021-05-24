# Election_Analysis

## Overview of Election Audit: Explain the purpose of this election audit analysis.

In this challenge, I helped the Colorado Board of Elections audit the results of a recent election. I was specifically working with two people named Seth and Tom to analyse election data for a recent congressional district in Colorado using Python programming and the terminal in Visual Basic.

## Election-Audit Results: Using a bulleted list, address the following election outcomes. Use images or examples of your code as support where necessary.
<img width="293" alt="Election_Results" src="https://user-images.githubusercontent.com/80979705/119289999-b44bc180-bc19-11eb-9f3f-aa8fa182de7f.PNG">
### How many votes were cast in this congressional election?

As can be seen in the screenshot above, there were a total of 669,711 votes cast in this election.

### Provide a breakdown of the number of votes and the percentage of total votes for each county in the precinct.

As can be seen in the image above of my election_results.txt file, the breakdown of votes and percentage of total votes is broken down by county below:

County Name: Percentage of Total Votes (Number of Votes)

Jefferson: 10.5% (38,855) 
Denver: 82.8% (306,055) 
Arapahoe: 6.7% (24,801) 

### Which county had the largest number of votes?

Unsurprisingly, Denver had by far the most votes with 306,055 votes cast- which translates to 82.8% of the total votes cast in the congressional election.

### Provide a breakdown of the number of votes and the percentage of the total votes each candidate received.

The breakdown by candidate is as follows:

Charles Casper Stockham: 23.0% (85,213)
Diana DeGette: 73.8% (272,892)
Raymon Anthony Doane: 3.1% (11,606)

### Which candidate won the election, what was their vote count, and what was their percentage of the total votes?

Diana DeGette is the candidate who won the election with 73.8% of the total votes cast for her. The size of her win is not even comparable to the other candidates, who received 23% and 3.1%. It was a blowout for Diana, and she won the election fair and square.

## Election-Audit Summary: In a summary statement, provide a business proposal to the election commission on how this script can be used—with some modifications—for any election. Give at least two examples of how this script can be modified to be used for other elections.

By changing or modifying the underlying dataset, and the relevant Python lists and dictionaries, this Python script should be able to analyse any election. 

One specific idea for an alternate use of the script with little modification could be for filling in the census. If we switch candidate with 'sex' or 'age group' it could be useful in tracking population growth in this region of Colorado.
This script could also be useful in extremely close elections. In extremely close elections like the Florida 2000 Presidential Race between Al Gore and George Bush, the votes were within a few hundred of each other. Usually when margins are that small, there is a recount done by hand and questionable ballots can be challenged or included one by one. The problem with handcounting though is that humans often make errors. This is where a computer program like Python may come in handy because computers are extremely reliable, and less likely to make mistakes in many cases.
