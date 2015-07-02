# DataVisualization_project2

This repository hosts a visualization created for the "Data Visualization and D3.js" Udacity class. 
The project consisted in finding an example of bad data visualization and then proposing a better solution
to visualize these data. I chose the data visualization in the "badViz.png" file. It shows the 
average time Americans spent per daily activity in 2004 and 2014 for 14 categories of activities.
There are several issues with this visualization:
- The body shape adds noise to it and keeps from having a good understanding of the data
- This format makes it hard to spot the changes in values between 2004 and 2014
- It also makes it hard to spot the most time-consuming activities

In order to solve these issues, I propose the visualization previewed in file "thumbnail.png" (I followed the
procedure in: https://gist.github.com/mbostock/6466603 to create this thumbnail). It is a dynamic 
visualization which Dimple.js code cand be found in file "index.html". The dataset is in file "data.csv". 
I propose to visualize this dataset with a slope graph combined to a bubble chart to show the difference
of values between 2004 and 2014 and the percentage of a day each activity takes.
