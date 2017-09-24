# Make Effective Data Visualization

# Summary

The title of my visualization is "Data Science shows left handed 6 foot tall baseball players are the best!". This has a mostly author driven narrative to conclude that the the best baseball players are 6 feet tall (72 inches) and left handed. Being from the UK I am relatively unfamiliar with the sport of baseball and wanted to be able for myself and others to increase there interest in the sport by connecting at a personal level (we all of a certain physiology to compare against). To this end the user is encouraged to interact with the data to discover more information about each datapoint such as number of Home Runs and player weight.

# Design

## Initial data exploration

### The first step was to investigate the affect of height or weight vs the the batting average or home runs to see if any patterns emerged. As the baseball_data.csv dataset volume is small the initial investigation was done using Excel. Within the Excel environment scatter plots and bubble charts were tested and the handedness was filtered.

From this initial investigation it was concluded that a scatter plot of height vs batting average was a good starting point of a compelling story to address.

NB: It was noticed that the dataset contained some players had a batting average of 0. The players with zero batting average were removed to improve the story telling within the visualization.

## Chart Type
### A scatterplot was selected as the best way to communicate the initial data exploration. It is intentionally taller than it is wide to enable better separation of the denser data points are the centre of the chart. Batting average was chosen to be on the y axis to give more impact of the best values which are higher on the screen. NB: Height on the y axis was explored to enable better separation of the batting values but the story lost a lot of impact.

## Visual Encoding
### The data to be communicated is categorical data of quantitative measures i.e. the handedness of height data vs batting average. Separate colors were used to differentiate each category of handedness (Right, Left & Both). The categorical colors chosen are color blind safe to ensure the 10% of males and 1% of women who are color blind are not disenfranchised. Axis values and labels were chosen to be simple and to not distract from the main data being communicated

## Legend
### A legend was required to enable the user to identify each handness category. A simple legend with minimum text was positioned in the top right corner as this was decided to be the best location that did not distract from the main chart. The circle radius were slightly enlarged in the legend to improve clarification of the categories and also help differentiate the legend points from the main data points.

## Chart evolution

## Visualization version 1

### In the first version of the visualization I made a conscious effort to design it so that it would be friendly for those with color blindness and hence use of color was limited. Hence the only color were applied to the scatter plot were used differentiate the categorical data of the handedness of each player. A light grey was chosen for the background of the tooltip popup to highlight to the user the more detailed data that appears below the scatterplot 

## Visualization version 2

### Feedback from visualization version 1 resulted in increasing the height of the y axis and slightly reducing the circle radius to enable increased spacing of the points in the middle of the chart. Self feedback also resulted in changing the font type from the default font to Verdana.

A quick feedback from the original users was positive

## Visualization version 3

### Feedback from a user in implemented in the latest version by changing the title of the chart to be more like a newspaper headline with complementary formatting (Times New Roman). The main change was adapting the mouseover interaction to enable a tooltip pop up next to the selected data point

# Feedback 

## user 1 - James (feedback on Visualization version 1)
### - chart is explanatory (72" is the best height)
- blending of of color in the centre needs to be denser
- try to be able to differentiate between similar players
- increase size of the chart 

## user 2 - Edna (feedback on Visualization version 1)
### - chart is clear and concise
- best player height is between 70 to 74 inches
- it was a surprise to see that left handed players are generally better (challenged pre-conceptions)
- color merger in the centre could be improved

## user 3 - Jack (feedback on Visualization version 1)
### - batting average looks better for left handed players
- taller people have lower overall performance ("perhaps they should play basketball")
- try to reduce the congestion of data points in the middle of the chart
- try to differentiate the color of right handed and both handed players

# Resources

### Baseball Data -  https://docs.google.com/document/d/1w7KhqotVi5eoKE3I_AZHbsxdr-NmcWsLTIiZrpxWx4w/pub?embedded=true
Color palette - chosen from http://colorbrewer2.org/#
CSS reference - https://www.w3schools.com/cssref/css_websafe_fonts.asp
d3 reference - https://github.com/d3/d3/blob/master/API.md
svg reference - https://developer.mozilla.org/en-US/docs/Web/SVG/Element
html reference - https://www.w3schools.com/tags/default.asp


