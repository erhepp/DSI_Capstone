# DSI Capstone and Projects

## Exploring Earthquake Magnitude and Intensity Relationships with Data Science

Returning to my roots as a geophysicist, I explored the relationship between earthquake intensity and factors such as magnitude, magnitude computation method, distance, depth and crustal thickness and density properties. Scientists at Lawrence Livermore National Labs have released a crustal model at 1 degree (both latitude and longitude) intervals, and I wanted to incorporate this information into intensity models.  Details can be found in theses blog posts on the Exploratory Data Analysis of US earthquakes from 1970 to 2017,  

**Retrieve USGS ComCat Data ->** https://erhepp.github.io/Get-USGS-ComCat-Data/  
**CRUST 1.0 Model ->**  https://erhepp.github.io/Crust1.0-Data/  
**EDA ->** https://erhepp.github.io/Earthquake-Data-Exploratory-Data-Analysis/   

Intensity, or the expression / damage level of the earthquake on the surface, is traditionally reported as a Modified Mercalli Intensity (MMI) rating, 0 - 12. In the last 20 years, a new method, using crowd sourced internet reported effects and damage estimates, was established by the USGS.  

This project first compared the crowdsourced intensity values, known as "community decimal intensity (CDI), with the MMI, and found that CDI typically evaluates an earthquake's intensity slightly lower than MMI, but that with the inclusion of additional factors of region and depth, and using the number of CDI reports per quake as a quality measure, that CDI can be reasonably used in place of MMI. This is fortunate, as it is cheap and easy to collect, and therefore CDI estimates exist for 3-4 times the earthquakes that have professionally assigned MMI measurements.  

**Comparison of CDI to MMI ->** https://erhepp.github.io/Earthquake-Intensity-Comparison-of-MMI-and-CDI/


With this new source of additional intensity measurement, the relationship of intensity to distance from an earthquake's origin was examined. The addition of crustal features, i.e. thickness and density of crustal layers, to traditional factors of distance and depth, resulted in a model with closer correspondence of predicted to observed intensity. The new model explained twice the variance, about 45%, over the original model (of about 20%).

**Exploration of Intensity with Distance ->**  Notebook to be published soon

Planned work will utilize the crustal parameters at both the observation points as well as the earthquake origin, and will attempt more advanced techniques to access the validity and accuracy of each intensity observation in order to improve understanding of the magnitude, distance, intensity relationships.
Clicking this link will display a page with additional description links to the various parts of this and other projects.
</br>
</br>

**Presentations**  

Below are two presentations I prepared for use when explaining this project, one for audiences not experienced in data science, and a second for technical audiences:

Non-Technical -> https://github.com/erhepp/DSI_Capstone/blob/master/Capstone_NonTechnicalFinal.pdf  
Technical -> https://github.com/erhepp/DSI_Capstone/blob/master/Capstone_TechnicalFinal.pdf

</br>
</br>

## PROJECT: What makes a TV show successful?
This analysis and model attemts to determine the factors that influence high or low IMDb ratings for TV shows. https://erhepp.github.io/tv-show-analysis/
