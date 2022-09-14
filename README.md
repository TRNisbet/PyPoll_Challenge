# Module 3 PyPoll Challenge

## Overview of Election Audit:
The purpose of this project is to write additional code to a file to return accurate results for a) voter turnout for each county; b) the percentage of votes from each county out of the total count; c) the county with the highest turnout.  The additional requirements should display in the terminal and be written to election_results.txt in the same format as the original code.  The file used to obtain the data is in the Resource Folder and located here: [election_results.csv](Resources/election_results.csv).  The file created by the audit is located in the Analysis folder and is located here: [election_results.txt](Analysis/election_results.txt).

## Election-Audit Results:
### County Results:
•	The results of the audit show that 369,711 total votes were cast.

•	Denver County accounted for 82.8% of the votes cast with 306,055 total votes, making Denver the county with the most votes and the highest percentage of the turnout.

•	Jefferson County accounted for 10.5% of the votes cast with 38,855 total votes.

•	Arapahoe County accounted for 6.7% of the votes cast with 24,801 total votes.  


### Candidate Results:
•	Diana DeGette won the election with 73.8% of the total votes with a vote count of 272,892.

•	Charles Casper Stockham was the second highest vote receiving candidate with 23.0% of the votes and 85.213 total votes.

•	Raymon Anthony Doane received the least number of votes from the candidates with 3.1% of the votes with 11,606 total votes.  


## Election Audit Summary
The code written for the Election Audit could be applied to larger elections, but the format of the file would need to be consistent in both name and layout to the current “election_results.csv” file.  In order to handle results covering a range of ballot measures the input file would need a column to distinguish the ballot measure and code would need to be added to account for it.  The addition of multiple measures in one file could be achieved with a new for loop over the for loops already in the script and the code to pull out the unique ballot measure would be similar to the loops for the counties and candidates, this is not all the changes that would need to be made to the file, but just a starting point as the output to the terminal and “.txt” file would need to be altered along with other elements in the file.  Utilizing the current script across multiple elections would warrant changes to the input and output files, as the files would need to reference the specific elections that is being tabulated.  Again, existing code would need to be altered to allow a user to input the file names for the input and output file.  However, the code as written works as expected in determining the winner of an election, breaking down the votes by county and candidate, along with some other information.  
