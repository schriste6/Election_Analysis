# Election Analysis  
## Overview of Election Audit
### A Colorado Board of elections committee requested an automated audit process that delivers outcome data of a recent local congressional election.  
## Resources  
* Data Source: election_results.csv
* Software: Python 3.9.7, Visual Studio Code 1.63.2
## Election Audit Results  
The Analysis of the election delivered the following outcomes:  
* **369,711 total votes** were cast in this congressional election
* County breakdown by percentage of total votes and (number of cast votes):
  * Jefferson: 10.5% (38,855)
  * Denver: 82.8% (306,055)
  * Arapahoe: 6.7% (24,801)
* **Denver** received the largest number of votes (306,055)
* Candidate breakdown by percent of the total votes (number of cast votes):
  * Charles Casper Stockham: 23.0% (85,213)
  * Diana DeGette: 73.8% (272,892)
  * Raymon Anthony Doane: 3.1% (11,606)
* **Diana DeGette won the election with 73.8% of the votes and 272,892 cast votes**
# Challenge Summary
The automated audit process developed for the recent congressional election is proven successful by delivering on all requested outcomes. An unexpected 'win' is the developed script can be modified to apply to any election, and even enhanced to deliver additional outcomes:
   1. Expand lists and dictionaries to accommodate flexible geographical scope, such as, but not limited to; local, region, state, and national. This would allow any election committee access to election results with consistency, accuracy, and efficiency.  Below demonstrates current County dictionary and list.  Adding lists and dictionaries can expand the scope and deliverables from a regional level to a nation level.    
![](/Resources/Example_1_dict_list.png)  
   2. Expand deliverables to include other important information from elections data.  Greatest county turnout is developed in the current script, but perhaps (hypothetically) there is interest in knowing the lowest county turnout because it may suggest disengagement from government services.  Below demonstrates calculation to deliver County with greatest turnout.  By adding thoughtful outcomes will demonstrate robust analytics and allow government added insight into constituents.    
![](/Resources/Example_1_lowest_turnout.png)
