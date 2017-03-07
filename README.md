# TitanicViz
Visualizing Titanic survival rates by passenger sex, age, and class.

## Summary
This is a visualization of survival rates of passengers aboard the Titanic by class, sex, and age. The dataset includes demographic and passenger information from 891 of the 2,224 passengers and crew aboard the Titanic. The visualization is a series of bar charts that demonstrate the survival rates of male and female passengers by age group. The buttons allow the viewer to see the survival rates for different ticket classes: 1st, 2nd, or 3rd.

## Design
I wanted to allow the viewer to see passenger survival rates as they differed between sex, age group, and class. 

In the first two iterations of the visualization (index_v1.html, index_v2.html), I created the charts showing survival rates by sex among the three classes, with the option to view this chart for certain age groups. 

In response to feedback on the first iteration, in the second iteration (index_v2.html) I created stacked bar charts demonstrating both the survival rate and the death rate; this made clear the one case where there was no data (female, 2nd class, age group 61-80) as opposed to the four cases of 0% survival rates. I also created tooltips to show the actual numbers of individuals in each bar, either survivors or dead, and the total.

I then decided that a different approach better answered my question of: was it women and children first, or did class play a part. In the final iteration of my visualization (index_v3.html), I start with survival rates by sex for each age group, then allow the viewer to click through the class to see how these rates change by the passengers' ticket class. 

I think the third iteration provides a more clear demonstration that women have higher survival rates across all ages. Looking at all classes, women and men have opposite survival patterns in regards to age: as women age their chances of survival increase, while as men age there changes broadly decrease. Viewing the data by class reveals substantial differences in survival between classes -- with first class having higher survival rates across age and sex. Second class passengers had high survival rates for women, but very low for men. In the third class, both men and women had quite low survival rates, excusing the sole woman in the 3rd class, 61-80 age range who's survival resulted in a 100% survival rate.

In response to reviewer feedback, I created the fourth iteration, in which I added brief commentary text on the findings for each of the classes which appeared when the buttons were clicked. 

## Feedback
I collected feedback from five friends on the first iteration of the visualization (index_v1), summarized below. 

*Observations & takeaways:*
- Women have higher survival in all 3 classes. 
- Rich people, women, and old folk had precedence
- Age groups 0-15 and 61-80 have a much different pattern than the overall survival rates
- Cannot differentiate between where the survival rate is zero vs. where there was no data.
 
*Suggestions:*
- Show how many passengers are in each group, percentages can be deceiving. 
- Might the surprising survival rates simply be because of small  sample sizes.
- Show bigger space between classes.

Feedback from the udacity reviewer ont he third iteration of the visualizations (index_v3):
- Correct the tooltips values for 'All' class category.
- Add text to visualization explaining my findings.
- Add more comments throughout the code, remove redundant code, clean/remove debugger and console commands. 

## Resources
Titanic facts
- http://www.titanicfacts.net/titanic-survivors.html
- https://en.wikipedia.org/wiki/RMS_Titanic

Ongoing guidance from Udacity coach!
- https://discussions.udacity.com/t/titanic-bar-chart-d3-js/225077/15

Bar charts
- https://bost.ocks.org/mike/bar/
- https://bost.ocks.org/mike/bar/2/
- https://bost.ocks.org/mike/bar/3/
- https://bl.ocks.org/mbostock/3019563
- grouped-stacked bar chart: http://bl.ocks.org/gencay/4629518
- stacked w/ labels: http://bl.ocks.org/juan-cb/43f10523858abf6053ae
- scale.ordinal vs. scaleBand: http://stackoverflow.com/questions/37548408/d3-4-0-rangeroundbands-equivalent
- example in dimple.js: https://discussions.udacity.com/t/final-project-start/203226/10

CSS:
- http://stackoverflow.com/questions/5703552/css-center-text-horizontal-and-vertical-inside-a-div-block 
- https://www.w3schools.com/css/css_border.asp*/

Margins: 
- https://bl.ocks.org/mbostock/3019563

Axes 
- http://www.d3noob.org/2012/12/adding-axis-labels-to-d3js-graph.html

Html: 
- https://www.w3schools.com/jsref/jsref_slice_array.asp
- Breaks in text: http://stackoverflow.com/questions/13049050/can-you-insert-a-line-break-in-text-when-using-d3-js

Tooltips:
- http://www.d3noob.org/2013/01/adding-tooltips-to-d3js-graph.html
- http://bl.ocks.org/Caged/6476579
- https://discussions.udacity.com/t/problems-with-interaction-of-final-project/181141/22

Adding labels/text to plot
- http://bl.ocks.org/juan-cb/faf62e91e3c70a99a306
- https://github.com/d3/d3/wiki/SVG-Shapes#svg_text

x vs. dx
- http://stackoverflow.com/questions/19127035/what-is-the-difference-between-svgs-x-and-dx-attribute

Colors:
- http://colorbrewer2.org/#type=sequential&scheme=BuGn&n=3
