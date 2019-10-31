# Max's project 4 (assignment 7) readme
## rationale and team assessment 
* We chose vanilla web technologies because the project originally had a much shorter timeframe.
  * I wanted it to be possible for each member of the group to produce something that worked 
* There didnt seem to be much of a need for any sort of multiple page approach
  * even working in the same javascript file we didn't really need to touch each other's methods.. easy to merge
* I (max) hashed out the JS fetch request method and made the interface. I also wrote the getTopCommitters committerGraph function
  * Davin and Ziang made the and getPUllAcceptanceRate/pullGraph and getIssues/drawIssueGraph function pairs, respectively. 
* I chose the google charts api for the graphs because it was the first result on google (wonder why) and had good documentation

## How this works and instructions
* To launch our visualization page, open the html file locally
 * the script and stylesheet should be in the same directory
 * if hosted on a web server somewhere, it would work the exact same
 
* When the body loads, the page makes a call to the augur API to get an array of repo group objects
 * these groups are displayed in the first dropdown
* When a repo group is selected, the page makes a call to get the repos in that group
 * the repos are displayed in the second dropdown
 * for groups with many repos, we offer the ability to search repos by name with the "filter repos" input field
* After selecting a repo, the "get repo metrics" button will call the three functions that get:
 * top committer, new issue, and pull acceptance rate data
 * the graphs for each of the three sets of data are then drawn on the page
