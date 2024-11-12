# Github Users Analysis from Specific Region.
This Project scrapes the github users data using github API and derive meaningful insights. 

This is the readme file of the Project as part of coursework for Tools in Data Science The Three important aspects of Project

### Explanation of Data Scraping process: 
The data scraping began with the generation of token of Github API from the developer settings. The Token (Personal Access) was generated for fetching the data. The os and requests module were imported and the token was stored as secrets (environment variable) in Colab for security purposes. The GitHub API scraping process involves sending requests to GitHub’s servers, often using query parameters or endpoints (e.g., users, repos). The API responds with JSON data. To avoid rate limits, requests are spaced or use authentication. The data was then checked for boolean values and True, False were modified to true, false respectively. The Empty values in these columns were assigned Null. The Company Name was cleaned to remove whitespace, @ symbol and were converted to uppercase.
### Observations:
Interesting Observation after analyzing the data: One interesting observation is regression slope of the followers on repos which is negative indicating the inverse relationship between two. Also secondly the correlation coefficient between followers and repos is negative indicating negative correlation.Only approximately 25% of people who are marked as hireable shared their email.
### Recommendtion based on Analysis:
One recommendation can be to increase the number of developers who are hireable to share their email id so as for better reach in case of an opportunity. Another recommendation based on analysis can be done that quality of repositories and their impact on the community matters rather than number of repositories, hence the impactful repositories gain more followers than others.
