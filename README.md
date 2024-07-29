Analysis of Jeep Cars from Cars24
This project involves the extraction, cleaning, analysis, and visualization of data for used Jeep cars available in Mumbai on the Cars24 website. The main goal is to provide insights into the pricing, age, and usage of these cars.

Table of Contents
Introduction
Data Extraction
Data Cleaning
Analysis
Visualizations
Insights
Requirements
How to Run
Contributors
Introduction
This project focuses on analyzing used Jeep cars listed on the Cars24 website. The analysis includes data extraction using web scraping, data cleaning, and various statistical analyses and visualizations to gain insights into the car market in Mumbai.

Data Extraction
Data was gathered from the Cars24 website using web scraping techniques. The following data points were extracted for used Jeep cars available in Mumbai:

Car Name (object)
Year of Manufacture (int64)
Kilometers Driven (in km) (int32)
Fuel Type (object)
Transmission (object)
Price (in Lakhs) (float64)
Data Cleaning
The extracted data underwent cleaning to ensure accuracy and usability:

Removal of unwanted text and characters.
Conversion of data types to appropriate formats (e.g., integers for Year of Manufacture, floats for Price).
Storage of cleaned data in a CSV file for further analysis.
Analysis
Descriptive statistics provide a summary of key metrics in the dataset. The following analyses were performed:

Distribution plots for Year of Manufacture, Kilometers Driven, and Price.
Box plots to compare prices by Fuel Type and Transmission.
Correlation analysis to examine relationships between variables such as Kilometers Driven, Year of Manufacture, and Price.
Visualizations
Several plots were created to visualize the data:

Distribution Plots: To show the spread and frequency of Year of Manufacture, Kilometers Driven, and Price.
Box Plots: To compare prices based on Fuel Type (Petrol vs. Diesel) and Transmission (Manual vs. Automatic).
Correlation Matrix: To visualize relationships between key variables.
Insights
Key findings from the analysis include:

The average price of the cars is around 12.28 lakhs.
The dataset contains cars mainly from the years 2017 to 2021.
Diesel cars have a different price distribution compared to petrol cars.
Automatic and manual transmission cars also show different price distributions.
The correlation matrix shows significant relationships between kilometers driven, year of manufacture, and price.
Requirements
Python 3.x
Libraries: pandas, numpy, matplotlib, seaborn, requests, BeautifulSoup4
How to Run
Clone the repository:
bash
Copy code
git clone https://github.com/yourusername/jeep-cars-analysis.git
cd jeep-cars-analysis
Install the required libraries:
Copy code
pip install -r requirements.txt
Run the data extraction script:
Copy code
python data_extraction.py
Run the data cleaning script:
Copy code
python data_cleaning.py
Run the analysis and visualization script:
Copy code
python analysis_visualization.py
