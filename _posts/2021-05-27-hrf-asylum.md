---
layout: post
title: The Blue Witness Project
subtitle: My contributions to the Human Rights First Blue Witness application
---

This project was a collaboration between Lambda School and Human Rights First, a nonprofit organization that challenges America to live up to her ideals.
Inapropirate use of police force has been a problem for some time, so I helped build a tool to keep track of incidents around the country to keep police 
forces honest. Going into this project I was afraid it might become political, yet Human Rights First has done a great job of keeping policits out of their goals.

#### Technical Contributions
To obtain information for this project we scraped Twitter for keywords related to police activity, and presented those tweets to an admin to approve to be put on the map. Often times these tweets describe real incidents, yet they don't include enough information to be usable. I was tasked with writing a Twitter bot that could reply to these sources to ask for more information. It then updates the information with the response to be approved by the admin again.

The main technical challenge for this task was code compatibility. The front and backend is written in Javascript, and I work in Python, so implimenting my rough bot could prove to be difficult. Luckily, I know a little Javascript, enough that I was able to rewrite it in Javascript. While it did take some time, it made implimentation a simple function call.

#### Current and Future State of the Project
As of right now, the Blue Wintess application is basically ready for public use. The users can clearly see, understand and interact with the incident map. There are sections for more information about recent incidents and general information on the severity of incidents. The admin board is fully functional. Once a day Twitter is scraped for incidents, which can then be approved, rejected, or have more information requested via the Twitter bot.

Going forward, a number of improvements and new features can be added. To start, the admin board is often flooded with incidents, many of which are duplicates. Being able to idenify and remove these duplicates before the admin sees them would greatly reduce their workload. One potential new feature could be to scrape data from Reddit as well as Twitter. Many people use Reddit, and posts are often times very through. Using this as a source could greatly improve the quality of the incidents presented to the admin board, as well as find stories that did not appear on Twitter.

This project has helped me learn to work in a team, something I have not always been great at. I also learned how to use the Twitter API, and going through this process helped me learn how to learn. Going forward I believe this will be one of the most valuable skills I can have. In my career I will always be working with new frameworks and APIs, and being able to keep up with the market will make me a valuable employee, wherever I work.
