# 20th Century Geopolitical Network Analysis:


20th Century Geopolitical Analysis
Data Visualization with Python: Constructing a Historical Network Analysis
Objective
The Institute for Public Policy requires a comprehensive analysis and visualization of the relationships between nations during the 20th century. Given the instability of global politics, the Institute seeks to explore historical connections between countries to aid its research.

This project aims to:

- Identify influential nations and their roles in shaping key geopolitical events of the 20th century.

- Examine historical relationships through centrality measures (degree, closeness, betweenness).

- Visualize the connections and communities among countries using advanced graph analysis techniques.

## Project Overview
This repository presents a thorough analysis of the relationships between countries during the twentieth century. It includes the following:

1- **Data Processing**

- Historical data on geopolitical events and relations was gathered and converted into a network graph, where:

- Nodes represent countries.

- Edges represent significant historical connections or interactions.

2- **Data Source**

- Data was extracted from the Wikipedia page, Key events of the 20th century. 
- The full text of the article was saved as a text file, 20th Century Events.txt, using BeautifulSoup. 
- Additionally, Selenium was used to compile a list of country names from the article into a CSV file, countries_list_20th_century_1.5.csv.

3- **Graph Analysis**

- The network was analyzed using NetworkX for:

- **Degree Centrality**: To identify countries with the most direct connections.

- **Closeness Centrality**: To find central countries that can quickly connect with others in the network.

- **Leiden Communities**: To detect groups of countries with shared historical or geopolitical relationships.

4- **Visualizations**

- **Network Graph**: A visual representation of country relationships, color-coded by the communities identified through the Leiden algorithm.

- **Centrality Plots**: Bar charts displaying the countries with the highest degree and closeness centrality scores.

## Visualization of 20th Century Geopolitical Analysis (NLP application output)
Click [here](https://drive.google.com/file/d/1l270Gk35ADIM3xqPavVgE2v7xH0CONLO/view?usp=sharing)

## Requirements
To run the project, the following libraries are required:
- `Python==3.10`
+ [Requirements files](https://github.com/TNIBM/20th-Century/tree/main/Requirements)
 
## Conclusion
This project offers significant insights into the historical relationships between countries in the 20th century. 
By exploring the roles and connections of various nations, researchers can enhance their geopolitical analyses and policy recommendations. 
The visualizations and metrics provide an effective and accessible way to understand the complexities of global politics during this turbulent era.
