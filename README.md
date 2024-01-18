# Challenge-14

# Belly-button-challenge.

## Background:

In this assignment, we will build an interactive dashboard to explore the Belly Button Biodiversity datasetLinks to an external site., which catalogues the microbes that colonise human navels.The dataset reveals that a small handful of microbial species (also called operational taxonomic units, or OTUs, in the study) were present in more than 70% of people, while the rest were relatively rare.

### Data source:
URL https://2u-data-curriculum-team.s3.amazonaws.com/dataviz-classroom/v1.1/14-Interactive-Web-Visualizations/02-Homework/samples.json.


 
## Project : 
 Task divided into steps:

1.Use the D3 library to read in samples.json from the URL

https://2u-data-curriculum-team.s3.amazonaws.com/dataviz-classroom/v1.1/14-Interactive-Web-Visualizations/02-Homework/samples.json.


2.Create a horizontal bar chart with a dropdown menu to display the top 10 OTUs found in that individual.

   Use sample_values as the values for the bar chart.

   Use otu_ids as the labels for the bar chart.

   Use otu_labels as the hovertext for the chart.

  ## Bar chart:
![newplot (3)](https://github.com/svuth23/belly-button-challenge/assets/136966712/1eec4283-de1c-45b6-8313-0582b960612f)


3. Create a bubble chart that displays each sample.
   Use otu_ids for the x values.

   Use sample_values for the y values.

   Use sample_values for the marker size.

   Use otu_ids for the marker colors.

   Use otu_labels for the text values.

  ## Bubble Chart:

  ![newplot (5)](https://github.com/svuth23/belly-button-challenge/assets/136966712/b77e33a1-04f6-4b93-9f2e-a72024c5f8a9)


  4. Display the sample metadata, i.e., an individual's demographic information.

  5. Display each key-value pair from the metadata JSON object somewhere on the page.

  ![image](https://github.com/svuth23/belly-button-challenge/assets/136966712/6fcab907-a9c7-445b-837c-ab31115c6037)




   6. create Gauge chart

   # Gauge chart 
   
     ![newplot (4)](https://github.com/svuth23/belly-button-challenge/assets/136966712/99de81a4-c888-41c3-b981-2f053b1a3b6e)


The related data Updates all the plots when a new sample is selected and website page is: 

## https://svuth23.github.io/belly-button-challenge/



### external useful links :

https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css
 
https://plot.ly/javascript/gauge-charts/

https://d3js.org/d3.v7.min.js

https://cdn.plot.ly/plotly-latest.min.js
