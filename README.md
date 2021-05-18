# Visualizations for Data Viz
## Jittered dot plot
![1-Jittered dot plot](https://user-images.githubusercontent.com/44620594/118350637-867dc300-b51d-11eb-975f-52c0f2dc2ee7.png)    
    
*Principle 1 - Maximizing the data-ink ratio*    
Unnecessary borders and lines were removed. The present lines -- the dotted horizontal lines -- serve as guiding markers to help viewers clarify which dots belong to which months as the dots extend further away from the name of the months found on the y-axis. I also scaled daily COVID-19 cases to thousands in order to save "ink".

*Principle 2 - Mobilize every graphical element to show the data*    
I feel like this type of chart already conforms to this principle, as every data point is unobstructed by graphical elements and clearly distinguishable. I am not sure what I could have done here improve on this principle.

*Principle 3 - Maximize data density and the size of the data matrix*    
I feel like this plot conforms to maximizing data density as I am displaying three sources of information (months, counts of daily reported COVID-19 cases, and types of COVID-19 cases). As for maximizing the size of the data matrix, I increased the plot margins to allow for more space between the dots and pushed out the x-/y-axis labels closer to the outer limits. At first, I played around with shrinking the data points but this effort made it more difficult to discern how many cases each dot represented. I ultimately chose to make the data dots a bit larger.

*Principle 4 - Escape flatland*    
I used color to display multivariate data (months and type of COVID-19 case).

*Principle 5 - Provide the user with an overview and details*    
The x-/y-axis are labeled appropriately to provide viewers with information to make sense of the graph. Further, I provided a legend describing what each color means. One thing I could have done, but admittedly had difficulty doing, is to provide a red diamond-shaped label in the legend indicating that the red diamond in the graph represents the month average of daily COVID-19 cases.

*Principle 6 - Utilize layering and separation*    
I used color to separate type of COVID-19 case (active vs deaths vs recovered). Also, I provided a particular color and shape to the month average of daily COVID-19 cases.

*Principle 7 - Utilize narratives of space and time*    
The position of a dot on its corresponding dotted horizontal line informs the viewer the space a) between each dot, b) between the dot and 0, and c) between each dot and the maximine value. These anchors provide a clear narrative to the viewer of the daily amounts of COVID-19 cases per month, which is the intention of the data visualization.

*Narrative analysis*    
The jittered dot plot illustrates daily amounts of COVID-19 cases -- broken down by month and type of case -- in the USA from October 2020 to March 2021. As can be seen from the visualization, the month of January 2021 saw some of the highest number of daily reported COVID cases, reaching up to 300,000, while the months of October 2020 and March 2021.


## Stacked histogram
![2-Stacked histogram](https://user-images.githubusercontent.com/44620594/118350638-867dc300-b51d-11eb-8f9a-9c74cefee391.png)    
    
*Principle 1 - Maximizing the data-ink ratio*    
Unnecessary borders and lines were removed. The horizontal lines were added to help viewers identify where sections of each distribution falls along the y-axis. I also scaled confirmed COVID-19 cases to millions in order to save "ink".

*Principle 2 - Mobilize every graphical element to show the data*    
I feel like this chart conforms to this principle fairly well, as the shape of each distribution is visible despite the presence of overlap. I understand that this principle might be improved if I used multiplots to display each distribution. However, I feel comparison between distributions is much easier by stacking them, given the similarity of each distribution.

*Principle 3 - Maximize data density and the size of the data matrix*    
I feel like this plot conforms to maximizing data density as I am displaying three sources of information (months, number of confirmed COVID-19 cases, and types of COVID-19 cases). As for maximizing the size of the data matrix, I increased the plot margins to allow for the distributions to take up more space. Also, I moved the legend into the chart area to allow more space for the data matrix.

*Principle 4 - Escape flatland*    
I used color to display multivariate data (months and type of confirmed COVID-19 case).

*Principle 5 - Provide the user with an overview and details*    
The x-/y-axis are labeled appropriately to provide viewers with information to make sense of the graph. Further, I provided a legend describing what each color means.

*Principle 6 - Utilize layering and separation*    
I used color to separate type of confirmed COVID-19 case (recovered vs deaths vs active). In hindsight, I could have kept the same order for the COVID-19 type as in the jittered dot plot.

*Principle 7 - Utilize narratives of space and time*    
The lines are portrayed across several months, utilizing time to inform the narrative.

*Narrative analysis*    
The stacked histogram illustrates the distribution of confirmed COVID-19 cases broken down by month and type of case. The months span March 2020 to March 2021. As can be seen from the visualization, the distribution for individuals who recovered from COVID-29 is greater than the number of active COVID-29 cases at each month starting from May 2020.

## Faceted waffle bar chart
![3-Faceted waffle bar chart](https://user-images.githubusercontent.com/44620594/118350639-87165980-b51d-11eb-9701-6db1e83efbe3.png)    
    
*Principle 1 - Maximizing the data-ink ratio*    
Unnecessary borders and lines were removed.

*Principle 2 - Mobilize every graphical element to show the data*    
I feel like this type of chart already conforms to this principle, as every data point is unobstructed by graphical elements and clearly distinguishable. I am not sure what I could have done here improve on this principle.

*Principle 3 - Maximize data density and the size of the data matrix*    
I feel like this chart conforms to maximizing data density as I am displaying three sources of information (sex, counts of lab-confirmed COVID-19 cases, and age group). As for maximizing the size of the data matrix, I widened the plot margins to allow for more separation between each "waffle".

*Principle 4 - Escape flatland*    
I used color to display multivariate data (months and type of COVID-19 case).

*Principle 5 - Provide the user with an overview and details*    
The x-/y-axis are labeled appropriate to provide viewers with information to make sense of the graph. Further, I provided a legend describing what each color means. One thing I could have done, but admittedly had difficulty doing, is to provide a red diamond-shaped label in the legend indicating that the red diamond in the graph represents the month average of daily COVID-19 cases.

*Principle 6 - Utilize layering and separation*    
I used color to separate type of COVID-19 case (active vs deaths vs recovered). Also, I provided a particular color and shape to the month average of daily COVID-19 cases.

*Principle 7 - Utilize narratives of space and time*    
I am not sure what I could have done here for this type of chart.

*Narrative analysis*    
The faceted waffle bar chart illustrates the proportion of confirmed COVID-19 cases in TX, grouped by sex and age group. Data displays a snapshot of the month of April, 2021.
As can be seen from the visualization, higher proportions of males had onfirmed COVID-19 cases - specifically, males between the ages of 18 to 49. After maies, individuals with no provided sex information had the highest proportions of confirmed COVID-19 cases, which included individuals between 18 to 49 yr olds as well as individuals 65 and older. On the other hand, females between the ages of 18 and 49 had the lowest proportions of onfirmed COVID-19 cases. 


## Edge bundle chart
![4-Edge bundle chart](https://user-images.githubusercontent.com/44620594/118350640-87165980-b51d-11eb-8838-21e615a2c0e5.png)    
    
*Principle 1 - Maximizing the data-ink ratio*    
Only necessary graphic elements were kept.

*Principle 2 - Mobilize every graphical element to show the data*    
I feel like this type of chart already conforms to this principle, as every data point is unobstructed by graphical elements and clearly distinguishable. I am not sure what I could have done here improve on this principle.

*Principle 3 - Maximize data density and the size of the data matrix*    
I could have maximzied data density by manipulating thickness levels to the lines or by color coding the lines based on association ranges. However, my intention is to illustrate the assocations of Question 1 to other Questions, so I did not want to detract from that narrative. As for maximizing the size of the data matrix, I feel like this type of chart already conforms to this principle, given that the data matrix makes up most of the visualization. I am not sure what I could have done here improve on this principle.

*Principle 4 - Escape flatland*    
I used color to display multivariate data (months and type of COVID-19 case).

*Principle 5 - Provide the user with an overview and details*    
The x-/y-axis are labeled appropriate to provide viewers with information to make sense of the graph. Further, I provided a legend describing what each color means. One thing I could have done, but admittedly had difficulty doing, is to provide a red diamond-shaped label in the legend indicating that the red diamond in the graph represents the month average of daily COVID-19 cases.

*Principle 6 - Utilize layering and separation*    
I used color to separate type of COVID-19 case (active vs deaths vs recovered). Also, I provided a particular color and shape to the month average of daily COVID-19 cases.

*Principle 7 - Utilize narratives of space and time*    
As a general benefit of dot plots, the position of a dot on its corresponding dotted horizontal line informs the viewer the space a) between each dot, b) between the dot and 0, and c) between each dot and the maximine value. These anchors provide a clear narrative to the viewer of the daily amounts of COVID-19 cases per month, which is the intention of the data visualization.

*Narrative analysis*    
The edge bundle chart illustrates moderate to strong associations between 12 questions of a trauma-informed care tool, with each line representing an association between two questions. As shown in the chart, moderate to strong associations are present between all questions, except for Question 1 with Questions 4, 5, and 8. Lines going from Question 1 are shown in red to highlight the absence of moderate or strong associations with Questions 4, 5, and 8.



## Line graph
![5-Line chart](https://user-images.githubusercontent.com/44620594/118350641-87165980-b51d-11eb-8a47-ef0c8c850b58.png)    
    
*Principle 1 - Maximizing the data-ink ratio*    
Unnecessary borders and lines were removed. Further, I removed all months from the x-axis except for the first and last month (March 2020 and March 2021). While unconventional, I felt that keeping all of the months added clutter to the fitted line, confidence intervals, and residuals - all of which are the main focus of the visualization. I also added dotted horizontal lines for guiding purposes. I also scaled COVID-19 cases to thousands in order to save "ink".

*Principle 2 - Mobilize every graphical element to show the data*    
After removing unnecessary and distracting graphical elements, I feel like this type of chart conforms well to this principle. I have not identified any graphical element that obstructs the data.

*Principle 3 - Maximize data density and the size of the data matrix*    
I feel like this graph conforms to maximizing data density as I am displaying three sources of information (fitted line, confidence intervals, and residuals). Also, I extended the margins a little bit to allow more space for the data matrix.

*Principle 4 - Escape flatland*    
I used color to display multivariate data (months and type of COVID-19 case).

*Principle 5 - Provide the user with an overview and details*    
The x-/y-axis are labeled appropriate to provide viewers with information to make sense of the graph. Further, I provided a legend describing what each color means. One thing I could have done, but admittedly had difficulty doing, is to provide a red diamond-shaped label in the legend indicating that the red diamond in the graph represents the month average of daily COVID-19 cases.

*Principle 6 - Utilize layering and separation*    
I used color to separate type of COVID-19 case (active vs deaths vs recovered). Also, I provided a particular color and shape to the month average of daily COVID-19 cases.

*Principle 7 - Utilize narratives of space and time*    
As a general benefit of dot plots, the position of a dot on its corresponding dotted horizontal line informs the viewer the space a) between each dot, b) between the dot and 0, and c) between each dot and the maximine value. These anchors provide a clear narrative to the viewer of the daily amounts of COVID-19 cases per month, which is the intention of the data visualization.

*Narrative analysis*    
The line graph illustrates estimated COVID-19 infection rates in TX, with estimated infection rates displayed in the thousands. The data spans from March 2020 to March 2021. The data visualization shows that there is greater uncertainty of the estimated infection rates for the months of December and January, as indicated by the residuals and wider confidence intervals.


amounts of COVID-19 cases -- broken down by month and type of case -- in the USA from October 2020 to March 2021. As can be seen from the visualization, the month of January 2021 saw some of the highest number of daily reported COVID cases, reaching up to 300,000, while the months of October 2020 and March 2021.

## Chord diagram
![6-Chord diagram](https://user-images.githubusercontent.com/44620594/118350642-87165980-b51d-11eb-9544-93a0f1d0514e.png)    
    
*Principle 1 - Maximizing the data-ink ratio*    
Only necessary graphic elements were kept. Perhaps I could have shrunk the outer-most thick layer, which is a solid black, but I felt that making it thick would facilitate matching the inner lines and the questions to which they belong.

*Principle 2 - Mobilize every graphical element to show the data*    
I feel like this type of chart already conforms to this principle, as every data point is unobstructed by graphical elements and clearly distinguishable. I am not sure what I could have done here improve on this principle.

*Principle 3 - Maximize data density and the size of the data matrix*    
Data density is maximized by including varying line thickness to represent thicker or smaller p-values. As for maximizing the size of the data matrix, I feel like this type of chart already conforms to this principle, given that the data matrix makes up most of the visualization. I am not sure what I could have done here improve on this principle.

*Principle 4 - Escape flatland*    
I used color to display multivariate data (months and type of COVID-19 case).

*Principle 5 - Provide the user with an overview and details*    
The x-/y-axis are labeled appropriate to provide viewers with information to make sense of the graph. Further, I provided a legend describing what each color means. One thing I could have done, but admittedly had difficulty doing, is to provide a red diamond-shaped label in the legend indicating that the red diamond in the graph represents the month average of daily COVID-19 cases.

*Principle 6 - Utilize layering and separation*    
I used color to separate type of COVID-19 case (active vs deaths vs recovered). Also, I provided a particular color and shape to the month average of daily COVID-19 cases.

*Principle 7 - Utilize narratives of space and time*    
As a general benefit of dot plots, the position of a dot on its corresponding dotted horizontal line informs the viewer the space a) between each dot, b) between the dot and 0, and c) between each dot and the maximine value. These anchors provide a clear narrative to the viewer of the daily amounts of COVID-19 cases per month, which is the intention of the data visualization.

*Narrative analysis*    
The chord diagram illustrates p-values corresponding to associations between 12 questions in the trauma-informed care tool. Larger lines represent larger p-values, while smaller lines represent smaller p-values. The largest lines are found between Question 1 with Question 4, 5, and 8. This illustration corroborates the weak the associations between these questions which were previously illustrated in the edge bundle chart.

