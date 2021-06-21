## Activity File: Exploring Kibana

* You are a DevOps professional and have set up monitoring for one of your web servers. You are collecting all sorts of web log data and it is your job to review the data regularly to make sure everything is running smoothly. 

* Today, you notice something strange in the logs and you want to take a closer look.

* Your task: Explore the web server logs to see if there's anything unusual. Specifically, you will:

:warning: **Heads Up**: These sample logs are specific to the time you view them. As such, your answers will be different from the answers provided in the solution file. 

---

### Instructions

1. Add the sample web log data to Kibana.
2. Answer the following questions:  

## Cooresponding Screenshots for the below activity can be found in the link below. 
![Screenshots](Images/)

- In the last 7 days, how many unique visitors were located in India?
     - In the last 7 days there were 224 unique visitors from the country of India. 

- In the last 24 hours, of the visitors from China, how many were using Mac OSX?
     - In the past 24 hours the amount of users that were using the Mac OSX OS were 27.91%

- In the last 2 days, what percentage of visitors received 404 errors? How about 503 errors?
     - 2.78% of the people connecting received 404 codes, while 4.16% received 503 codes. 

- In the last 7 days, what country produced the majority of the traffic on the website?
     - In the last 7 days the counrty with the most traffic produced was China.

- Of the traffic that's coming from that country, what time of day had the highest amount of activity?
     - The heat map shows that the highest ammountof traffic apperast to be around hour 10. 

- List all the types of downloaded files that have been identified for the last 7 days, along with a short description of each file type (use Google if you aren't sure about a particular file type).
     - In the last 7 days there have been reported downloads of .gz (an archive file compressed by GNU zip), .css (this file is used to format contents of a webpage), .zip (this is an archive file that supports lossless data compression),   .deb (a software package from a linux distribution), and .rmp files (Package manager files).



3. Now that you have a feel for the data, Let's dive a bit deeper. Look at the chart that shows Unique Visitors Vs. Average Bytes.

- Locate the time frame in the last 7 days with the most amount of bytes (activity).
     - 6-19-2021 at 19:00 has the highest count of bytes in the past 7 days with 9,002 bytes.

- In your own words, is there anything that seems potentially strange about this activity?
     - This activity seems strange because the byte count is double what is usually seems to be, but only has a count of 2. Versus the others with byte counts of 5,000 have counts between 40-79.



4. Filter the data by this event.

- What is the timestamp for this event?
     - The time stamp is 6-19-2021 at 19:00

- What kind of file was downloaded?
     - The type of file that was downloaded was a zip file.

- From what country did this activity originate?
     - The country in which it originated is from BR. 

- What HTTP response codes were encountered by this 
visitor?
     - The response code received by the visitor was the code 200. Which is the HTTP success response code.



5. Switch to the Kibana Discover page to see more details about this activity.

- What is the source IP address of this activity?
     - The client IP is 17.111.163.53

- What are the geo coordinates of this activity?
{
  "lat": 42.59157139,
  "lon": -114.7967178
}

- What OS was the source machine running?
     - The OS running on the machine is windows 7

- What is the full URL that was accessed?
     - https://artifacts.elastic.co/downloads/kibana/kibana-6.3.2-windows-x86_64.zip
	

- From what website did the visitor's traffic originate?
     - http://twitter.com/success/mark-kelly



6. Finish your investigation with a short overview of your insights. 

- What do you think the user was doing?
     - It looks like the user was downloading zip file containing kibana setup files.

- Was the file they downloaded malicious? If not, what is the file used for?
     - It does not look malicious, it look slike it its used to set up kibana. 

- Is there anything that seems suspicious about this activity?
     - The only thing tha seems suspicious is the amount of bytes used for one person during this period. 

- Is any of the traffic you inspected potentially outside of compliance guidlines?
     - No traffic seemed to be out of compliance. 


---
© 2020 Trilogy Education Services, a 2U, Inc. brand. All Rights Reserved.  