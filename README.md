# A data-driven investigation into bias within stop and search practices of the police forces of England and Wales
The code provided here generates an data-driven investigation into stop and search rates. Following extraction from the police.uk API, tt utilizes SQL to manage the data in a relational database. It uses R, particularly the tidyverse ecosystem, to process, transform and visualize the data for in-depth investigation. In particular, I generate multi-level geographic mappings of police data using GeoJSON files integrated using specified R packages. The final report is uploaded as an html. 

For clarity, the aim of the paper was to apply a data science investigation to the following research question: “In the United Kingdom, a police officer has powers to stop and search any individual if the officer has ‘reasonable grounds’ to suspect the individual is carrying certain items or, under some other conditions, if a senior police officer has granted approval (see here for details). Are there biases in who experiences stop and search by the police?”

## Directory
- Data folder - Contains all raw data collected from police.uk API, gov.uk and census 2021 sources, as well as GeoJSON geographic shapefiles
- MY472_Final_for_Submission - Final Rmarkdown document to reproduce my findings and figures
