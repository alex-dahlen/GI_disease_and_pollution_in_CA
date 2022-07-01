# GI_disease_and_pollution_in_CA
Python code to accompany the paper "Environmental Pollutants are Associated with Irritable Bowel Syndrome in a Cohort of California Residents".

The analysis tested for an association between zip code-level environmental pollution and the incidence of various GI diseases in California, which were obtained from the Optum Clinformatics dataset.  

This code goes through several steps:
1) Read in census data at the census tract level
2) Roll it up to the zip code level
3) Exploratory analysis of how census data, GI disease, and Optum sampling are related
4) Regression analysis to test the association between GI disease and pollution, adjusting for census data and for Optum's sampling bias.
5) Sensitivity analyses.

Optum data is unfortunately private so it cannot be shared.  I am sharing the code for transparency and for other researchers who want to do geospatial models with census data.
