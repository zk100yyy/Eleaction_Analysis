# Eleaction_Analysis

## 1.Overview of Election Audit
#### This election audit was conducted in order to ensure accurate and satisfactory results be submitted to the Colorado Board of Elections for their recent election cycle. Python was used to properly ingest and manipulate the provided election data so that it be accurately and easily analyzed. Results were submitted in .txt format.

## 2.Election-Audit Results

* **How many votes were cast in this congressional election?**

  There were 369,711 votes cast in the election.

* **Provide a breakdown of the number of votes and the percentage of total votes for each county in the precinct.**

 
    * Jefferson had 10.5% of votes, or 38,885 total votes
    * Denver had 82.8% of votes, or 306,055 total votes
    * Arapahoe had 6.7% of votes, or 24,801 total votes
* **Which county had the largest number of votes?**

    Denver had the largest voter turnout. (306,055 voters)

* **Provide a breakdown of the number of votes and the percentage of the total votes each candidate received.**

    Of the candidates, Charles Casper Stockham recieved 23.0% of the votes with 85,213 votes, Diana DeGette 73.8% of the votes with 272,892 votes and the last candidate Raymon Anthony Doane recieved 3.1% of the votes with 11,606 votes.
* **Which candidate won the election, what was their vote count, and what was their percentage of the total votes?**

    Diana DeGette was determined to be the winner of the elections, recieving 73.8% of the votes with 272,892 votes cast for them.
    
## 3.Election-Audit Summary

**This python script can be used, with some modification, for any election. This relies mostly on the format of provided data. Should the election result data, in .csv format, maintain it's current format, of candidate's names in column 3, and county name in column 2 - then you can run this script unchanged. However, so long as you import a .csv and know what columns your county names falls within, and which column your candidate's names fall within - you can use said column's index number to very minimally alter the script to work with your data. In example, if your candidate name was in column 5 and your county name fell within column 4 - you would simply change the number in parenthesis in the below script to those column's corresponding index number (column # - 1).**

**So, two options to get this script to work with any .csv of data would be to**

**1. Re-position candidate names and county names to columns 3 and 2 respectively.**

**2. Ammend the below section of script to fit the candidate names and county names column's corresponding index number.**

**With this script and additional formatting information provided above, this script will prove to be effective in providing it's election analysis.**
