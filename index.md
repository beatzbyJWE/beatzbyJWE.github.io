# Portfolio

In my portfolio I provide some of my work in data science across my professional and academic careers. I will be adding to this regularly as I continue to learn about and adopt the principles of data science.

## Work

### FTA Safety Analysis & Visualization

I've developed a comprehensive suite of tools for analyzing and visualizing Federal Transit Administration (FTA) safety data. This work demonstrates geospatial analysis, interactive visualization, and data-driven insights for public transit safety to aid policy makers.

For example, I developed an analysis to help answer business questions about trends in New York City. While I can't share the real example, here is an overview of what I did in a new file:
<ul>
  <li>Data cleaning and preprocessing of FTA safety datasets</li>
  <li>Statistical analysis of incident patterns and trends</li>
  <li>Identification of high-risk areas and incident types</li>
</ul>

[FTA Safety Analysis](/fta_safety_analysis.py)

One result is a general map with a heat map option where you can toggle on and off the types of deadly events occurring from 2014-present. 

<iframe src="/fta_nyc_fatal_incidents_map.html" width="800" height="600" style="border:none;"></iframe>

The next iteration is a more  interactive time-slider visualization of transit safety incidents in New York City containing:
<ul>
  <li>Temporal analysis with time-slider functionality (note the increase in severe events beginning in 2020 and escalating in following years)</li>
  <li>Geospatial mapping of incidents across NYC's transit modes</li>
</ul>

<iframe src="/fta_nyc_time_slider_map.html" width="800" height="600" style="border:none;"></iframe>

I used the data collected through the NTD that my team helped to validate and publish to DOT's open data portal [here](https://data.transportation.gov/Public-Transit/Major-Safety-Events/9ivb-8ae9). I asked Claude for some help with finding the deadliest events in New York City. The resulting code is here:
- [NYC Base Map Generation](/fta_nyc_basemap.py) - Creating foundational map
- [Time Slider Map Script](/fta_nyc_time_slider_map.py) - How I got the temporal visualization
- [Deadly Events Mapping](/fta_deadly_events_map.py) - Focused analysis of fatal incidents

## UVA Data Science Program

Here are a few of the things I am most proud of working on during my time enrolled at the University of Virginia School of Data Science.

Movie Recommender System Using IMDB Dataset
[Movie Recommender System Project](/machinelearnjoe/Kmeans_tomatoes.ipynb)
A team and I used a variet of techniques to predict movie scores. This is some of the work from that project where we were using kmeans clustering to explore whether there were organic clusters between models when certain features were and weren't included. It was a way to used supervised learning for data exploration before moving onto learning with unlabeled data.

[Haiti Relief Project](/machinelearnjoe/Disaster%20Relief%20Project.htm)

In this project I will:
<ul>
  <li>Show how data science could have augmented the provision of life-saving relief after the 2010 Haiti Earthquake.</li>
  <li>Compare traditional classification techniques with machine learning methods for solving a color-based classification problem.</li>
   <li>Iterate through a simple cost/benefit analysis method where a tailored "F-Score" balances precision and recall during classification.</li>
  <li>Wrangle and combine large datasets. </li>
  <li>Output a color palette based on RGB data.</li>
  <li>Map Lat-Long data using mapview package.</li>
</ul>

<img src="images/Screen Shot 2020-12-31 at 4.53.33 PM.png?raw=true"/>

[Principal Components and Hierarchical Clustering](/PC%20%26%20Hierarchical%20Cluster.htm)

In this exercise are solutions for classwork related to hierarchical clustering and establishing variance explained by principal components starting by creating loading vectors from the original data. A colleague demonstrated the math to do so and I coded it in R.

[Connecting to APIs Using Json] (

---

## Personal Data Science Work

[Simple Data Wrangling Practice](/DataWrangling_Practice.html)

I completed this exercise early into my excursion in data science because it provides a great R crash course in:
<ul>
  <li>Dealing with formatting and incorrect or undesirable data types.</li>
  <li>Handling NAs and understanding outliers.</li>
  <li>Organizing a data file.</li>
</ul>

[NFL 2021 Big Data Bowl](/pdf/sample_presentation.pdf)

---
### NLP for Data Validation

[Using NLP to Validate Data](/NLP%20wPublic%20Transit%20Data.ipynb)

In my job I manage a team that handles data validation. Here is an exercise that I did on on public data as a proof of concept for a data validation technique. The goal was to:
<ol>
  <li>Locate and extract "year" from long text "notes".</li>
  <li>Compare this year to another value in the same record.</li>
  <li>Discuss accuracy of the results.</li>
</ol>

[Treating Structured Data as Unstructured to Learn about Data Quality](/machinelearnjoe/Data%Wrangling%Practice.htm)

In this project I will:
<li>Use k-means clustering to group data with a known structure</li>
<li>Use neural networks to do the same thing. </li>
