# Analysis of the Election Audit

## Overview of Election Audit

Working from this election_results.csv file, we will use 'for' loops and conditional statements with membership and logical operators to find the requested results.

Additional data was requested by the election commision to complete the audit:
* The voter turnout for each county
* The percentage of votes from each county out of the total count
* The county with the highest turnout

We'll then, print the results to the command line and save them to election_results.txt file.

## Election-Audit Results

###### _*Results in Command line*_

 <img width="458" alt="commandline" src="https://user-images.githubusercontent.com/104603128/170837765-a7b85b18-8914-4deb-a10b-2750043aa9e4.png">
 
###### _*Results in .txt file*_
 
  <img width="202" alt="Untitled" src="https://user-images.githubusercontent.com/104603128/170835783-b45c3d2a-7cba-424f-843a-c9032114e507.png">
  
  
- *How many votes were cast in this congressional election?*


 The total number of votes cast in the elections are 369,711.


- *Provide a breakdown of the number of votes and the percentage of total votes for each county in the precinct.*

 The number of votes for each county are as follows: 

|   County's Name  |   Percentage   | Number of Votes|
| ---------------- | -------------- |----------------|
|    Jefferson     |      10.5%     |     38,855     |
|    Denver        |      82.8%     |    306,055     |
|    Arapahoe      |       6.7%     |     24,801     |
  
- *Which county had the largest number of votes?*

As dipicted in the picture above the largest number of votes are from Denver.

- *Provide a breakdown of the number of votes and the percentage of the total votes each candidate received.*

Refer to the table below for the number of votes & percentage of total votes of each candidate:

|    Candidate's Name     |   Percentage   | Number of Votes|
| ----------------------- | -------------- |----------------|
| Charles Casper Stockham |      23.0%     |     85,213     |
| Diana DeGette           |      73.8%     |    272,892     |
| Raymon Anthony Doane    |      3.1%      |     11,606     |

- *Which candidate won the election, what was their vote count, and what was their percentage of the total votes?*


Diana DeGette won the election with 272,892 total votes and the votes percentage is 73.8%.

## Election Audit Summary

* By uploading a different raw data for any election here-

file_to_load = os.path.join("Resources", "election_results.csv")  can get similar results.

* Add more candidates/counties to this election or for any election .

* County can be switched for states for larger elections and have similar results.



