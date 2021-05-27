---
layout: post
title: HRF Asyulm Project
subtitle: My contributions to the Human Rights First Asylum application
---

This project was a collaboration between Lambda School and Human Rights First, a nonprofit organization that challenges America to live up to her ideals.
Each year, tens of thousands of people seek refuge in the United States, and only a small portion of those are allowed in. The tool we built gives lawyers better aggregate data about favorable rulings to help them get their clients into the country, and out of danger. Going into this project I was afraid it might become political, yet Human Rights First has done a great job of keeping policits out of their goals.

#### Technical Contributions
A big part of the project was to be able to communicate quickly and clearly to lawyers information about previous cases to inform their current case. To do this, we made visualizations that can be loaded dynamically about whatever the user would like to see in the moment. I helped design these visualizations to convey information in the most helpful way possible. We went with a stacked bar chart, which can show information about many categories at once.

The main technical challenge for this task was code compatibility. The front and backend is written in Javascript, and I work in Python, so implimenting my rough bot could prove to be difficult. Luckily, I know a little Javascript, enough that I was able to rewrite it in Javascript. While it did take some time, it made implimentation a simple function call.

#### Current and Future State of the Project
As of right now, the Blue Wintess application is basically ready for public use. The users can clearly see, understand and interact with the incident map. There are sections for more information about recent incidents and general information on the severity of incidents. The admin board is fully functional. Once a day Twitter is scraped for incidents, which can then be approved, rejected, or have more information requested via the Twitter bot.

Going forward, a number of improvements and new features can be added. To start, the admin board is often flooded with incidents, many of which are duplicates. Being able to idenify and remove these duplicates before the admin sees them would greatly reduce their workload. One potential new feature could be to scrape data from Reddit as well as Twitter. Many people use Reddit, and posts are often times very through. Using this as a source could greatly improve the quality of the incidents presented to the admin board, as well as find stories that did not appear on Twitter.

This project has helped me learn to work in a team, something I have not always been great at. I also learned how to use the Twitter API, and going through this process helped me learn how to learn. Going forward I believe this will be one of the most valuable skills I can have. In my career I will always be working with new frameworks and APIs, and being able to keep up with the market will make me a valuable employee, wherever I work.
