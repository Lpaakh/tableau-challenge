# tableau-challenge

In this project Laura Paakh May created visualizations and analyzed data for the New York Citi Bike Program. 

Analysis:
The graphs plotted depict that total count of riders was significantly effected by the pandemic shutdown. The number of riders in April 2020 after the state shutdown on March 20, 2020 plummeted lower than any count in 2017-2020 to roughly 683,000. In prior years April came in at 1.3 and 1.7 million users. Usually the lines make somewhat of a scoop shape with January as the lowest point possibly due to colder winter temperatures, but in 2019-2020 the graph makes somewhat of a V shape. The unexpected phenomena is that in May of 2020 the number of users more than doubled to roughly 1.5 million. This could theoretically be explained by the need to get food and other essentail items, people feeling couped up and needing to get out again, etc.

The lines of the next graphs of gender counts follow similar patterns as the total count graphs when the rider count gets to March and April. The shutdown did indeed significantly lower the number of riders especially in April 2020 compared to April of 2018 and 2019. The visualization shows a much greater number of males riding the bikes compared to female and other genders. These graphs highlight the need for diverisifying the bike program outreach to female and other genders. There are possibly cultural tendencies that drive males to ride bike more than other genders. Also there may be a marketing strategy for the bikes that appeals more to male riders. 

Another set of visualizations show the most unexpected phenomena of all the dashboards. There is a high propensity of the 1969 birth year. An explanation for this could be that a large group of people does not wish to share their actual birth year in American culture and may think it's fun to have 1969 as thier year. There is also a fair amount of people that recorded their birth years before 1910; one can speculate with strong certainty that in 2019 there were not any bicyclers riding that were born in 1857 or any born before 1910. 

The map provides the most popular start and end stations for the citi bikes with zip codes. An unexpected phenomena is the lack of bike users around central park. The lower count of bikers despite this being a popular tourist destination could be due to the COVID-19 pandemic and inturn less tourism traffic and people gathering in smaller groups. There lowest numbers appear to be concentrated at the 07302, 07304, 07306, 07307 zip codes and 10452, 10455, 10459 zip codes. More advertising and marketing outreach could be needed in these areas.

Laura Paakh May completed the analysis with the below assignment specifications:

"Your task in this assignment is to aggregate the data found in the Citi Bike Trip History Logs and find two unexpected phenomena.
Design 2-5 visualizations for each discovered phenomena (4-10 total). You may work with a timespan of your choosing. Optionally, you may merge multiple datasets from different periods.
The following are some questions you may wish to tackle. Do not limit yourself to these questions; they are suggestions for a starting point. Be creative!


How many trips have been recorded total during the chosen period?


By what percentage has total ridership grown?


How has the proportion of short-term customers and annual subscribers changed?


What are the peak hours in which bikes are used during summer months?


What are the peak hours in which bikes are used during winter months?


Today, what are the top 10 stations in the city for starting a journey? (Based on data, why do you hypothesize these are the top locations?)


Today, what are the top 10 stations in the city for ending a journey? (Based on data, why?)


Today, what are the bottom 10 stations in the city for starting a journey? (Based on data, why?)


Today, what are the bottom 10 stations in the city for ending a journey (Based on data, why?)


Today, what is the gender breakdown of active participants (Male v. Female)?


How effective has gender outreach been in increasing female ridership over the timespan?


How does the average trip duration change by age?


What is the average distance in miles that a bike is ridden?


Which bikes (by ID) are most likely due for repair or inspection in the timespan?


How variable is the utilization by bike ID?


Next, as a chronic over-achiever:

Use your visualizations (does not have to be all of them) to design a dashboard for each phenomena.
The dashboards should be accompanied with an analysis explaining why the phenomena may be occuring.

City officials would also like to see one of the following visualizations:


Basic: A static map that plots all bike stations with a visual indication of the most popular locations to start and end a journey with zip code data overlaid on top.


Advanced: A dynamic map that shows how each station's popularity changes over time (by month and year). Again, with zip code data overlaid on the map.


The map you choose should also be accompanied by a write-up unveiling any trends that were noticed during your analysis.


Finally, create your final presentation

Create a Tableau story that brings together the visualizations, requested maps, and dashboards.
This is what will be presented to the officials, so be sure to make it professional, logical, and visually appealing.


Considerations
Remember, the people reading your analysis will NOT be data analysts. Your audience will be city officials, public administrators, and heads of New York City departments. Your data and analysis needs to be presented in a way that is focused, concise, easy-to-understand, and visually compelling. Your visualizations should be colorful enough to be included in press releases, and your analysis should be thoughtful enough for dictating programmatic changes.

Submission
Your final submission should include:

A link to your Tableau Public workbook that includes:

4-10 Total "Phenomenon" Visualizations
2 Dashboards
1 City Official Map
1 Story


A text or markdown file with your analysis on the phenomenons you uncovered from the data.


Sharing Your Work
In order to share your work, we are asking that you will save your workbook as a .twbx file so that your TA's can grade them.
To save your workbook as a .twbx file, you will just need to select "Save As..." from the "File" dropdown. Then, select the .twbx option.

Assessment
Your final product will be assessed on the following metrics:


Analytic Rigor


Readability


Visual Attraction



Hints


You may need to get creative in how you combine each of the CSV files. Don't just assume Tableau is the right tool for the job. At this point, you have a wealth of technical skills and research abilities. Dig for an approach that works and just go with it.


Don't just assume the CSV format hasn't changed since 2013. Subtle changes to the formats in any of your columns can blockade your analysis. Ensure your data is consistent and clean throughout your analysis. (Hint: Start and End Time change at some point in the history logs).


Consider building your visualizations with small extracts of the data (i.e. single files) before attempting to import the whole thing. What you will find is that importing all 20+ million records of data will create performance issues quickly. Welcome to "Big Data."


While utilizing all of the data may seem like a nice power play, consider the time-course in making your analysis. Is data from 2013 the most relevant for making bike replacement decisions today? Probably not. Don't let overwhelming data fool you. Ground your analysis in common sense.


Remember, data alone doesn't "answer" anything. You will need to accompany your data visualizations with clear and directed answers and analysis.


As is often the case, your clients are asking for a LOT of answers. Be considerate about their need-to-know and the importance of not "cramming in everything". Of course, answer each question, but do so in a way that is organized and presentable.


Since this is a project for the city, spend the appropriate time thinking through decisions on color schemes, fonts, and visual story-telling. The Citi Bike program has a clear visual footprint. As a suggestion, look for ways to have your data visualizations match their aesthetic tones.


Pay attention to labels. What exactly is "time duration"? What's the value of "age of birth"? You will almost certainly need calculated fields to get what you need.


Keep a close eye for obvious outliers or false data. Not everyone who signs up for the program is answering honestly.


In answering the question of "why" a phenomenon is occurring, consider adding other pieces of information on socioeconomic or other geographic data. Tableau has a map "layer" feature that you may find handy.


Don't be afraid to manipulate your data and play with settings in Tableau. Tableau is meant to be explored. We haven't covered all that you need -- so you will need to keep an eye out for new tricks.


Treat this as a serious endeavor! This is an opportunity to show future employers that you have what it takes to be a top-notch analyst.


Good luck!



Copyright
Data Boot Camp © 2019. All Rights Reserved."
