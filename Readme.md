# Groundwater Storage Change

    Groundwater is the main source for drinking and irrigation applications, so it is significantly important to manage groundwater resources. Hence analyzing groundwater storage changes (GWSC) is essential to develop groundwater models and forecast trends. The groundwater levels keep on decreasing and the major freshwater source for drinking and irrigation. Monitoring the groundwater storage trend is essential so that it will be used in sustainable way.


# Scope and Objective of the Study

To study the Groundwater storage change and analyze its trend for twenty years in Cauvery River basin 

    1.	Estimate GWS using parameters required namely surface runoff, surface moisture, plant canopy water.
    2.  Assess the total water thickness for the area of study.
    3.	Developing a groundwater storage model for Cauvery basin.
    4.	Estimate the spatiotemporal groundwater storage change in Cauvery River basin using GRACE satellite data.
    5.	Comparing the GRACE-derived groundwater storage change with rainfall data.

# Study Area Description

    The Cauvery basin rises on Brahmagiri Hill of the Western Ghats in southwestern Karnataka state, flows in a southeasterly direction for 475 miles (765 km) through the states of Karnataka and Tamil Nadu, and descends the Eastern Ghats in a series of great falls. Before emptying into the Bay of Bengal south of Cuddalore, Tamil Nadu, the river breaks into a large number of distributaries forming a wide delta called the “Garden of Southern India".The study area extends over states of Tamil Nadu, Karnataka, Kerala and Union Territory of Puducherry draining an area of 81,155 Sq.km which is nearly 2.7% of the total geographical area of the country with a maximum length and width of about 560 km and 245 km.

    The basin is mainly influenced by South-West monsoon in Karnataka & Kerala and North-East monsoon in Tamil Nadu. Most of the parts of Tamil Nadu receive rainfall from the North-East Monsoon. Rainfall in the delta area is of the order of 1000 mm annually. In the coastal areas the highest rainfall months are October, November and December, while further inland the peak monthly rainfall is early October. While the South-West monsoon supply is copious and dependable, the North-East monsoon supply is irregular and subject to frequent failure 

# Data used

    TOTAL WATER THICKNESS(TWS)

		The HRB CSR and JPL data (19× 19) have some time irregularities for the period of study from 2003 to 2022. One of the pros of GRACE satellite data is its complete spatial and temporal data over a large area provision. Also, despite its low resolution, it has the advantage of recording changes in total TWS water storage. The total water thickness is measured in kg per sq meter.

    SOIL MOISTURE

		Soil moisture is downloaded from GLDAS for the period of study from 2003 to 2022. One of the pros of GRACE satellite data is its complete spatial and temporal data over a large area provision. Also, despite its low resolution, it has the advantage of recording changes in soil moisture. The soil moisture is measured in cm.

    SURFACE RUN-OFF 

		Surface run-off is downloaded from GLDAS for the period of study from 2003 to 2022. One of the pros of GRACE satellite data is its complete spatial and temporal data over a large area provision. Also, despite its low resolution, it has the advantage of recording changes in surface run-off. The soil moisture is measured in cm

	PLANT CANOPY WATER

		Plant canopy water is downloaded from GLDAS for the period of study from 2003 to 2022. One of the pros of GRACE satellite data is its complete spatial and temporal data over a large area provision. Also, despite its low resolution, it has the advantage of recording changes in surface run-off. The plant water canopy is measured in cm.

# Data Conversion

    NetCDF (network Common Data Form) is a file format designed to support the creation, access, and sharing of scientific data. It is used extensively in the atmospheric and oceanographic communities to store variables, such as temperature, pressure, wind speed, and wave height.

	Panoply is a software designed by NASA for desktop image processing. Panoply is a cross-platform application that plots geo-gridded arrays from NetCDF, HDF and GRIB datasets. It can be used for both raster and vector files with both optical and radar file formats. The netCDF file is read using panoply which contains the parameters of Groundwater storage. The parameters selected by the study area taken can be exported to .txt, .csv, .cdl formats. The attributes from the location of the study are extracted and it is converted into .csv which is used for mapping and further time series.

# Software Used

	Arc GIS

		ArcGIS Desktop is a foundational piece for GIS professionals to create, analyze, manage, and share geographic information so decision-makers can make intelligent, informed decisions. It allows you to create maps, perform spatial analysis, and manage data. You can import multiple data formats and use powerful analytical tools and workflows to identify spatial patterns, trends, and non-obvious relationships. ArcGIS is built around a geodatabase, which uses an object–relational database approach for storing spatial data. Geodatabases in ArcGIS can be stored in three different ways namely File geodatabase, Personal geodatabase, Enterprise geodatabase (formerly known as an SDE or ArcSDE) geodatabase  

	Q GIS

		QGIS is a Geographic Information System (GIS) software referred as Quantum GIS (QGIS). The software was first developed by a team of geoscientists in Germany. Subsequently, it has been made an Open-source community software. It has been designed for an easy and effective implementation of spatial algorithms through easily approachable user interface with many visualization options. It runs under Windows and Linux operating systems. Its Graphical-User-Interface (GUI) allows the user to manage and visualize data as well as to perform data analyses and manipulations by executing modules. Besides menu, tool and status bars, which are typical for the majority of modern programs, QGIS interfaces the user with three additional control elements. Loaded module libraries are listed in the module’s workspace together with a list of their modules. 
		Similarly created map views will be listed in the map’s workspace and data objects in the data workspace, hierarchically sorted by their data type. Dependent on which object in a workspace is selected, the object properties control shows an object-specific set of sub-windows. Common to all objects are sub-windows for settings and descriptions. In case a module is selected, the settings window is populated with the module parameters. Here the user can choose data sets and other options for the module execution.

	MS-Excel

	    Microsoft Excel has the basic features of all spreadsheets, using a grid of cells arranged in numbered rows and letter-named columns to organize data manipulations like arithmetic operations. It has a battery of supplied functions to answer statistical, engineering and financial needs. In addition, it can display data as line graphs, histograms and charts with a very limited three-dimensional graphical display. Spreadsheet applications such as MS Excel use a collection of cells arranged into rows and columns to organize and manipulate data. They can also display data as charts, histograms and line graphs. MS Excel permits users to arrange data to view various factors from different perspectives.

# Groundwater Storage Map 

    The .csv file obtained for monthly data is added as XY data and the z-data had given as monthly GWS in ArcGIS. The country's basin shape file has been obtained from WRIS and masking was done in QGIS. The XY data is exported as a .shp file and it was subjected to projection to fix the data points in the study area. The final map for monthly Groundwater storage is obtained by IDW method. The GWS map had been created for the months January, March, May, July, September, November, December from 2003 to 2022. Post to this Trend analysis for these years and correlating with rainfall data is followed.

# Results and Discussion

    The study reveals that the main source of groundwater recharge is precipitation. In the years 2006, 2011, 2017 the precipitation in the Cauvery River basin is considerably less but the graph shows the increasing trend of groundwater storage change since the upper Cauvery regions are situated at higher elevations than lower and middle river basins. So, the precipitation in upper regions results in water flow thus, influencing the trend in the above-mentioned years.

    The average difference in groundwater thickness from 2022 to 2003 is in the order of 26.179 cm yr-1 which shows increase in groundwater compared to the conditions in 2003. Even though, study reveals the reality of an average groundwater decline of 5.877 cm per year across the Cauvery River basin from 2003 to 2022. The maximum depletion rate was observed during 2019 (-16.979 cm) while the minimum was observed during 2002 (12.55cm) has been inferred 
