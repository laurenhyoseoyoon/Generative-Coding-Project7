# A7: Data Visualization

## Your name
Lauren Hyoseo Yoon

## Your Glitch link
[my page](https://laurenhyoseoyoon-a1.glitch.me)


## What data sources are you using? Link the API/Kaggle/etc pages 

Coffee Flavors data from Special Coffee Association
(1) https://sca.coffee/research/coffee-tasters-flavor-wheel
(2) https://github.com/plotly/datasets/blob/master/coffee-flavors.csv


## Describe the format of the data

The data that I used is in csv format, and it consists of three columns: Main IDs of coffee flavor, Specific labels associated with IDs, and Parents (Highest hierarchy of flavors) for IDs 


## How did you pre-process your data, if at all?

- I extracted coffee flavor data into 3 columns so that the sunburst diagram can effectively visualize the hierarchy in concise fashion. 
- When extracting the data, I used comma to differentiate the values corresponding to each column for each row. At last, I generated into a csv file. 
- Most importantly, I had to interpret the data structure and explore ways to illustrate the linkage between the flavors. 


## How are you visualizing the data?

- Sunburst diagram
- A Sunburst Diagram is used to visualize hierarchical data, depicted by concentric circles. The circle in the centre represents the root node, with the hierarchy moving outward from the center. A segment of the inner circle bears a hierarchical relationship to those segments of the outer circle which lie within the angular sweep of the parent segment. (https://datavizproject.com/data-type/sunburst-diagram/)


## What did you notice about this data that you didn't anticipate?

- As a huge fan of coffee, the data was familiar to me. However, there was one aspect that I did not anticipate while visualizing this data in the sunburst diagram. One strength of the sunburst diagram is its interactivity with the user as user can click the specific section of the data that they want to zoom in. I initially thought that this zoom-in effect takes place in every section of the data, yet it was not: Zooming in is not possible in the outermost sections. 


## What do you want the visitor to your page to understand about this data?

- The main aim of this visualization is to understand the hierarchical structure of coffee flavors and how they are associated each other. Furthermore, one of the integral aspects of sunburst diagram is the interactivity with the visitor by clicking to specific section of the diagram. When the visitor clicks a specific flavor section, it zooms into its flavor more in-depth which helps people to better understand the specific flavors that are associated with the flavor-of-interest. 


## List any resources (code, images, etc) you've used, and where you got them from

(1) https://sca.coffee/research/coffee-tasters-flavor-wheel
(2) https://github.com/plotly/datasets/blob/master/coffee-flavors.csv


## List any help you got from classmates or websites, so that you can remember it for later
