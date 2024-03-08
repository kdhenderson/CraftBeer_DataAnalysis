# CraftBeer_DataAnalysis
Data Analysis of Craft Beers and Breweries in the US - A Case Study

## Purpose

This is a data analysis of craft beers and breweries in the United States, all 50 states plus Washington, DC. The study has three main objectives, to evaluate the number of craft breweries in each state, to provide summary statistics of craft beer metrics, and to investigate statistical relationships between these metrics. We aim to provide useful insight into the craft beer industry of value to executives of Budweiser.
* **Analysis team:** Willis Jones and Kristin Henderson
* **Stakeholders:** Budweiser CEO and CFO


## Repository structure

### Root directory

* `README.md`: Readme file detailing purpose, contents and usage.
* `Analysis_BeersAndBreweries.Rmd`: Rmarkdown file with introduction, questions to be addressed, all code to interact with the data and build the plots, written explanations, and conclusion.
* `Analysis_BeersAndBreweries.html`: HTML file knitted with the above and with embedded data and visualizations.
* `Presentation_Final_Analysis.ppt`: Powerpoint slides for our final statistical analysis with link to seven-minute YouTube video team presentation.
* `Presentation_Initial_EDA.ppt`: Powerpoint slides for our initial EDA presentation.

### Data directory containing the two data files.

##### Codebook:

* `Beers.csv`: a dataset of US craft beers with 2410 observations of 7 variables.
  -	Name: Name of the beer.
  -	Beer_ID: Unique identifier of the beer.
  -	ABV: Alcohol by volume of the beer.
  -	IBU: International Bitterness Units of the beer.
  -	Brewery_ID: Brewery id associated with the beer.
  -	Style: Style of the beer.
  -	Ounces: Ounces of beer.
	
* `Breweries.csv`: a dataset of US breweries with 558 observations of 4 variables.
  -	Brew_ID: Unique identifier of the brewery.
  -	Name: Name of the brewery.
  -	City: City where the brewery is located.
  -	State: U.S. State where the brewery is located.

In the code, these two datasets are imported and merged into a dataframe called `bbDF` by the unique identifier of the brewery, Brew_ID. `bbDF` includes all variables and observations from both datasets.


## Usage

* Clone this repository
`git clone https://github.com/kdhenderson/CraftBeer_DataAnalysis.git`
* The files were created with RStudio version 2023.12.0+369.
* All required libraries are listed and loaded in the Rmarkdown file in one of the first code chunks.
