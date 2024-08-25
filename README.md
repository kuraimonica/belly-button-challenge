# belly-button-challenge
Module 14 Challenge

I completed the following steps
1. Used the D3 library to read in samples.json from the URL https://static.bc-edx.com/data/dla-1-2/m14/lms/starter/samples.json.
2. Created a horizontal bar chart with a dropdown menu to display the top 10 OTUs found in that individual.
   - Used sample_values as the values for the bar chart.
   - Used otu_ids as the labels for the bar chart.
   - Used otu_labels as the hovertext for the chart.
  
3. Created a bubble chart that displays each sample.
   - Used otu_ids for the x values.
   - Used sample_values for the y values.
   - Used sample_values for the marker size.
   - Used otu_ids for the marker colors.
   - Used otu_labels for the text values.
  
 4. Displayed the sample's metadata, i.e., an individual's demographic information.
   - Looped through each key-value pair from the metadata JSON object and create a text string.
   - Appended an html tag with that text to the #sample-metadata panel.

 5. Updated all the plots when a new sample is selected and created a dashboard.

The code is in the static/js folder/
