# Election_Analysis
Election analysis and audit of results in a Colorado precinct.

## Project Overview
A Colorado Board of Elections employee, Tom, and I were assigned the task of completing an election audit for a local congressional election.  Deliverables for this project include:
1. Calculating the total number of votes cast in the election.
2. Getting a complete list of candidates who received votes.
3. Calculating the total number of votes each candidate recieved.
4. Calculating the percentage of votes each candidate won.
5. Determining the winner of the election based on popular vote.

## Resources
* Data Source: election_results.csv
* Software: Python 3.7.6, Visual Studio Code 1.63.2

## Summary
The analysis of the election demonstrates:
* There were a total of 369,711 votes cast in this election.
* The candidates were:
     * Charles Casper Stockham
     * Diana DeGette
     * Raymon Anthony Doane
* Here are the candidate results:
     * Charles Casper Stockham received 23.0% of the vote for a total of 85,213 votes.
     * Diana DeGette received 73.8% of the vote for a total of 272,892 votes.
     * Raymon Anthony Doane received 3.1% of the vote for a total of 11,606 votes.
* The winner of this congressional election was: 
     * **Diana DeGette**, who received **73.8%** of the vote for a total of **272,892 votes**.

## Challenge Overview
### Overview of Election Audit
This election audit was completed for the Colorado Board of Elections.  In addition to candidate results for this congressional election, a deeper dive was completed to provide further audit and analysis regarding:
* Voter turnout for each county
* Percentage of votes from each county out of the total count
* County with the highest turnout

### Election Audit Results
This congressional election analysis provides an indepth look at voter results in the counties of Arapahoe, Denver, and Jefferson.  Election outcomes included the following:
* **Number of Votes Casted in this Election**
     1. The total number of votes in this election was 369,711 and is referenced in election_analysis.txt as Total Votes: 369,711.
     2. To start, a voter counter was initialized:
     
        ![image](https://user-images.githubusercontent.com/94148420/148704595-1471b758-5972-4158-b54c-a12af9fb8f98.png)
     3. Then the following code was written to determine and print the total number of votes to the terminal and save to a text file:

        ![image](https://user-images.githubusercontent.com/94148420/148704736-0ceb4dbe-c0a2-4afc-8751-16d209181c6b.png)
        
        ![image](https://user-images.githubusercontent.com/94148420/148704935-0ee0cb17-9315-4320-940a-0d1f0765f912.png)


* **Number of Votes and Percentage of Total Votes for Each County in the Precinct**
     1. Here are the results for the number of votes and percentage for each county:
          * Jefferson: 10.5% (38,855)
          * Denver: 82.8% (306,055)
          * Arapahoe: 6.7% (24,8012)
     2. To start, the county was found in the second column or position 1 in the CSV file:

         ![image](https://user-images.githubusercontent.com/94148420/148709333-8525110d-3cc1-48a6-8e6b-1563758e7557.png)

     3. Then the county's vote count was tracked:

        ![image](https://user-images.githubusercontent.com/94148420/148709432-3f36a5f0-bf5d-4077-a9c8-dbe28e689329.png)
        
     4. And finally the results tabulated and printed to the terminal and saved to a text file:

        ![image](https://user-images.githubusercontent.com/94148420/148709603-b4483a50-8f40-4191-b940-ada35ed2cb14.png)


* **The County that had the Largest Number of Votes**
     1. The county that had the largest number of votes was **Denver**.
     2. An "if" statement was writen to determine the county with the largest number of votes, then printed to the terminal and saved to a text file:

        ![image](https://user-images.githubusercontent.com/94148420/148709772-c13ec6ee-df01-4b91-ac8c-6112d52547d6.png)


* **Provide a breakdown of the Number of Votes and the Percentage of the Total Votes Each Candidate Received**
     1. Here is a breakdow of the number of votes and the percentage of the total votes each candidate received:
          * Charles Casper Stockham: 23.0% (85,213)
          * Diana DeGette: 73.8% (272,892)
          * Raymon Anthony Doane: 3.1% (11,606)
     2. To start, the candidate name was found in the third column or position 2 of the CSV file.

        ![image](https://user-images.githubusercontent.com/94148420/148710061-5549ebcd-ac17-4052-8b34-188232b13fbd.png)
        
     3. The candidates total number of votes was calculated:

        ![image](https://user-images.githubusercontent.com/94148420/148710148-4c08d58a-eb4d-4863-a803-3da07bd34298.png)
        
     4. And finally the results were tabulated and printed to the terminal and saved to a text file:
         
         ![image](https://user-images.githubusercontent.com/94148420/148710272-6b7cd12e-fe84-47c5-a590-d31f0d4de473.png)


* **The Winning Candidate, Their Vote Count, and what was Their Percentage of the Total Votes**
     1. The winning candidate was **Diana DeGette** with **272,892** votes, and **73.8%** of the vote.
     2. The following script was written to determine the winning candidate, the winning count, and the winning percentage:

        ![image](https://user-images.githubusercontent.com/94148420/148710401-d3d68c49-7e61-4861-9744-d91041e2ea49.png)


## Challenge Summary
### Election Audit Summary
This election audit and analyis tool is an excellent model and can be used by the Colorado Board of Elections for audit and analysis of future elections.  This scipt is easily adaptable and can be used for local, county, and other state level elections.

Although this tool was only used in one precinct for this congressional election, in the future, it can be easily expanded to include all precincts and include each candidate's party affiliation.  Additional state races to consider for analysis would be the governor's race and other elected officials. 
