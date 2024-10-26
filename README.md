# DuRP_Sediment_Fluxes
This repository contains data collected at the USDA-ARS Jornada Experimental Range (JER) Duneland Restoration Project (DuRP) and National Wind Erosion Research Network (NWERN) site and used in the DuRP Sediment Fluxes project.

# Authors

Nicholas P. Webb1, Brandi Wheeler1, Brandon L. Edwards1, Jeremy W. Schallner2, Neeshia Macanowicz3, Justin W. Van Zee1, Ericha M. Courtright1, Brad Cooper1, Sarah E. McCord1, Dawn Browning1, Saroj Dhital1, Kristina E. Young1, Brandon T. Bestelmeyer1

1 USDA-ARS Jornada Experimental Range, Las Cruces, NM, USA
2 Bureau of Land Management, Las Cruces District Office, Las Cruces, NM, USA
3 Department of Biology, New Mexico State University, Las Cruces, NM, USA

# Created

2015-2024

# Purpose

This repository contains data used by Webb et al. in their analysis for "Magnitude shifts in aeolian sediment transport associated with degradation and restoration thresholds in drylands", submitted for publication in JGR Biogeosciences.

# Data

Measurements were collected during the period May 2015 to May 2024 at the DuRP and NWERN sites on the Jornada Experimental Range in south-central New Mexico, USA. 

Meteorological data were measured at the NWERN site with a centrally-located 10 m meteorological tower equipped with cup anemometers at 0.5 m, 1.0 m, 1.5 m, 2.5 m, and 5.0 m above ground level (AGL) , and one RM Young 3002 cup anemometer with a wind vane mounted at 10 m AGL to measure the vertical wind speed profile. A Campbell Scientific EE181 model air temperature/relative humidity probe was mounted at 4.0 m AGL and temperature sensors (model 107-L) were mounted at 2.0 m and 10 m AGL. A tipping bucket rain gauge (TE525) was mounted at 1.5 m AGL approximately 4 m to the northwest of the central tower. The southern 3 m tower was equipped with an RM Young 3002 cup anemometer and wind vane mounted at 3.0 m. Data were sampled at 1 Hz and were logged every 1 min on Campbell Scientific CR1000 data loggers.

Horizontal sediment mass flux was measured using 9 (DuRP) or 27 (NWERN) Modified Wilson and Cooke (MWAC) sediment samplers (Webb et al., 2019). The 9 or 27 freely rotating masts, each with four MWAC samplers (0.1, 0.25, 0.5 and 0.85 m above ground level) were located across the sites using a stratified random sample design. A regular 3 x 3 grid provided strata and one (DuRP) or three (NWERN) MWAC masts with samplers were randomly located in each grid cell.

Transect data were collected on three parallel 30 m (DuRP) or 100 m (NWERN) transects spaced 60 degrees apart (from 0 degrees) with the transects passing through the center of the site at the meteorological tower. Methods of Herrick et al. (2018) were used to measure vegetation height, the size distribution of canopy gaps >=5 cm (unvegetated spaces between plant canopies), and foliar cover of vegetation by species and soil surface properties.

# Data files include:

1.	metdata_precip.zip - These files contain raw meteorological data for each year through 2024.
2.	metdata_wind.csv - This file contains calculated wind shear velocity, aerodynamic roughness length, and normalized shear velocity data.
3.	DuRP_NWERN_coremethods_data.csv - This file contains indicators of vegetation foliar cover by plant functional group calculated from vegetation transect data collected for each measurement event.
4.	DuRP_NWERN_integrated_fluxes_season.csv - This file contains vertically-integrated horizontal sediment mass fluxes calculated from Modified Wilson and Cooke (MWAC) data for each collection period (2015-2021).

The following lists provide field definitions for the meteorological, core indicators, and horizontal sediment mass flux data.

# metdata_precip.zip

•	TIMESTAMP - Month/Day/Year (MM/DD/YYYY) and time (HH:MM) of observation.

•	RECORD - Unique record number for each data point.

•	Switch - Switch 12V status (boolean) for triggering a collection.

•	AvgTemp_10M_DegC - Average temperature (Deg C) at 10 meters from base of tower.

•	AvgTemp_4M_DegC - Average temperature (Deg C) at 4 meters from base of tower.

•	AvgTemp_2M_DegC - Average temperature (Deg C) at 2 meters from base of tower.

•	AvgRH_4m_perc - Average relative humidity (percentage) at 4 meters from base of tower.

•	Total_Rain_mm - Total rain (milimeters) at 1.5 meters above ground.

•	WindDir_deg - Wind direction (degrees) at 10 meters from base of tower.

•	MaxWS6_10M_m_s - Maximum wind speed (meters/second) at 10 meters from base of tower.

•	MaxWS5_5M_m_s - Maximum wind speed (meters/second) at 5 meters from base of tower.

•	MaxWS4_2.5M_m_s - Maximum wind speed (meters/second) at 2.5 meters from base of tower.

•	MaxWS3_1.5M_m_s - Maximum wind speed (meters/second) at 1.5 meters from base of tower.

•	MaxWS2_1M_m_s - Maximum wind speed (meters/second) at 1 meter from base of tower.

•	MaxWS1_0.5M_m_s - Maximum wind speed (meters/second) at 0.5 meter from base of tower.

•	StdDevWS2_1M_m_s - Wind speed (meters/second) standard deviation at 1 meter from base of tower.

•	AvgWS6_10M_m_s - Average wind speed (meters/second) at 10 meters from base of tower.

•	AvgWS5_5M_m_s - Average wind speed (meters/second) at 5 meters from base of tower.

•	AvgWS4_2.5M_m_s - Average wind speed (meters/second) at 2.5 meters from base of tower.

•	AvgWS3_1.5M_m_s - Average wind speed (meters/second) at 1.5 meters from base of tower.

•	AvgWS2_1M_m_s - Average wind speed (meters/second) at 1 meter from base of tower.

•	AvgWS1_0.5M_m_s - Average wind speed (meters/second) at 0.5 meter from base of tower.

•	Sensit_Tot - Total number of particle counts within a logging interval (1 min) 5 cm above soil surface.

•	SenSec - Number of seconds within a logging interval (1 min) that particles were counted.

# metdata_wind.csv 
•	t	- timestamp for record.

•	u_10 – Wind speed (m/s) at 10 m above ground level (AGL).

•	dir - Wind direction (degrees) at 10 m AGL.

•	u_star - Wind shear velocity (m/s) obtained from Law of the Wall.

•	z_0 - Aerodynamic roughness length (m) obtained from Law of the Wall.

•	u_star_u_h - Normalized shear velocity = u_star / u_10

•	year - Year of sample collection.

•	date - Date of sample collection: mm/dd/yyyy

•	MMDD - Month and day of sample collection.

•	monthofyear - Month in which sample was collected.

•	day - Day of month in which sample was collected

•	season - Seaon of year in which sample was collected. Spring (MAM), summer (JJA), fall (SON), winter (DJF).

# DuRP_NWERN_coremethods_data.csv

•	EstablishDate	- The date the plot was established.

•	Datum	Zone – The datum of the plot location longitude and latitude.

•	Longitude_NAD83 - The longitude of the plot location in the NAD83 Datum.

•	Latitude_NAD83 - The latitude of the plot location in the NAD83 Datum.

•	PrimaryKey - Unique identifier for each plot-visit.

•	ProjectKey - Unique identifier for the study stie or plot.

•	AH_AnnForbCover - The cover of forbs in the plot. This indicator is derived from the Line Point Intercept method.

•	AH_AnnForbGrassCover - The cover of annual forbs and grasses in the plot. This indicator is derived from the Line Point Intercept method.

•	AH_AnnGrassCover - The cover of annual grasses in the plot. This indicator is derived from the Line Point Intercept method.

•	AH_ForbCover	 - The cover of forbs in the plot. This indicator is derived from the Line Point Intercept method.

•	AH_ForbGrassCover - The cover of forbs and grasses in the plot. This indicator is derived from the Line Point Intercept method.

•	AH_GrassCover - The cover of grasses in the plot. This indicator is derived from the Line Point Intercept method.

•	AH_HerbLitterCover - The cover of herbaceous plants and litter in the plot. This indicator is derived from the Line Point Intercept method.

•	AH_PerenForbCover - The cover of perennial forbs in the plot. This indicator is derived from the Line Point Intercept method.

•	AH_PerenForbGrassCover - The cover of perennial forbs and grasses in the plot. This indicator is derived from the Line Point Intercept method.

•	AH_PerenGrassCover	- The cover of perennial grasses in the plot. This indicator is derived from the Line Point Intercept method.

•	AH_PerenShrubCover	- The cover of perennial shrubs in the plot. This indicator is derived from the Line Point Intercept method.

•	AH_PerenSubShrubCover - The cover of perennial sub-shrubs in the plot. This indicator is derived from the Line Point Intercept method.

•	AH_PerenSucculentCover - The cover of perennial succulents in the plot. This indicator is derived from the Line Point Intercept method.

•	AH_PerenWoodyCover - The cover of perennial woody plants in the plot. This indicator is derived from the Line Point Intercept method.

•	AH_ShrubCover - The cover of shrubs in the plot. This indicator is derived from the Line Point Intercept method.

•	AH_SubShrubCover - The cover of sub-shrubs in the plot. This indicator is derived from the Line Point Intercept method.

•	AH_SucculentCover - The cover of succulents in the plot. This indicator is derived from the Line Point Intercept method.

•	AH_TotalLitterCover - The cover of litter in the plot. This indicator is derived from the Line Point Intercept method.

•	AH_WoodyCover - The cover of woody plants in the plot. This indicator is derived from the Line Point Intercept method.

•	AH_WoodyLitterCover - The cover of woody litter in the plot. This indicator is derived from the Line Point Intercept method.

•	BareSoilCover	- The basal cover of soil in the plot, not including soil that has cover above it. This indicator is derived from the Line Point Intercept method.

•	TotalFoliarCover - The foliar cover of plants in the plot. This indicator is derived from the Line Point Intercept method.

•	GapCover_25_50 - The percentage of the plot's soil surface covered by gaps between plant canopies that are from 25-50 cm in size. This indicator is measured using the Gap 
Intercept method (commonly three transects per plot).

•	GapCover_51_100 - The percentage of the plot's soil surface covered by gaps between plant canopies that are from 51-100 cm in size. This indicator is measured using the 
Gap Intercept method (commonly three transects per plot).

•	GapCover_101_200 - The percentage of the plot's soil surface covered by gaps between plant canopies that are from 101-200 cm in size. This indicator is measured using the 
Gap Intercept method (commonly three transects per plot).

•	GapCover_200_plus - The percentage of the plot's soil surface covered by gaps between plant canopies that are greater than 200 cm in size. This indicator is measured 
using the Gap Intercept method (commonly three transects per plot).

•	GapCover_25_plus - The percentage of the plot's soil surface covered by gaps between plant canopies that are greater than 25 cm in size. This indicator is measured using 
the Gap Intercept method (commonly three transects per plot).

•	Mean_Max_Hgt - The average height (cm) on the macroplot of the tallest plant part measured at each height pin drop interval. If both woody and herbaceous heights are measured, the tallest measurement is considered. Calculated from data collected using the height method.


# DuRP_NWERN_integrated_fluxes_season.csv

•	X - row ID

•	Flux – Vertically-integrated horizontal sediment mass flux (units g/m/d).

•	Site - Study site name; GRASS = GSH, BOER = HGR, DUNE = SHR, MESIN = SHI.

•	Date – Sediment sample collection date (DD-Mon-YY).

•	MMDD - Month and day of sample collection.

•	group_date - Season and year in which sample was collected.

•	year - Year in which sample was collected.

•	monthofyear - Month of year in which sample was collected.

•	dayofyear - Julian day of year in which sample was collected.

•	day - Day of year in which sample was collected

•	Primarykey - Unique identifier of data used in the Landscape Data Commons - https://landscapedatacommons.org 

# References

Herrick, J.E., Van Zee, J.W., McCord, S.E., Courtright, E.M., Karl, J.W., & Burkett, L.M. (2018), Monitoring Manual for Grassland, Shrubland, and Savanna Ecosystems, Volume 1: Core Methods, Second EditionRep., USDA-ARS Jornada Experimental Range, Las Cruces, New Mexico.

Webb, N. P., Herrick, J. E., Van Zee, J. W., Courtright, E. M., Hugenholtz, C. H., Zobeck, T. M., et al. (2016), The National Wind Erosion Research Network: Building a standardized long‐term data resource for aeolian research, modeling and land management. Aeolian Research, (22), 23–36.

Webb, N., Chappell, A., Edwards, B., McCord, S., Zee, J., Cooper, B., Courtright, E., Duniway, M., Sharratt, B., Tedela, N., Toledo, D. (2019), Reducing Sampling Uncertainty in Aeolian Research to Improve Change Detection. Journal of Geophysical Research: Earth Surface, (124).  doi: 10.1029/2019JF005042, 2019.


