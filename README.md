# Project 3 - Data Visualization Track

## Outline
The following project focuses on analyzing data from the 45 most populous cities in Canada, providing insights into various aspects of the Canadain housing market. The key components of the project, along with their explanations and summaries, are found below:

### Summary Statistics Table
The following table displays the summary statistics for the data set I used. This table includes key measures, such as the minimum, maximum, mean, median, and standard deviations of house prices

![summary_stats](https://github.com/korzenim/project3/assets/148805368/25a6b3ad-c17c-4eb9-a3fa-50eeb61b40bc)
Some key information:
- The cheapest house price is $35,768
- The most expensive house price is $37 million!
- The average house is priced at about $943,000, with 3 beds and 2.5 baths

### Map Visualization:
Using the Folium Python library, I created a map visualization, showing the locations of the 45 cities in the dataset, along with the average house price for the city. You can drag the map to move around, zoom in on desired locations, and can select any of the 45 markers to show the city name and average house price.
The File, titled "canadian_house_prices_map.html" can be found in the main directory.

### Average House Price per City
The following bar chart showcases the average house price per city. This visualization provides a clear comparison of the housing costs across Canada's most populous cities.

![avg_price_per_city](https://github.com/korzenim/project3/assets/148805368/1198042c-eb67-448b-8b22-0b44d9cf1ea2)

Some key information:
- Canada's top 3 most expesive cities, based off housing prices, are:
      - White Rock, BC
      - Vancouver, BC
      - Maple Ridge, BC
- Canada's 3 least expensive cities, based off housing prices, are:
      - Regina, AB
      - Saint John, NL
      - Sault Ste. Marie, ON

### Price Per Income
Using the median house prices and median family earnings for each city, I created visualizations to highlight the price-to-income ratio for each city. This visualization allows for easy assessment of housing affordability across the different cities.

![ppi](https://github.com/korzenim/project3/assets/148805368/29b7994f-2692-408c-a659-d7d88b93737a)

Based on the Price per Income (ppi) statistic in the visualization, the most affordable and least affordable cities to live within in Canada are Regina, SK, and White Rock, BC, respectivley.

### Price Distributions
This histogram illustrates the distribution of the house prices in the 45 most populous cities in Canada. The visualization provides insight into the frequency of different price ranges.

![house_prices_distribution](https://github.com/korzenim/project3/assets/148805368/12f85204-85e5-4890-90f9-ac4627c71232)

From this visualization, we can see that the distribution of house prices are right-skewed, meaning there exist outliers that will overestimate the average house prices in the country. We can also see that the median house price is around $600,000, and that the vast majority of houses do not exceed a price of $3,000,000.

### Population Distribution
The following pie chart shows the population distribution, by province, in Canada. To be clear, this distributions is only based on these 45 cities, and not the entire Canadian population.

![piechart](https://github.com/korzenim/project3/assets/148805368/d553ab92-2c71-4785-8fa1-471e7e4b8261)

From this, we can see that the most populous provinces in our dataset are Ontario (with over 50% of city dwellers living in the province!), followed by British Columbia and Alberta.


Overall, the project presents a comprehensive analysis of housing market trends, affordability, and population distribution in Canada's most populous cities through a variety of visualizations and data summaries. These insights can be valuable for understanding regional differences and making informed decisions related to housing and urban planning.

## Ethical Considerations
When conducting data analysis projects such as this one, ethical considerations are important to ensure that the findings are accurate, unbiased, and respectful of individuals' privacy. For this project, the following ethical considerations were taken into account:
- Data Source and Integrity: The dataset was sourced from a reputable provider to ensure the data's accuracy and reliability. Any necessary data cleaning was performed to correct errors and remove outliers that could skew the analysis.
- Privacy and Anonymity: The dataset did not contain any personally identifiable information (PII), ensuring the privacy and anonymity of individuals represented in the data.
- Fair Representation: Visualizations and analyses were conducted in a way that fairly represents the data without misleading interpretations or selective reporting. This approach helps to avoid perpetuating stereotypes or biases related to geography, income, or housing.
- Transparency: The project's methods and sources have been documented to promote transparency. By providing references and outlining the project process, others can verify the findings and understand the context of the analysis.
By adhering to these ethical considerations, the project aims to provide a balanced and responsible analysis of Canadian housing market trends and population distribution.

## References
Link to dataset: https://www.kaggle.com/datasets/jeremylarcher/canadian-house-prices-for-top-cities




## Requirements:
1. Your project must include visualizations. The visualizations can be created with:
    - Python (e.g. Matplotlib, Pandas plotting, hvplot)
    - JavaScript (e.g. Plotly or Leaflet)
    - A Python or JavaScript visualization library that was not covered in class
2. Your project must include at least one JavaScript OR Python library that we did not cover.
3. Your project must be powered by a dataset with at least 100 records.
4. If possible, your final visualization should ideally include at least three visualizations.
5. Your GitHub repo must include a README.md with an outline of the project including:
    - An overview of the project and its purpose
    - Instructions on how to use and interact with the project
    - At least one paragraph summarizing efforts for ethical considerations made in the project
    - References for the data source(s)
    - References for any code used that is not your own
