---
layout: post
title: HRF Asyulm Project
subtitle: My contributions to the Human Rights First Asylum application
---

This project was a collaboration between Lambda School and Human Rights First, a nonprofit organization that challenges America to live up to her ideals.
Each year, tens of thousands of people seek refuge in the United States, and only a small portion of those are allowed in. The tool we built gives lawyers better aggregate data about favorable rulings to help them get their clients into the country, and out of danger. Going into this project I was afraid it might become political, yet Human Rights First has done a great job of keeping policits out of their goals.

#### Technical Contributions
A big part of the project was to be able to communicate quickly and clearly to lawyers information about previous cases to inform their current case. To do this, we made visualizations that can be loaded dynamically about whatever the user would like to see in the moment. I helped design these visualizations to convey information in the most helpful way possible. We went with a stacked bar chart, which can show information about many categories at once.

The main technical challenge for this task was code compatibility. The front and backend is written in Javascript, and our team works in Python, so getting our visualizations to the frontend presented a problem. We saw two ways to solve this. The first would be to set up an endpoint that takes type of information requested and return a png that the frontend can display. This works, but it makes our visualizations static; the frontend couldn't tweak them at all if they wanted to. The second, better option would be to return a Plotly JSON object, and let the frontend generate the visualization with Plotly in Javascript. This way the frontend can change them as they see fit, and we only have to maintain the data behind it.

#### Current and Future State of the Project
As of right now, the HRF Asylum application is just about ready for public use. Currently, laywers can upload their past cases, see information about case outcomes broadly, and sort by judges to see how specific judges have ruled in the past. The only thing holding the application back is a lack of cases in the database. Right now we only have about 200 cases from a handful of judges. Once we obtain more cases, the project can be fleshed out much better, and will in turn be appealing for more lawyers.

Going forward, I forsee one main feature being grately improved to help with this problem. Right now a lawyer can upload a case, and our application will scrape the pdf for the relevant information. Some pieces it is really good at finding, like the judge, and some pieces aren't super clear, so the user has to put those in manually. If we can fix this problem, users will be more inclined to upload their cases, as it won't be much of a hassle for them. Eventually, this will give us enough data to release the project broadly.

This project has helped me learn to work in a team, something I have not always been great at. I also learned how to use the Plotly API, and going through this process helped me learn how to learn. Going forward I believe this will be one of the most valuable skills I can have. In my career I will always be working with new frameworks and APIs, and being able to keep up with the market will make me a valuable employee, wherever I work.
