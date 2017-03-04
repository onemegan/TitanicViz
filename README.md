# TitanicViz
Visualizing Titanic survival rates by passenger class, sex, and age.


## Summary
This is a visualization of survival rates of passengers aboard the Titanic by class, sex, and age. The dataset includes demographic and passenger information from 891 of the 2,224 passengers and crew aboard the Titanic. The visualization is a series of bar charts that demonstrate the survival rates of male and female passengers in 1st, 2nd, and 3rd class. The buttons allow the viewer to see the survival rates for different age groups.

## Design
I wanted to allow the viewer to click between ages to compare the basic bar plot of survival rates by sex and class. In iterating the visualization, I realized it would be helpful to start with a broad view of the survival rates for passengers as a whole by sex and class, so I added the 'All' ages category.

## Feedback
Observations & takeaways:
- Women have higher survival in all 3 classes. 
- Rich people, women, and old folk had precedence
- Age groups 0-15 and 61-80 have a much different pattern than the overall survival rates
 
Suggestions:
- Show how many passengers are in each group, percentages can be deceiving. 
- Might the surprising survival rates simply be because of small  sample sizes.


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


CSS:
- http://stackoverflow.com/questions/5703552/css-center-text-horizontal-and-vertical-inside-a-div-block 
- https://www.w3schools.com/css/css_border.asp*/

Margins: 
- https://bl.ocks.org/mbostock/3019563

Axes 
- http://www.d3noob.org/2012/12/adding-axis-labels-to-d3js-graph.html

Html: 
- https://www.w3schools.com/jsref/jsref_slice_array.asp

Tooltips:
- http://www.d3noob.org/2013/01/adding-tooltips-to-d3js-graph.html
- http://bl.ocks.org/Caged/6476579
- https://discussions.udacity.com/t/problems-with-interaction-of-final-project/181141/22

Adding labels/text to plot
- http://bl.ocks.org/juan-cb/faf62e91e3c70a99a306
- https://github.com/d3/d3/wiki/SVG-Shapes#svg_text

x vs. dx
- http://stackoverflow.com/questions/19127035/what-is-the-difference-between-svgs-x-and-dx-attribute
