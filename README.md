# Project7_DataSience_Udacity_DataVisualization
Visualizing Titanic data set through a bar chart, using Dimple.js 
This chart is visualization of corrolation between class and gender with survival rate of the passengers.

first iteration : this is my first iteration of the visualization. The first person that saw this chart believed commented that the legend is not descriptive enough and instead of 1 and 0 for survived and not survived, there should be the actual words to make it easier for the viewer to understand the chart

second iteration : the second commenter believed that the text that comes up when hovering over part of a chart shows survived=0 when hovering on the part that shows the percentage of people that perished and that can be confusing.

third iteration : the third commenter said that it would be better to have some title to describe the purpose of the chart and that it would be better that the chart was larger and at the centre of the screen.

forth iteration : this include the last change suggested by the third commenter.


Design decision :

I first experimented with the age being at the x axis and percentage of survival being at y axis using two line plots with different colors for males and females. The plot was an irregular ziczac line, showing no corrolation. and it corresponded with findings in project2 using pearsons r function. the only sound and substantial corrolation would be between pclass(passengers ticket class) and survival rate and between gender and survival rate. in order to convey the most relevant information from the dataset where most information is included bar chart seemed to be the best choice. there are two discrete parameters: gender and class and scater plot and line plot are not the best option for that purpose.
