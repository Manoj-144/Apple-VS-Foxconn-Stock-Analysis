# Apple vs Foxconn Stock Analysis

This project examines the stock performance of **Apple Inc.** and **Foxconn**, focusing on the impact of Apple product releases on both companies' stocks. Given that Foxconn is a major manufacturer for Apple, the study explores how the release of key Apple products correlates with stock price movements and trading volumes. An interactive Tableau dashboard was created to present the analysis results in a dynamic and user-friendly format.

## Project Overview

The project is centered around collecting product names and release dates using web scraping and analyzing stock price movements for Apple and Foxconn. The analysis focuses on periods surrounding the release of certain Apple products, instead of a fixed time period, to understand the stock performance before and after these events.

## Why Compare Apple and Foxconn?

Foxconn, being Apple's primary manufacturer for products like iPhones, plays a crucial role in Apple's supply chain. This close relationship allows for a unique opportunity to compare the stock behavior of both companies and analyze how Apple product launches influence Foxconn's stock performance as well. The project aims to highlight the interconnectedness of the two companies in the stock market.

## Libraries and Tools Used

### Data Collection
- **Web Scraping**:
  - **BeautifulSoup**: Used for scraping product names and release dates from relevant web pages.
  - **Requests**: Facilitated the web scraping by fetching HTML content from the web.
  
- **API for Stock Data**:
  - **yfinance**: Collected historical stock data for both Apple and Foxconn.

### Data Cleaning and Analysis
- **Pandas**: 
  - Used for data manipulation, cleaning, and organization.
  - Dataframes were created to store and process stock data for analysis.
  
- **NumPy**: 
  - Used for efficient numerical operations and data preprocessing tasks.
  
### Data Visualization
- **Matplotlib**:
  - Used to create various charts and plots for analyzing price percent changes and stock volumes.
  
- **Seaborn**:
  - Enhanced the visual quality of the graphs and aided in producing detailed visualizations such as histograms and line charts.

### Dashboard Creation
- **Tableau**: 
  - An interactive dashboard was built using Tableau to visualize the stock analysis in a dynamic way. The dashboard allows users to explore data related to Apple and Foxconn stocks through various filters and charts.

## Steps for Data Collection

1. **Web Scraping**:
   - I used BeautifulSoup and Requests to scrape product release dates and names from the web. The scraped data was compiled into a structured format for further analysis.
   
2. **APIs for Stock Data**:
   - The yfinance library was utilized to fetch historical stock data for both Apple and Foxconn. This included data points such as closing prices, volume, and percentage changes in stock prices.

3. **Data Cleaning**:
   - Using Pandas, I handled missing data, removed outliers, and ensured the datasets for both companies were aligned for comparative analysis. NumPy was used for some numerical operations during the preprocessing steps.

## Analysis Performed

1. **Product-Based Stock Analysis**:
   - The stock data for both Apple and Foxconn was analyzed in relation to specific Apple product releases. Price fluctuations and trading volume were examined to identify the impact of these launches on the market.

2. **Price and Volume Correlation**:
   - By calculating daily percentage changes in price and comparing stock volumes, I explored the correlation between stock performance and trading volume, especially around product launch periods.

3. **Comparative Analysis**:
   - Key financial metrics such as daily closing prices, percentage changes, and trading volumes were compared between Apple and Foxconn to determine how their stock behaviors diverged or aligned over time.

## Key Findings from the Analysis

1. **Impact of Apple Product Launches**:
   - The release of major Apple products significantly affected Apple's stock price and volume. Foxconn, although less directly impacted, also experienced spikes in trading volume, reflecting the manufacturing role it plays.

2. **Apple Stock Performance**:
   - Apple's stock closed at **$191.80** on the last analyzed date, reflecting a **-0.54%** price drop, with a substantial volume increase of over **85.78 million units**, indicating high market activity.

3. **Foxconn Stock Performance**:
   - Foxconn’s stock closed at **$101.89**, with a slight **0.48%** increase in price. Trading volume also rose by **29.12 million units**, indicating significant market interest during the analysis period.

4. **Stock Volume Patterns**:
   - The trading volumes for Apple were consistently higher than Foxconn, with spikes around major product releases, such as new iPhones.

## Graphical Insights

### 1. **Price Percent Change Histogram**:
   - This histogram shows the distribution of daily price changes for both Apple and Foxconn. Apple's stock exhibited more volatility in terms of price changes compared to Foxconn, reflecting its more consumer-driven nature.

### 2. **Volume of Stocks Over Time**:
   - This line chart tracks the daily trading volume for both companies, showing Apple’s consistently higher volume. Notable spikes correspond to major product releases, especially for Apple.

## Interactive Tableau Dashboard

I created an interactive dashboard in Tableau to allow for an intuitive exploration of the stock data. The dashboard includes:
- **Product Filters**: Enables users to select specific Apple product releases and analyze their impact on stock performance.
- **Price and Volume Trends**: Visualizes the price and volume fluctuations for both companies, with easy-to-use filters for specific time periods and events.
- **Summary Table**: Provides a side-by-side comparison of closing prices, price changes, and trading volumes for both companies.

### Key Features of the Tableau Dashboard:
- **Product Focus**: Users can focus on specific Apple product releases and explore the related stock performance data.
- **Company-wise Breakdown**: Allows users to switch between Apple and Foxconn for a company-specific analysis.
- **Interactive Filters**: Users can explore different time frames and compare the performance of both companies over time.

## Conclusion

This project provides valuable insights into the relationship between Apple and Foxconn's stock performance, particularly around the release of key Apple products. The analysis highlights how interconnected the two companies are and how Apple's product launches significantly affect both stocks. The Tableau dashboard enhances this analysis by offering an interactive platform for data exploration.
