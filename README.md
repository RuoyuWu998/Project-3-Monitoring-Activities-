# Project-3-Monitoring-Activities-
## Team member: Ruoyu Wu 
### Project Description
The log file containing information regarding the activities of users. My reports provide insights into the activities of the users which can help in making decisions for the higher officials.
### Flow description
This project has a function including four functions including detecting suspicious activities, irresponsible behaviors, glitches and domain count.
#### Suspicious Activities 
If any user logs into any of the systems more than 5 times in a single day, or if the user logs into any of the systems even once between 12:00 am to 5:00 am, it is marked as suspicious behavior. The first step is to read the data line by line and make each line a list with sepcific individual's information. The next step is to count the total login number of each user in each day. Check if the number is larger than 5.  
