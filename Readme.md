## Minor Project: Deploying a Machine Learning Pipeline on Cloud
![CRAN/METACRAN](https://img.shields.io/cran/l/devtools?style=for-the-badge) ![Minor Project](https://img.shields.io/badge/Minor%20Project-ML%20on%20Cloud-orange?style=for-the-badge)

---
### Table of Contents
1. [Introduction](#introduction)
2. [Initial Plan](#initial_plan)
3. [The Dataset](#the_dataset)
4. [Pairplot](#pairplot)
5. [Heat Map](#heatmap)
6. [Feature Importance](#feature_importance)
7. [Tableau Dashboard](#tableau_dashboard)
8. [Resources](#resources)

---
### Machine Learning Pipeline on Cloud <a name="introduction"></a>

The aim of this project is to create a Machine Learning Model and deploy it on a Cloud Application and create a Web Application for accessing it through internet. <br> <br>
We will be using a simple dataset of used vehicles for our model and try to predict the price of a vehicle depending values of the features specified by the user/buyer. <br> <br>
<h6> Click <a href = "https://github.com/adityakumaar/ML-Pipeline-On-Cloud/blob/master/ML%20Pipeline%20-%20Used%20Vehicles%20Price%20Prediction.ipynb" target="_blank" rel="noopener noreferrer">here</a> to view the Machine Learning Pipeline. </h6>
<h6> Click <a href="https://minor-1.herokuapp.com/" target="_blank" rel="noopener noreferrer">here</a> to view temporary hosted WebApp. </h6>

---
### Initial Plan: <a name="initial_plan"></a>
<ul>
  <li> - [x] 1. Load the dataset </li>
  <li> - [x] 2. Perform EDA on the dataset </li>
  <li> - [x] 3. Generate Plots and visuals </li>
  <li> - [x] 4. Select a suitable Machine Learning Model </li>
  <li> - [x] 5. Create a Tableau Dashboard </li>
  <li> - [x] 6. Develop a Web App using Flask </li>
  <li> - [ ] 7. Create a single/double webpage site for the Web App </li>
  <li> - [ ] 8. Embed the Dashboard into WebApp </li>
  <li> - [ ] 9. Deploy the project on Heroku </li>
</ul>

---
### The Dataset <a name="the_dataset"></a>
<h6> *a preview of the dataset </h6>
<img src = "https://github.com/adityakumaar/ML-Pipeline-On-Cloud/blob/master/extras/vehicle_dataset_sample.png" />

---
### Pairplot <a name="pairplot"></a>
<img src = "https://github.com/adityakumaar/ML-Pipeline-On-Cloud/blob/master/extras/pairplot.png" />

---
### Heat Map <a name="heatmap"></a>
<img src = "https://github.com/adityakumaar/ML-Pipeline-On-Cloud/blob/master/extras/heatmap.png" />

---
### Feature Importance <a name="feature_importance"></a>
<img src = "https://github.com/adityakumaar/ML-Pipeline-On-Cloud/blob/master/extras/feature_importance.png" />

---
### Tableau Dashboard <a name="tableau_dashboard"></a>
<h6> *You can access the interactive dashboard <a href = "https://public.tableau.com/views/MinorProjectDashboard/Dashboard?:language=en&:display_count=y&:origin=viz_share_link" target="_blank" rel="noopener noreferrer"> here </a> </h6>

<div class='tableauPlaceholder' id='viz1603617479435' style='position: relative'><noscript><a href='#'><img alt=' ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Mi&#47;MinorProjectDashboard&#47;Dashboard&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='MinorProjectDashboard&#47;Dashboard' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Mi&#47;MinorProjectDashboard&#47;Dashboard&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en' /></object></div>                

---
### Resources <a name="resources"></a>
- [x] <a href = "https://www.kaggle.com/adityakumaar/vehicle-price-prediction?select=vehicle_dataset.csv" > Vehicle Dataset </a>
- [x] <a href = "https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestRegressor.html" > Random Forest Regressor </a>
