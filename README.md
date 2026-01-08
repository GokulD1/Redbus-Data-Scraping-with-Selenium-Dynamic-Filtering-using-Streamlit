🚌 **Redbus Data Scraping with Selenium & Dynamic Filtering using Streamlit**
**1. Overview**

The Redbus Data Scraping and Visualization Project aims to revolutionize transportation data analysis by automating the extraction, storage, and visualization of bus travel information.
Using Selenium Web Scraping, the project collects real-time bus details from the Redbus website, including routes, timings, prices, seat availability, bus types, and operators.

The scraped data is stored in a structured SQL database, and an interactive Streamlit application is developed to allow users to dynamically filter and analyze the data.
This solution enables data-driven decision-making, improving operational efficiency and strategic planning in the transportation industry.

**2. Objectives**

Automate data collection from the Redbus website using Selenium

Scrape minimum 10 Government State Transport Corporations (GSTC)

Include private bus operators for selected routes

Store scraped data in a structured SQL database

Develop an interactive Streamlit dashboard for filtering and visualization

Provide insights into pricing, availability, and route performance

**3. Business Use Cases**

Passenger Decision Support – Compare prices, timings, and availability

Operational Planning – Optimize routes and schedules

Competitive Analysis – Compare government vs private operators

Revenue Optimization – Analyze pricing trends

Market Intelligence – Identify high-demand routes

**4. Skills & Technologies Used**
Skills

Web Scraping & Automation

Data Cleaning & Transformation

SQL Database Management

Data Filtering & Visualization

Streamlit Application Development

Technologies

Python

Selenium

Pandas & NumPy

MySQL / SQLite

Streamlit

**5. Data Source**

Website: Redbus
Data Type: Dynamic web content
Scraping Method: Selenium WebDriver

Data Collected

Bus Name

Bus Type (AC / Non-AC / Sleeper / Seater)

Operator Type (Government / Private)

Route

Departure Time

Arrival Time

Duration

Ticket Price

Seat Availability

Ratings

**6. Data Scraping Methodology**
Selenium Automation Steps

Launch browser using Selenium WebDriver

Navigate to Redbus website

Select state transport corporation

Load dynamic content using waits and scrolling

Extract bus details using XPath / CSS selectors

Repeat process for:

Minimum 10 Government Bus Transport Corporations

Private buses for the same routes

Example Government Operators Scraped

TNSTC

KSRTC

APSRTC

MSRTC

TSRTC

KSRTC (Kerala)

RSRTC

OSRTC

UPSRTC

HRTC

**7. Data Storage (SQL Database)**
Database Design

Table Name: bus_routes

Column Name	Description
id	Unique ID
state	State name
route	Source → Destination
bus_name	Bus operator name
bus_type	AC / Non-AC / Sleeper
operator_type	Government / Private
departure_time	Departure time
arrival_time	Arrival time
duration	Travel duration
price	Ticket cost
seats_available	Available seats
rating	User rating
Benefits

Structured data storage

Fast querying and filtering

Scalable for future expansion

**8. Data Cleaning & Processing**

Removed duplicate bus entries

Converted prices and seat counts to numeric values

Standardized time formats

Handled missing ratings and seat availability

**9. Streamlit Application**
Application Features
User Filters

State selection

Route selection

Operator type (Government / Private)

Bus type

Price range

Seat availability

Rating filter

**Outputs**

Filtered bus results table

Price comparison views

Availability insights

Advantages

User-friendly interface

Real-time filtering

Quick decision-making

**10. Results**
Deliverables
Component	Description
Selenium Scraper	Automated data extraction
SQL Database	Structured bus data
Streamlit App	Interactive filtering dashboard
Clean Dataset	Analysis-ready data
Key Outcomes

Successfully scraped data from 10+ Government Transport Corporations

Integrated private bus data for comparison

Built a scalable data pipeline

Enabled efficient travel analysis

**11. Conclusion**

This project successfully demonstrates how web scraping, database storage, and interactive visualization can be combined to create a powerful transportation analytics solution.
The integration of Selenium, SQL, and Streamlit provides a scalable and efficient system for real-time travel data analysis.

**12. Future Enhancements**

Real-time scraping scheduler

Integration with Google Maps

Fare prediction using ML

Booking trend analysis

Cloud deployment
