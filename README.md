# Kickstarter-Analysis
## Project Overview
* Helping my friend Louise take a closer look at Kickstarter data, specifically at how campaigns performed based on their goal and based on their launch date. 
### Analysis and Challenges
* To check how campaigns performed based on their launch date I created a pivot table, and used that pivot table to make a line graph. It was challenging to choose the right filter categories for the pivot table, but once I created the line graph it made clear which filters are correct. ![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/82781202/146693045-9dfceab2-8d55-44d3-b007-eb14a55b8614.png)
* To check how campaigns performed based on their goal I created a new table based on goal range, and used the countifs() formula to filter through the original data for what I was looking for. I then used this new table to create a line graph. It was challenging to ensure that the countifs() were using the correct criteria and returning the correct results, I used filters on the Kickstarter data to spotcheck if my countifs() were working correctly. ![Outcomes_vs_Goals](https://user-images.githubusercontent.com/82781202/146693074-60c6fd0e-1c64-4601-a85d-c7c8f2632be4.png)
#### Results
* I can conclude that the probability of a theater campaign being canceled is not related to the launch date of that campaign. The line representing canceled campaigns line stays relativley flat throughout. I can also conclude that the succesfulness of a theater campaign does appear to be related to the launch date. There were more successful outcomes between March and May.
* I can conclude that goal amount is not a driving force in how succesful a play campaign is. As you can see in the graph above, there is not a definite trend between goal amount and success rate.
I find that a huge limiting factor of this dataset is we don't have any data that describes the quality of the kickstarter campaign, we can't test if the success rate is related to how "good" the campaign idea is.
We could also create a graph that shows the relationship between how well a campaign performed and how long it was open for pledges. 
