
### Team name: BERTLENIKA

<h2 align="center">Collecting data challenge</h2>
<p align="center"><a href="https://github.com/CorentinChanet/challenge-collecting-data">
<img src="https://becode.org/app/uploads/2021/06/logo-becode.png" alt="Logo" width="200" height="200"></a></p>
<h3 align="center"> Web scraping group project at <a href="https://github.com/becodeorg"><strong>BeCode</strong></a></h3><br><br>

Contributors : [Lena](https://github.com/Len-Fid), [Anika](https://github.com/anikaarevalo), [Bertram](https://github.com/BertramDHooge)

## The timeline of the project: 
**28/02/22 - 01/03/22**


## Objectives of the project: 
* Scrape a website containing information about the Belgian house market
* Build a dataset from scratch

## Libraries used:
* Selenium 
* BeautifulSoup
* Pandas 
* JSON

## Usage:
After cloning the repo simply run this as you would any other jupyter notebook. If you want to scrape the data yourself you can run the [main notebook](https://github.com/BertramDHooge/challenge-collecting-data/blob/main/scraping_that_josn.ipynb), or if you just want a visual walkthrough but don't want to have the large time investment required to run the main project you can use the [demo version](https://github.com/BertramDHooge/challenge-collecting-data/blob/main/scraping_that_demo.ipynb), this will do the exact same steps as the main notebook, but has been edited to scrape significantly less data, thus reducing the time required. 


## Walk through of this scraping challenge:
* Locating elements of the source code of the requisite URL from the immoweb.be/en web site
* Extracting targeted elements (links) asynchronously per web get and saving these links by creating a list in a soup file for parsing
* Creating a data frame using pandas for approximately 10,000 inputs
* Saving everything in a CSV file

## Dataset details:
Dataset contains the following columns :

- Locality
- Type of property (House/apartment)
- Subtype of property (Bungalow, Chalet, Mansion, ...)
- Price
- Type of sale (Exclusion of life sales)
- Number of rooms
- Area
- Fully equipped kitchen (Yes/No)
- Furnished (Yes/No)
- Open fire (Yes/No)
- Terrace (Yes/No)
  - If yes: Area
- Garden (Yes/No)
  - If yes: Area
- Surface of the land
- Surface area of the plot of land
- Number of facades
- Swimming pool (Yes/No)
- State of the building (New, to be renovated, ...)
