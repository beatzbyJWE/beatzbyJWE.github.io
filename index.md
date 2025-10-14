---
layout: default
---

<style>
  :root {
    /* Copper Aquamarine Dream Palette */
    --primary-color: #6C739C;
    --secondary-color: #424658;
    --accent-color: #C56B62;
    --accent-light: #D9A69F;
    --warm-copper: #DEA785;
    --soft-pink: #F0DAD5;
    --light-gray: #BFB9B5;
    --sage-green: #BABBB1;
    --text-color: #424658;
    --light-bg: #F0DAD5;
    --card-shadow: 0 4px 6px -1px rgba(66, 70, 88, 0.1), 0 2px 4px -1px rgba(66, 70, 88, 0.06);
    --hover-shadow: 0 10px 15px -3px rgba(66, 70, 88, 0.15), 0 4px 6px -2px rgba(66, 70, 88, 0.08);
  }

  body {
    max-width: 1200px;
    margin: 0 auto;
    padding: 2rem 4rem;
    background-color: #FDFBFA;
  }

  .hero {
    background: linear-gradient(135deg, var(--primary-color) 0%, var(--secondary-color) 100%);
    color: white;
    padding: 3rem 2rem;
    border-radius: 12px;
    margin-bottom: 3rem;
    text-align: center;
  }

  .hero h1 {
    font-size: 2.5rem;
    margin-bottom: 1rem;
    font-weight: 700;
  }

  .hero p {
    font-size: 1.125rem;
    opacity: 0.95;
    max-width: 800px;
    margin: 0 auto;
    line-height: 1.6;
  }

  .section {
    margin-bottom: 4rem;
  }

  .section-title {
    font-size: 2rem;
    font-weight: 700;
    color: var(--text-color);
    margin-bottom: 0.5rem;
    padding-bottom: 0.75rem;
    border-bottom: 3px solid var(--primary-color);
    display: inline-block;
  }

  .section-subtitle {
    font-size: 1.5rem;
    font-weight: 600;
    color: var(--primary-color);
    margin-top: 2.5rem;
    margin-bottom: 1.25rem;
  }

  .project-card {
    background: white;
    border-radius: 8px;
    padding: 1.5rem;
    margin-bottom: 1.5rem;
    box-shadow: var(--card-shadow);
    transition: all 0.3s ease;
    border-left: 4px solid var(--accent-color);
  }

  .project-card:hover {
    box-shadow: var(--hover-shadow);
    transform: translateY(-2px);
    border-left-color: var(--warm-copper);
  }

  .project-card h3 {
    margin-top: 0;
    margin-bottom: 0.75rem;
    font-size: 1.25rem;
    font-weight: 600;
  }

  .project-card h3 a {
    color: var(--primary-color);
    text-decoration: none;
    transition: color 0.2s ease;
  }

  .project-card h3 a:hover {
    color: var(--accent-color);
    text-decoration: underline;
  }

  .project-card h4 {
    color: var(--primary-color);
    margin-top: 0;
    margin-bottom: 0.75rem;
  }

  .project-card p {
    color: #5a5e6b;
    line-height: 1.6;
    margin-bottom: 1rem;
  }

  .project-card ul {
    margin: 1rem 0;
    padding-left: 1.5rem;
  }

  .project-card li {
    color: #5a5e6b;
    line-height: 1.8;
    margin-bottom: 0.5rem;
  }

  .project-card ol {
    margin: 1rem 0;
    padding-left: 1.5rem;
  }

  .project-card ol li {
    color: #5a5e6b;
    line-height: 1.8;
    margin-bottom: 0.5rem;
  }

  .project-links {
    list-style: none;
    padding-left: 0;
  }

  .project-links li {
    margin-bottom: 0.5rem;
  }

  .project-links a {
    color: var(--primary-color);
    text-decoration: none;
    font-weight: 500;
    transition: color 0.2s ease;
  }

  .project-links a:hover {
    color: var(--accent-color);
    text-decoration: underline;
  }

  .project-image {
    width: 100%;
    max-width: 600px;
    border-radius: 8px;
    box-shadow: var(--card-shadow);
    margin: 1rem 0;
  }

  .map-container {
    background: white;
    border-radius: 8px;
    padding: 1.5rem;
    margin: 1.5rem 0;
    box-shadow: var(--card-shadow);
  }

  .map-container iframe {
    width: 100%;
    height: 600px;
    border: none;
    border-radius: 8px;
  }

  .featured-badge {
    display: inline-block;
    background: linear-gradient(135deg, var(--warm-copper) 0%, var(--accent-color) 100%);
    color: white;
    padding: 0.25rem 0.75rem;
    border-radius: 12px;
    font-size: 0.75rem;
    font-weight: 600;
    margin-left: 0.5rem;
    text-transform: uppercase;
    letter-spacing: 0.05em;
  }

  .divider {
    height: 2px;
    background: linear-gradient(90deg, var(--primary-color) 0%, var(--light-bg) 100%);
    margin: 3rem 0;
  }

  .external-link {
    color: var(--primary-color);
    text-decoration: none;
    font-weight: 500;
    transition: color 0.2s ease;
  }

  .external-link:hover {
    color: var(--accent-color);
    text-decoration: underline;
  }

  @media (max-width: 768px) {
    body {
      padding: 1rem 1.5rem;
    }

    .hero h1 {
      font-size: 2rem;
    }

    .section-title {
      font-size: 1.5rem;
    }

    .project-card {
      padding: 1rem;
    }

    .map-container {
      padding: 1rem;
    }

    .map-container iframe {
      height: 400px;
    }
  }
</style>

<div class="hero">
  <h1>Data Science Portfolio</h1>
  <p>Showcasing my work in data science, machine learning, and analytics across professional and academic projects. This portfolio demonstrates practical applications of advanced analytics, geospatial visualization, and data-driven decision making.</p>
</div>

<div class="section">
  <h2 class="section-title">Professional Work</h2>

  <h3 class="section-subtitle">FTA Safety Analysis & Visualization <span class="featured-badge">Featured</span></h3>

  <div class="project-card">
    <p>I've developed a comprehensive suite of tools for analyzing and visualizing Federal Transit Administration (FTA) safety data. This work demonstrates geospatial analysis, interactive visualization, and data-driven insights for public transit safety to aid policy makers.</p>

    <p>For example, I developed an analysis to help answer business questions about trends in New York City. While I can't share the real example, here is an overview of what I did in a new file:</p>
    <ul>
      <li>Data cleaning and preprocessing of FTA safety datasets</li>
      <li>Statistical analysis of incident patterns and trends</li>
      <li>Identification of high-risk areas and incident types</li>
    </ul>

    <p><a href="/fta_safety_analysis.py" class="external-link">View FTA Safety Analysis Code →</a></p>
  </div>

  <div class="project-card">
    <h4>General Map with Heat Map Option</h4>
    <p>A general map with a heat map option where you can toggle on and off the types of deadly events occurring from 2014-present.</p>
  </div>

  <div class="map-container">
    <iframe src="/fta_nyc_fatal_incidents_map.html" title="NYC Fatal Incidents Map"></iframe>
  </div>

  <div class="project-card">
    <h4>Interactive Time-Slider Visualization <span class="featured-badge">Interactive</span></h4>
    <p>The next iteration is a more interactive time-slider visualization of transit safety incidents in New York City containing:</p>
    <ul>
      <li>Temporal analysis with time-slider functionality (note the increase in severe events beginning in 2020 and escalating in following years)</li>
      <li>Geospatial mapping of incidents across NYC's transit modes</li>
    </ul>
  </div>

  <div class="map-container">
    <iframe src="/fta_nyc_time_slider_map.html" title="NYC Time Slider Map"></iframe>
  </div>

  <div class="project-card">
    <p>I used the data collected through the NTD that my team helped to validate and publish to DOT's open data portal <a href="https://data.transportation.gov/Public-Transit/Major-Safety-Events/9ivb-8ae9" class="external-link" target="_blank">here</a>. I asked Claude for some help with finding the deadliest events in New York City. The resulting code is here:</p>
    <ul class="project-links">
      <li><a href="/fta_nyc_basemap.py">→ NYC Base Map Generation</a> - Creating foundational map</li>
      <li><a href="/fta_nyc_time_slider_map.py">→ Time Slider Map Script</a> - How I got the temporal visualization</li>
      <li><a href="/fta_deadly_events_map.py">→ Deadly Events Mapping</a> - Focused analysis of fatal incidents</li>
    </ul>
  </div>

  <h3 class="section-subtitle">NLP for Data Validation</h3>

  <div class="project-card">
    <h4><a href="/NLP%20wPublic%20Transit%20Data.ipynb">Using NLP to Validate Data</a></h4>
    <p>In my job I manage a team that handles data validation. Here is an exercise that I did on public data as a proof of concept for a data validation technique. The goal was to:</p>
    <ol>
      <li>Locate and extract "year" from long text "notes"</li>
      <li>Compare this year to another value in the same record</li>
      <li>Discuss accuracy of the results</li>
    </ol>
  </div>

  <div class="project-card">
    <h4><a href="/machinelearnjoe/Data%20Wrangling%20Practice.htm">Treating Structured Data as Unstructured to Learn about Data Quality</a></h4>
    <p>An innovative approach to understanding data quality by applying unsupervised learning techniques:</p>
    <ul>
      <li>Use k-means clustering to group data with a known structure</li>
      <li>Use neural networks to do the same thing</li>
    </ul>
  </div>
</div>

<div class="divider"></div>

<div class="section">
  <h2 class="section-title">UVA Data Science Program</h2>
  <p>Here are a few of the things I am most proud of working on during my time enrolled at the University of Virginia School of Data Science.</p>

  <div class="project-card">
    <h3><a href="/machinelearnjoe/Kmeans_tomatoes.ipynb">Movie Recommender System Using IMDB Dataset</a></h3>
    <p>A team and I used a variety of techniques to predict movie scores. This is some of the work from that project where we were using kmeans clustering to explore whether there were organic clusters between models when certain features were and weren't included. It was a way to use supervised learning for data exploration before moving onto learning with unlabeled data.</p>
  </div>

  <div class="project-card">
    <h3><a href="/machinelearnjoe/Disaster%20Relief%20Project.htm">Haiti Relief Project</a></h3>
    <p>In this project I will:</p>
    <ul>
      <li>Show how data science could have augmented the provision of life-saving relief after the 2010 Haiti Earthquake</li>
      <li>Compare traditional classification techniques with machine learning methods for solving a color-based classification problem</li>
      <li>Iterate through a simple cost/benefit analysis method where a tailored "F-Score" balances precision and recall during classification</li>
      <li>Wrangle and combine large datasets</li>
      <li>Output a color palette based on RGB data</li>
      <li>Map Lat-Long data using mapview package</li>
    </ul>
    <img src="images/Screen Shot 2020-12-31 at 4.53.33 PM.png?raw=true" alt="Haiti Relief Project Visualization" class="project-image"/>
  </div>

  <div class="project-card">
    <h3><a href="/PC%20%26%20Hierarchical%20Cluster.htm">Principal Components and Hierarchical Clustering</a></h3>
    <p>In this exercise are solutions for classwork related to hierarchical clustering and establishing variance explained by principal components starting by creating loading vectors from the original data. A colleague demonstrated the math to do so and I coded it in R.</p>
  </div>
</div>

<div class="divider"></div>

<div class="section">
  <h2 class="section-title">Personal Data Science Work</h2>

  <div class="project-card">
    <h3><a href="/DataWrangling_Practice.html">Simple Data Wrangling Practice</a></h3>
    <p>I completed this exercise early into my excursion in data science because it provides a great R crash course in:</p>
    <ul>
      <li>Dealing with formatting and incorrect or undesirable data types</li>
      <li>Handling NAs and understanding outliers</li>
      <li>Organizing a data file</li>
    </ul>
  </div>

  <div class="project-card">
    <h3><a href="/pdf/sample_presentation.pdf">NFL 2021 Big Data Bowl</a></h3>
    <p>Analysis and insights from the NFL's Big Data Bowl competition.</p>
  </div>
</div>
