<h2>🏙️ 15-Minute City Analysis</h2>
<p><b>Accessibility analysis of social housing communities to essential services in Sheffield, United Kingdom.</b></p>

<h3>Introduction</h3>
<p>
The 15-minute city, an urban planning concept also known as ‘chrono-urbanism’, aims to ensure residents can access essential services within a 15-minute walk. This GIS project is commissioned by Urban Retrofit. It investigates how social housing communities in Sheffield adhere to the 15-minute city concept. The study supports Sheffield City Council in promoting sustainability, reducing car dependency, and improving quality of life for lower-income communities while addressing urban inequalities.
</p>

<h3>Methodology and Data</h3>
<p>
Our study combined spatial analysis, census data, and accessibility metrics to evaluate social housing clusters and their proximity to essential services.
</p>

<h4>Defining Social Housing Clusters</h4>
<p>
We used data from the 2021 Census provided by the Office for National Statistics (ONS) to analyse housing tenure types in Sheffield at the LSOA level. After cleaning the data in Python, we identified areas with high levels of social housing by combining two categories: council/local authority rented and other social rented homes.
</p>
<p>
The data was visualised to highlight clusters of social housing, showing areas with the highest concentration of social housing units.
</p>

<h4>Classification of Essential Services</h4>
<p>
Essential services were classified based on their ability to serve basic urban functions. Services were categorised into three tiers based on their importance:
</p>
<ul>
  <li><strong>Tier 3:</strong> Essential for basic community needs</li>
  <li><strong>Tier 2:</strong> Support daily movement and engagement with broader society</li>
  <li><strong>Tier 1:</strong> Improve quality of life</li>
</ul>

<h4>Essential Services by Tier</h4>
<table border="1" cellspacing="0" cellpadding="6">
  <tr>
    <th>Tier 3 (Basic Community Needs)</th>
    <th>Tier 2 (Daily Movement & Engagement)</th>
    <th>Tier 1 (Quality of Life)</th>
  </tr>
  <tr>
    <td>Pharmacies & GPs (Health)<br>Dentists (Health)<br>Health Centres (Health)<br>Primary & Secondary Schools (Education)<br>Places of Worship (Religion)<br>Convenience Food Shops (Food)</td>
    <td>Other Food Shops<br>Public Toilets<br>ATMs<br>Banks<br>Post Office</td>
    <td>Greenspaces<br>Cafés & Restaurants<br>Shopping Centres<br>Leisure Centers<br>Youth Clubs<br>Barbers & Hairdressers</td>
  </tr>
</table>

<h4>Network Analysis</h3>
<p>
The main purpose of our study is to evaluate the accessibility of a 15-minute city for social housing communities. First, we created population-weighted centroids for each social housing community. Then, we used the <strong>Network Analyst Tool</strong>, along with a road network sourced from Ordnance Survey (OS), to conduct our accessibility analysis.
</p>

<h4>Workflow</h4>
<p>The workflow for the accessibility analysis is illustrated below:</p>

<div>
  <img src="path-to-your-network-analysis-image.png" alt="Network Analysis Workflow" width="700">
</div>
