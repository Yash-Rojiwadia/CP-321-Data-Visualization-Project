# CP 321 Project : Covid-19 in America
This project is focused on tracking Covid-19 cases in the 7 days of March 2022 in each country of America. The data was collected from official government sources and compiled into a comprehensive map for analysis.

This is a HTML and JavaScript code that creates a choropleth map showing COVID-19 cases in North and South America. The map is interactive, allowing the user to select between different options for viewing the data, such as viewing data from the current week or the previous week.

The code uses the D3.js library to create the map, and loads in data from two external sources: a JSON file containing geographical data, and a CSV file containing COVID-19 data for each country in the Americas.

The code creates a dropdown menu with six different options for viewing the data. When the user selects an option, the code removes any existing map and creates a new one based on the user's selection.

The map uses a Mercator projection to display the geography of the Americas, and color-codes each country based on its number of COVID-19 cases. The color scheme is determined by a color scale that maps different ranges of cases to different colors. The legend at the bottom of the map shows the color scale and the corresponding ranges of cases.
