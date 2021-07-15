# Belly-Button-Biodiversity-Dashboard
## Overview
The goal of this project is to visualize belly button microbial data. To identify a vaiable alternative source of beef, improbable beef has decided to gather data from volunteers and determine whether their belly button could be the potential source of bacteria species that can be synthesized to make beef alternative. 

Improbable beef has gathered demographic and belly button data from 153 volunteers. We will use this data to create visualization that will help easily identify people that may have bacteria that can be used to synthesize beef. At the end of the analysis, we will produce a bar chart that visualises the top 10 bacterial species found in the belly buttons of the volunteers, a bubble chart that emphasises bacterial species with the highest concentration per individual, and a gauge chart that displays belly washing frequency per week for each volunteer. If Improbable Beef identifies a bacterial species as a candidate to manufacture synthetic beef, our Visualization will help to identify whether that species is found in the navel of anyone of the volunteers.

### Control Flow
1.  Create a folder structure to hold the index.html file, and the JavaScript files
2.  create a basic HTML page to view the belly button JSON data
3.  Load and inspect the belly button JSON data using the JavaScript, and Web browser's console log
4.  Create an event listener to check for changes in the volunteer ID
5.  The HTML page will have the following layout
      - The HTML page will hold a dropdown panel for the volunteer ID and their corresponding demographic data
      - two columns that will hold a horizontal bar chart and a gauge chart
      - a row to dsiplay a bubble chart
6.  Create a JavaScript to read the JSON data     
      - The JavaScript will contain a function that creates a horizontal bar chart to display the top 10 bacterial species (OTUs) when an individual’s ID is selected from the dropdown menu on the webpage. The horizontal bar chart will display the sample_values as the values, the otu_ids as the labels, and the otu_labels as the hover text for the bars on the chart.
      - Another block of code in the function will create a bubble chart that will display the following when an individual’s ID is selected from the dropdown menu webpage:
            - The otu_ids as the x-axis values.
            - The sample_values as the y-axis values.
            - The sample_values as the marker size.
            - The otu_ids as the marker colors.
            - The otu_labels as the hover-text values. 
7.  The final part of the function will a gauge chart that displays the weekly washing frequency's value, and display the value as a measure from 0-10 on the progress bar in the gauge chart when an individual ID is selected from the dropdown menu.

### Results
Horizontal Bar Chart and Gauge Chart

![Horizontal_Bar_Chart](https://user-images.githubusercontent.com/67847583/125715296-1601304c-1f35-44f9-91f2-b22f110e48e1.png)

Gauge Chart

![Gauge_Chart](https://user-images.githubusercontent.com/67847583/125715302-07b0500e-fb82-481f-af11-6fcdf499d5cf.png)



Bubble Chart
![Bubble_Chart](https://user-images.githubusercontent.com/67847583/125714843-03f74d67-1c74-457f-ab4f-7e5721bd09d4.png)


Belly_Button_Biodiversity_Dashboard
![Belly_Button_Biodiversity_Dashboard](https://user-images.githubusercontent.com/67847583/125714893-ffe32cc1-5e29-4bcb-9031-412ab1f67bc3.png)
