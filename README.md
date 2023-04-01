# BIG-DATA

This project aims to perform an analysis of the Vendée Globe rankings using data available on their website. The code uses web scraping techniques to extract relevant information and download Excel files containing the rankings. It then creates a DataFrame that contains the important data for analysis. The rankings are selected based on defined criteria and concatenated to form a complete data table. Data visualization tools are then used to analyze the performance of different skippers throughout the race.

The project begins with web scraping to extract an identifier for each Excel file in the rankings section of the Vendée Globe website. This identifier takes the form of a date and time stamp that is then used to download the corresponding Excel file. However, due to issues with image content in the files, the Excel files are opened using pandas with the help of the xlwings library. The files are then processed and concatenated to form a complete DataFrame for analysis.

Data visualization tools, such as seaborn, are used to analyze the performance of different skippers throughout the race. The data is presented in various charts and graphs to provide insights into the performance of the skippers, including their speed, distance covered, and position in the race. Overall, the project provides a comprehensive analysis of the Vendée Globe race using publicly available data from the event's website.
