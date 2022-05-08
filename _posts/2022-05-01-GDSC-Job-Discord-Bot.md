---
title: GDSC Job Discord Bot
date: 2022-05-01
tags: [SQL,Python,WebScraping]
---

<hr>

This academic year (2021-2022) I was the president of the Google Developer Student Club, and in the winter semester I led and managed a project to create a discord bot 
that posts internships and job postings based on user preferences (location, job keywords). Furthermore, the bot has a notification feature where it
can notify the user of new job postings based on the notification interval provided by the user.   

University students search for internships on various job boards and to ease this process we decided to create a discord bot that can take user preferences i.e
locations, job keywords and notification interval and provide the job postings. I led a team of 7 and held weekly meetings and used SCRUM practices. I initially divided the teams into 3 - Database team, WebScraping team and Bot Configuration team.  

We begun by setting up a SQL database with the users and jobs tables,and scraped jobs from Indeed and LinkedIn then stored the postings in the database.   
For the bot configuration we designed user commands to start with ! and used a UI which displays 10 jobs per page with the Title, location, date and link to the job posting. The user can then click next or previous to view the next page. We sorted the jobs by date so that users can see the latest job postings first.

<hr>
<h3> Team Members: </h3>
* [Akrash Sharma](https://github.com/Akarsh654/)   
* [Ze Hui Peng](https://github.com/zhpeng811)  
* [Kelly Shih](https://github.com/kelly-shih/)  
* [Chee Tey](https://github.com/cheetiantey)  
* [Paul Bakshi](https://github.com/AinJex)  
* [Faiyad Rahman](https://github.com/FaiyadRahman)  
* [Pratham Arora](https://github.com/PrathamArora20)  

The full code can be found at [GitHub](https://github.com/Google-DSC-UAlberta/Discord-Bot)   

<hr>
<h3> User commands: </h3>  
<a href="https://imgbb.com/"><img src="https://i.ibb.co/ykrk6qZ/method.png" alt="method" border="0"></a>    



<hr>
<h3> Use Case:   </h3>   
<a href="https://ibb.co/Z66CXFv"><img src="https://i.ibb.co/XZZTLK6/register.png" alt="register" border="0"></a>   
<a href="https://ibb.co/ZH2gygd"><img src="https://i.ibb.co/Q8DHsH9/Inkedbot-LI.jpg" alt="Inkedbot-LI" border="0"></a>     



