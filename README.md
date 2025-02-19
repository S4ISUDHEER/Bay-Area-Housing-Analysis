# Bay-Area-Housing-Analysis

**My Approach and Key Findings**
I analyzed real estate listings across the Bay Area (focusing on counties like San Francisco, Alameda, Santa Clara) to understand the housing market dynamics, affordability, and to identify any downward pricing trends. My goal was to assess the types of properties listed and whether households in these areas can afford them based on median income.
**Data Sources:**
1.	Zip Code Data: I manually downloaded the zip code data from the government website to ensure the analysis focused on the relevant counties in the Bay Area.
2.	Property Listings: I scraped Realtor.com for approximately 900 listings, focusing on cities with more than 500 listings.
3.	Income Data: I pulled median household income data from government census sources to compare income levels with property prices.
**Process:**
-> Data Cleaning: I removed listings with corrupted data based on JSON parsing errors and focused only on median household income for analysis.
-> Top 20 Cities: I identified the top 20 cities by listing count, which helped narrow down the analysis to cities with many properties for sale.
<img width="1044" alt="Property distribution in the Bay Area" src="https://github.com/user-attachments/assets/4ed38e80-8ebb-4c86-a96a-c14d41be67a5" />

**Key Insights and Visualizations:**
**1.	Property Type Distribution:**
-> I used matplotlib and plotly to visualize the distribution of property types in the top 20 cities.
-> The analysis showed that condos and single-family homes make up the bulk of listings, with San Francisco having around 50% condos and San Jose showing a large number of single-family homes.
<img width="1031" alt="Most Popular Home Type In Bay Area" src="https://github.com/user-attachments/assets/3dff998c-00dc-4307-84ae-df1b25fdaf29" />

**2.	City-wise Property Distribution:**
-> I examined how property types are distributed across cities. In San Francisco, 43% of condos were listed, followed by San Jose and Walnut Creek, making up 65% of the condo listings in the Bay Area.
-> The trend showed a higher concentration of single-family homes in cities like Oakland and Santa Rosa.
<img width="1038" alt="City Wise Property Distribution For Condos" src="https://github.com/user-attachments/assets/599d0270-9d61-4fd2-9c32-787f94b41c84" />

**3.	Affordability Analysis:**
->	By calculating the median household income and factoring in EMI (Equated Monthly Installment) calculations, I assessed whether the typical family could afford properties in the area.
->	For 1-bedroom condos in cities like San Francisco, Mountain View, and San Jose, I found that median prices hovered around $600K, which is less affordable for many.
->	I calculated the EMI payable capacity using the assumption that families could spend up to 35% of their monthly income on housing.

<img width="1046" alt="Listing Prices for 1 Bed Homes" src="https://github.com/user-attachments/assets/7e8215e1-ef18-4fcf-9a7f-b7473e36c460" />

**4.	Discounted Listings:**
->	A unique feature I found was the high number of discounted listings, especially in San Francisco and San Jose. I observed that over 40 listings in San Francisco were priced below previous sale prices, suggesting motivated sellers or market corrections.

<img width="1042" alt="Affordability of Housing in Bay Area Cities" src="https://github.com/user-attachments/assets/70cc54f1-f5f6-4c39-8585-9f2fcd50c337" />

->	This trend of discounted properties was also visible in San Jose, where 30 listings showed similar price reductions, indicating that pricing adjustments were being made to match current market conditions.

<img width="1041" alt="Properties Listed at Discounts" src="https://github.com/user-attachments/assets/df45a35e-40ea-45c5-b64a-e123e7990e51" />

**5.	Price Trends and Market Dynamics:**
->	I visualized the relationship between square footage and listing prices using scatter plots, noting that most listings were under 3,000 sq ft, with a concentration around 1,500–2,000 sq ft for single-family homes and condos.
->	Properties with lower square footage (typically condos) were priced more affordably but still required significant investment in areas like San Francisco.
<img width="1037" alt="SQFT vs Price   Distribution of SQFT in Listings" src="https://github.com/user-attachments/assets/e6762b3e-6a4c-451a-9a56-5afcb5198ae4" />

**Key Findings:**
->	The majority of listings in the Bay Area are single-family homes and condos, reflecting the market’s focus on families.
->	Affordability is a major issue, especially in high-income cities like San Francisco and Mountain View, where 1-bedroom condos are priced around $600K.
->	There is a notable presence of discounted listings, particularly in San Francisco and San Jose, which may suggest a cooling market or opportunities for potential buyers.

<img width="1041" alt="Summary" src="https://github.com/user-attachments/assets/3e8ba6d3-43af-4578-8bde-d93201fb2ce8" />

