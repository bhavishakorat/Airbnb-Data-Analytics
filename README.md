Airbnb Data Analysis | Python & Power BI
This project is my end-to-end analysis of Airbnb listing data. I used Python in Google Colab to clean and explore the data, then created a Power BI dashboard to present the information visually.

The main goal was to understand how Airbnb listings differ by price, room type, neighbourhood and review activity.
What I wanted to explore
- How are listing prices distributed?
- Which room types appear most often in the dataset?
- Which neighbourhood groups have the most listings?
- How do prices vary between room types?
- How does review activity change over time?
Tools I used
- Python – data preparation and analysis
- Google Colab – writing and running the notebook
- Pandas – working with the dataset
- Matplotlib and Seaborn – creating charts
- Power BI – building the dashboard
Project process
1. Getting familiar with the data
I started by loading the Airbnb CSV file into Pandas. I checked the columns, data types, missing values and general structure to understand what information was available.
2. Cleaning the data
In the notebook, I worked on the following preparation steps:
- Converted last review into a date format.
- Filled missing reviews per month values with 0.
- Filled missing last review values using the earliest available date in that column.
- Removed rows where the listing name or host name was missing.
- Removed the license and house_rules columns from the analysis.
- Cleaned the price and service fee columns by removing currency symbols and converting the values to numbers.
- Removed duplicate rows.
3. Exploring the data with Python
I used charts to look at a few parts of the Airbnb market:
What I explored	Chart
Listing price distribution	Histogram with KDE
Number of listings by room type	Count plot
Listings across neighbourhood groups	Count plot
Price differences between room types	Box plot
Review activity over time	Line chart


What I noticed
These are the main patterns described in my notebook:
- Room types: Entire homes/apartments and private rooms are the most common listing types in the dataset. Shared rooms and hotel rooms appear less often.
- Neighbourhood groups: Manhattan and Brooklyn have more listings than the other neighbourhood groups shown.
- Prices and room types: Shared rooms generally have lower prices. Prices for private rooms, entire homes/apartments and hotel rooms vary more.
- Reviews over time: Review activity changes from month to month, with some noticeable increases and decreases.
- Prices overall: Listings cover a wide range of prices.
These observations describe the dataset I analysed. They do not explain why a particular pattern occurred.
Power BI dashboard
I also created a Power BI dashboard to present the Airbnb analysis in a visual format.



To explore the report, download the .pbix file and open it in Power BI Desktop. If Power BI asks for the source data, select the Airbnb CSV file and refresh the report.
Project files
Airbnb-Data-Analytics/
│
├── Dataset/
│   └── compressed_data.csv.gz
│
├── Python-Analysis/
│   └── Airbnb_project.ipynb
│
├── PowerBI-Dashboard/
│   └── Airbnb_dashboardpowerBi.pbix
│
├── Screenshots/
│   └── Airbnb_Dashboard.pdf
│
└── README.md



A note about the data
The findings in this project are based on the dataset available to me when I completed the analysis. Airbnb listings, prices and availability can change, so the results should be read as an analysis of this dataset rather than a picture of the live Airbnb market.
About me
Bhavisha Korat

B.Sc. IT (FinTech) Student

GitHub Profile
