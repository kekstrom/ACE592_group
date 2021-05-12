# ACE592_group 6 README file.

## File Structure: 
**"IA_counties"** : folder containing geo information for Iowa. The files in this folder contain the geometry of Iowa counties and information on their population and voting patterns since the early 2000s connected to each county.

**"Iowa Liquor Sales Data Cleaning.ipynb"**: Read in data for Iowa liqour consumption and basic data cleaning and exporting of cleaned data.

**Iowa Liqour Data Vis.ipynb**: Uses outputted data from liqour consumption (csv files located in this repository) to merge and visualize with voting data relevant to 2016 election. 

**"daily_county_sales.csv"**: date (dy day from 2014-2017), Iowa county, and total liqour sales for that county. This file is produced from the original dataset and outputted from "Iowa Liquor Sales Data Cleaning.ipynb" 

**"daily_county_volume_l"**: date (by day from 2014-2017), Iowa county, and total volume (liters) of liquor sold for that county. This file is produced from the original dataset and outputted from "Iowa Liquor Sales Data Cleaning.ipynb" 

**"MajorCampaignEvents.csv"**: timeline of selected major political events for the 2016 presidential elction with relevant speaking events in Iowa included. Some of these dates used in one graph found in "Iowa Liqour Data Vis.ipynb". 

**"monthly_county_sales.csv"**: date (dy month from 2014-2017), Iowa county, and total liqour sales for that county. This file is produced from the original dataset and outputted from "Iowa Liquor Sales Data Cleaning.ipynb"  

**"monthly_county_volume_l.csv"**: date (by month from 2014-2017), Iowa county, and total volume (liters) of liquor sold for that county. This file is produced from the original dataset and outputted from "Iowa Liquor Sales Data Cleaning.ipynb" 

## Project Summary:
**Authors**: Joe Chang (jwchanguiuc), Kierstin Ekstrom (keskstrom), Gretchen Kuck (gkuck20), Brayden Paur (bpaur), and Joel Tansey (joeltansey). 

**Summary**: This GitHub repository uses data (sources discussed below) on liqours sales in Iowa from 2014-2017 and attempts to see if any there are any trends in liqour consumption for Republican vs Democrat majority Iowan counties around the 2016 election and related events. The broader question that the authors wanted to investigate is: "Does national political elections affect liqour sales?" We attempt to use data from Iowa to answer this question. 

**Data Sources**: 
  Liqour Consumption- Originates from the State of Iowa's Alcoholic Beverages Division. A copy of the data can be found here: https://www.kaggle.com/residentmario/iowa-liquor-sales. The data is not uploaded into this GitHub due to its relatively large size (>3GB). 
  
  Iowa Shape file and voting information: Thank you to maxhully for this dataset (https://github.com/mggg-states/IA-shapefiles). Quoting from their "Sources" section: "The county shapefile comes from the US Census Bureau’s TIGER/Line Shapefiles (https://www.census.gov/cgi-bin/geo/shapefiles/index.php). 2010 Decennial Census demographic data were downloaded from American FactFinder (https://factfinder.census.gov/faces/nav/jsf/pages/index.xhtml). County level election data for presidential elections since 2000 were obtained from the MIT Elections Data and Science Lab (https://electionlab.mit.edu/). The Congressional district shapefile was obtained from the Iowa Legislature (https://www.legis.iowa.gov/legislators/districtMaps).

**Software Used**:This GitHub uses Jupyter notebooks to run Python 3. 
