# Data-Visualization-CSV-NY
This project is an interactive data visualization tool that presents data related to New York City, including AirBNB listings, parties, and bars. The application utilizes modern web technologies such as HTML, CSS, and JavaScript, along with libraries like D3.js and PapaParse for visualizing the data. The aim of the project is to provide a visually appealing and user-friendly way to explore different datasets through various graph types and map visualizations.

## Table of Contents
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation and Setup](#installation-and-setup)
- [Steps to Run Locally](#steps-to-run-locally)
- [Project Structure](#project-structure)
- [Description of Key Files](#description-of-key-files)
- [Key CSS Styles](#key-css-styles)

## Features
  - Graph Visualizations: Pie charts and bar graphs displaying the distribution of AirBNBs, parties, and bars in New York City.
  - Map View: Interactive map to explore the geospatial distribution of data points.
  - Word Cloud: Visualize the frequency of keywords related to the datasets.
  - Responsive Design: The application adapts seamlessly to different screen sizes, offering a clean, mobile-first design.
  
## Technologies Used
  - HTML/CSS: Structure and styling of the pages.
  - JavaScript: Provides interactivity and dynamic data visualizations.
  - D3.js: JavaScript library used for creating interactive charts, graphs, and other data-driven visualizations.
  - PapaParse: Library for parsing CSV files and loading data into the application.
  - D3 Cloud Layout: A layout for creating word clouds (in the pipeline for future features).
  - Leaflet.js: (Optional, as mentioned in the CSS) for creating map-based visualizations.
    
## Installation and Setup
  Prerequisites
  - A modern web browser (e.g., Chrome, Firefox, Safari).
  - Basic understanding of HTML, CSS, JavaScript, and data visualization concepts.
  - No server setup is required as the application works with static files.
    
## Steps to Run Locally
1.Clone the repository:
git clone https://github.com/yourusername/nyc-data-visualization.git

2.Navigate to the project directory:
cd nyc-data-visualization

3.Open index.html in your browser to view the landing page. From there, you can:
Load the map by clicking the "Load Map" button.
Load different graph visualizations (pie charts, bar graphs) by selecting "Load Graphs".

4.Ensure that data files are in place (e.g., CSV files like AB_NYC_2019.csv) for the application to work correctly.

## Project Structure

    /nyc-data-visualization
    │
    ├── index.html           # The landing page with navigation buttons
    ├── map.html             # Map page (when implemented)
    ├── graphsChoice.html    # Page to choose between different graphs
    ├── style.css            # CSS for page layout and design
    ├── /CSV                 # Directory containing CSV data files
    │   ├── AB_NYC_2019.csv
    │   ├── party_in_nyc.csv
    │   ├── bar_locations.csv
    └── /scripts             # JavaScript files for interactivity (if any)

## Description of Key Files
  - index.html: The main page where users can navigate to the map and graph pages.
  - map.html: Intended for the map view (yet to be implemented fully, but may contain geospatial visualizations in the future).
  - graphsChoice.html: Allows users to choose between different graph types (pie charts, bar graphs).
  - style.css: The main stylesheet that provides the look and feel of the app:
    - Responsive Layout: Flexbox-based layout for a mobile-first, responsive design.
    - Dark Gradient Background: A dark gradient background for a modern and visually striking effect.
    - Button Styling: Buttons have interactive hover effects and stylish, purple color schemes.
    - Chart Styling: The charts (pie and bar) are styled with smooth transitions, borders, and appropriate spacing.
    
## Key CSS Styles
General Styling:
  - The page features a dark background gradient and a light text color for readability.
  - Flexbox layout ensures elements are centered, and there is flexibility for future scaling.
Button Styling:
  - Buttons are styled with a purple background and change color on hover for a better user experience.
Map Container:
  - The map initially appears hidden but can "grow" to fill the screen on demand using smooth transitions.
    

