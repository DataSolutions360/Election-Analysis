# ELECTION-ANALYSIS
**Overview of Project**

  Analysis of an election audit of the COlorado Board of Elections for a recent 
  local congressional election, to determine the winning candidate and the largest voter turnout, 
  based on county. The analysis required the following data to be utilized:
    
    1) The list of all candidated in the election
    2) The total number of votes cast
    3) The total number of votes received per candidate
    4) The total number of votes per county
    5) the percent of votes for each candidate
    6) Winner of the election
    7) The county with the largest voter turnout
    
## Election Audit Results ##

  Results of the audit showed a total of **369,711** votes cast during the congressional election
  from the counties participating in the precinct.  These counties participant in the elections are:
  
    - Denver --> 82.8% popular vote --> 306,055 votes  
    - Jefferson --> 10.5% popular vote --> 38,855 votes
    - Arapahoe --> 6.7% popular vote --> 24,801 votes
    
![image](https://user-images.githubusercontent.com/8845050/166129402-c5aca184-7e27-4fdf-8c61-d5ee0e9da461.png)

## Candidate Results: ##

  Resulted of the audit are broken out by candidate, percentage of total vote, and allocated vote in aggregate 
  
      Diana Degette received 73.8% of the vote, which accounted for 272,892 votes.  She was the clear winner
      
      Charles Casper Stockham received 23.0% of the vote, which accounted for 85.213 votes
      
      Raymon Anthony Doane received 3.1% of the vote, which accounted for 11,606 votes
    
![image](https://user-images.githubusercontent.com/8845050/166129454-26dfbe55-7d67-4bf0-aff4-22e72980f1eb.png)
    
# Election Audit Summary

 The code developed for this analysis is an efficent tool to allow for situational adjustments.  This code is very scalable, and the 
 customization is easily expressed in the results with transparency.
  
![image](https://user-images.githubusercontent.com/8845050/166127175-3e2b45bd-5070-4f8e-8b54-63ae654c9f60.png)

  The code(file_to_load) allows for customization of the file location.  Data Source manipulation is extremely helpful when collaberating within a team.  
  Independent stakeholders can work on separate parts of a project, such as "Election Analysis".
  
    The code(file_to_save) allows the analyst/programmer the freedom to delegate the location(folder) within the file hierarchy.  
    
# Candidate Name Explained 

The code below "fetches" the candidate_name in candidate_votes, and calculates the vote_percentage

Candidate_results then tabulates "CANDIDATE_NAME | VOTE_PERCENTAGE | Sum of VOTES" respectively.
 
![image](https://user-images.githubusercontent.com/8845050/166127698-bb1ecb2f-1c8c-4697-a9ac-8efbafa2d109.png)

# County Vote Explained##

The code below "fetches" the sum of county_votes, for each respective county.

County_vote_percentage refers to the sum of county votes divided by the sum of total votes for the respective counties.

County Results uses an F string to combine qualitative and quantitative values to allow for readable, tabular views
  
  ![image](https://user-images.githubusercontent.com/8845050/166128158-0cd18615-11df-4ec4-814e-c4b87baecd9c.png)

  


    
    
