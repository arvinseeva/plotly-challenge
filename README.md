# plotly-challenge
Homework on using plotly

The main objective of this assignment was to explore the belly button diversity dataset which catalogues the microbes that colonise the human navel. 

The first task is to read the samples.json file. 

The next step is to create a horizontal bar chart with dropdown menu to display the top 10 OTUs. 

Part of this exercise included : 
- Use sample_values as the values for the bar chart.
- Use otu_ids as the labels for the bar chart.
- Use otu_labels as the hovertext for the chart.


Following this task, the next task was to build a bubble chart that displays each sample.
This involved the following : 
- Use otu_ids for the x values.
- Use sample_values for the marker size.
- Use otu_ids for the marker colors.
- Use otu_labels for the text values.


The task was then to display the sample metadata, i.e., an individual's demographic information.

This also involved to display each key-value pair from the metadata JSON object somewhere on the page.

Finally, the task was to update all of the plots any time that a new sample is selected.

For the additional task, we were asked to adapt the Gauge Chart from https://plot.ly/javascript/gauge-charts/ to plot the weekly washing frequency of the individual.

