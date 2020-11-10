# Project-3-Monitoring-Activities-
## Team member: Ruoyu Wu 
### Project Description
The log file containing information regarding the activities of users. My reports provide insights into the activities of the users which can help in making decisions for the higher officials.
### Flow description
This project contain 5 parts including detecting suspicious activities, irresponsible behaviors, glitches, domain count and laziness. 
### Read the Log File 
Read the log file line by line and make each line a list with specific individual's information. Make a dictionary. The key is the name and the value is another dictionary which has date as the key and other corresponding informtion (time, activity and server) in a list as value. 
#### Suspicious Activities 
If any user logs into any of the systems more than 5 times in a single day, or if the user logs into any of the systems even once between 12:00 am to 5:00 am, it is marked as suspicious behavior. Count the total login number of each user in each day. Check if the number is larger than 5. The next step is to check if the login time is  00:00 to 5:00 (12:00 a.m. to 5:00 a.m.). If login time is more than 5 times or between the time mentioned before, print all information in that day. Write a txt file to record the suspicious activities.
#### Irresponsible Behaviors and Glitches
Count the total login and logout number of each user in each day. If the number of login> logout, record the activites as irresponsible behaviors. Print all information in days with irresponsible behaviors. If the number of logout>login, record the activities as glitches.Print all information in days with glitch. Write a txt file to record irresponsible behavior and another txt file to record glitches.
#### Domain Count
Create a disctionary with unique emails and convert it to a list containing only the domains of the emails. Count the number of each domain and create a dictionary invloves domain name and the number of time it appears in the list I mentioned before which is a list of all the unique domains and the number of users registered within each domain. Write a txt file to record the information.
### Laziness 
If any user logs into any of the susyems less than twice in a single day and the number of login = logout, record the activities as " laziness". Count the number of login and logout. Print all information in days with laziness. Write a txt file to record the information.
