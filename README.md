# Cars24.com Scraper

This repository contains a Selenium web scraper for extracting data from cars24.com, a popular online platform for buying and selling used cars. The scraper retrieves information about different types of used Cars such as sedans, SUVs, hatchbacks, luxury SUVs, and luxury sedans. The extracted data includes details like car name, distance already travelled, year bought, number of previous owners, RTO location, transmission type, car type, type of fuel used, and price.

## Prerequisites

To run the scraper, ensure you have the following dependencies installed:

- Python 
- Selenium WebDriver
- Chrome or Firefox web browser
- Pandas library

You can download the Chrome driver from the following link https://chromedriver.storage.googleapis.com/index.html . Please download the version that matches your browser version. You can check the Browser version of Chrome using chrome//version


## Configure the WebDriver:

   - Download the appropriate WebDriver for your browser (Chrome or Firefox) and be compatible with your operating system.
   - Update the `webdriver_path` variable in the scraper script (`Cars24_scrapper.ipynb`) with the path to your WebDriver executable.



The scraper will extract data from cars24.com and save it to a CSV file. I first scrapped data for all types of cars separately like for hatchbacks, sedans, SUV etc and then used concat to combine them. I also performed some cleaning operations on the scrapped data.

## Scraped Data

The scraped data consists of approximately 8015 rows and 9 columns, including the following information:

1. Car Name: The name or model of the car.
2. Distance: The distance already travelled by the car.
3. Year Bought: The year when the car was purchased.
4. Previous Owners: The number of previous owners of the car.
5. RTO Location: The location of the Regional Transport Office.
6. Transmission: The type of transmission (automatic or manual).
7. Car Type: The type of car (sedan, SUV, hatchback, luxury SUV, luxury sedan).
8. Fuel: The fuel used (petrol, diesel, CNG, etc.).
9. Price: The price of the car.





