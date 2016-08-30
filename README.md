# Project7_DataSience_Udacity_DataVisualization
Visualizing Titanic data set through a bar chart, using Dimple.js 
This chart is visualization of corrolation between class and gender with survival rate of the passengers.

final_chart0.html(first iteration) : this is my first iteration of the visualization. The first person that saw this chart believed commented that the legend is not descriptive enough and instead of 1 and 0 for survived and not survived, there should be the actual words to make it easier for the viewer to understand the chart

final_chart1.html(second iteration) : the second commenter believed that the text that comes up when hovering over part of a chart shows survived=0 when hovering on the part that shows the percentage of people that perished and that can be confusing.

final_chart2.html(third iteration) : the third commenter said that it would be better to have some title to describe the purpose of the chart and that it would be better that the chart was larger and at the centre of the screen.

final_chart3.html(forth iteration) : this include the last change suggested by the third commenter.


Design decision :

I first experimented with the age being at the x axis and percentage of survival being at y axis using two line plots with different colors for males and females. The plot was an irregular ziczac line, showing no corrolation. and it corresponded with findings in project2 using pearsons r function. the only sound and substantial corrolation would be between pclass(passengers ticket class) and survival rate and between gender and survival rate. in order to convey the most relevant information from the dataset where most information is included bar chart seemed to be the best choice. there are two discrete parameters: gender and class and scater plot and line plot are not the best option for that purpose.
Here we have two categories and we want to compare the magnitude using a stacked bar chart. It is easier to compare to have two bar charts side by side. We have discrete values along x axis. For these reasons stacked bar chart seem to be the best option. I could have only shown the survival percentage which would also convey the information intended. I chose to show both percentages of survived and perished to highlight, in a very stark manner, the magnitude of perished for every group and it makes it easier to compare by the size of the charts. 
I chose two distinct colors for the two separate groups without varying in percieved intensity and the intensity is well balanced. The colors chosen are not unnecessarily too bright as the intention was not to make one group to stand out and also did not want to make in unpleasant and straining to the viewers eyes. 
