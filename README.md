# Kickstarter-Analysis
## Project Overview
* Helping my friend Louise take a closer look at Kickstarter data, specifically at how campaigns performed based on their goal and based on their launch date. 
### Analysis and Challenges
* To check how campaigns performed based on their launch date I created a pivot table, and used that pivot table to make a line graph. It was challenging to choose the right filter categories for the pivot table, but once I created the line graph it made clear which filters are correct. ![image_name](path/to/Theater_Outcomes_vs_Launch.png)
* To check how campaigns performed based on their goal I created a new table based on goal range, and used the countifs() formula to filter through the original data for what I was looking for. I then used this new table to create a line graph. It was challenging to ensure that the countifs() were using the correct criteria and returning the correct results, I used filters on the Kickstarter data to spotcheck if my countifs() were working correctly. 
#### Results
* I can conclude that the probability of a theater campaign being canceled is not related to the launch date of that campaign. The line representing canceled campaigns line stays relativley flat throughout. I can also conclude that the succesfulness of a theater campaign does appear to be related to the launch date. There were more successful outcomes between March and May.
*  
