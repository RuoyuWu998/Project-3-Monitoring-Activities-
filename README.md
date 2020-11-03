# Project-3-Monitoring-Activities-
## Team member: Ruoyu Wu 
### Project Description
The log file containing information regarding the activities of users. My reports provide insights into the activities of the users which can help in making decisions for the higher officials.
### Flow description
This project has a function including four functions including detecting suspicious activities, irresponsible behaviors, glitches and domain count.
#### Suspicious Activities 
If any user logs into any of the systems more than 5 times in a single day, or if the user logs into any of the systems even once between 12:00 am to 5:00 am, it is marked as suspicious behavior. The first step is to read the data line by line and make each line a list with sepcific individual's information. The next step is to count the total login number of each user in each day. Check if the number is larger than 5.  Record all activites for the person in that day as a list. The next step is to check if the login time is  24:00 to 5:00 (12:00 a.m. to 5:00 a.m.). If login time is between the time mentioned before. Record all activities of the person in that day as a list. Fuse two recorded list and write a txt file to record all suspicious activities.
### Irresponsible Behaviors and Glitches
Read the data line by line and make each line a list with sepcific individual's information. Iterate through individuals' information and count the number of a person's login and logout in a day. If the number of login> logout, record the activites as irresponsible behaviors. If the number of logout>login, record the activities as glitches. Write a txt file to record irresponsible behavior and another txt file to record glitches.
### Domain Count
Create a disctionary with unique emails and convert it to a list containing only the domains of the emails. Count the number of each domain and create a dictionary invloves domain name and the number of time it appears in the list I mentioned before which is a list of all the unique domains and the number of users registered within each domain. Write a txt file to record the information.
