# Summary 
This repository (for UCSB's Environmental Data Science Geospatial Analysis class) I am investigating the suitabiilty of different mollusks (Geoducks and Oysters) for aquaculture development off the American west coast. The information housed in this repository demonstrates skills of raster manipulation, map algebra, data visualization and the development and usage of generalizable workflows and functions

If a bug is spotted-shoot me an email (maeveli@ucsb.edu) and we can figure out together what's going on. Include the code ran, the error message recieved, and a screenshot of what you're working with. I'd appreciate it if you didn't contribute to this! Its my work for a class and a record of my process for research.

I am the primary author this assignment, it was developed in tandem with Caitlin Nordheim-Maestras and Lauren Puffer. The assignment was developed by Ruth Oliver

# Description

In this assignment I am using sea surface temperature (SST) and bathymetry data to caluclate the suitablle habitat in each of the maritime law designated exclusive economic zones in the Western coast of the united states for two different marine species of aquaculture interest, geoducks and oysters. I first mask temperature and depth data to regions taht are suitable for ech species, pulling data from SeaLifeBase about the species temperature and depth range. Then I calcualte within each zone the volume suitable area for the species, and compare across zones. Finally I visualize it in a map which is delineated in four regions, Washington coast, Oregon coast, and the Northern, Centeral and Southern Californian coast. I develop the workflow step by step and then build it into a single function which can be applied to any marine species to contextualize the viability of this species on the western coast. This can be used by scholars and policymakers to analyze the suitability of aquaculture on the North American West Coast. 


# Data Access
Sea Life base can be accessed here: https://www.sealifebase.ca/search.php

Temperature data can be accessed here: https://coralreefwatch.noaa.gov/product/5km/index_5km_ssta.php

Depth data can be accessed here: https://www.gebco.net/data-products/gridded-bathymetry-data#area

EEZ data can be accessed here: Marineregions.org

# data citations

Bathymetry

GEBCO Compilation Group (2022) GEBCO_2022 Grid (doi:10.5285/e0f0bb80-ab44-2739-e053-6c86abc0289c).

EEZ

Flanders Marine Institute (2025): MarineRegions.org. Available online at www.marineregions.org. Consulted on 2025-11-25.

SeaLifeBase

Palomares, M.L.D. and D. Pauly. Editors. 2025. SeaLifeBase. World Wide Web electronic publication. www.sealifebase.org, version (04/2025).

SST

NOAA Coral Reef Watch. NOAA Coral Reef Watch Version 3.1 Daily 5km Satellite Regional Virtual Station Time Series Data for West Coast of USA, 2008 - 2012r. College Park, Maryland, USA: NOAA Coral Reef Watch. Data set accessed at https://coralreefwatch.noaa.gov/product/vs/data.php.
