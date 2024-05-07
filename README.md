# TwitchViz
Web App for Dynamic Twitch Data Visualization with MongoDB, HTML/CSS/jQuery, and Charts.js

## Overview
In Iteration 3 of my Twitch data visualizing web application, we have completed the server-side code and introduced the client-side component. This version presents Twitch data in a browser with a clean and efficient interface, allowing users to interact with the data through documented functionalities.


## Execution
To run the application:
1. Ensure MongoDB is running.
   - Navigate to MongoDB's bin directory and execute `mongo`.
   - Example path: `C:\Program Files\MongoDB\Server\5.0\bin`
2. In the code's root directory, install dependencies and run the server-side code:
   - Install dependencies: `npm install`
   - Run the script: `node app.js`
3. Access the application at `localhost:3000` in a web browser.

## Features
- **Server-Side Execution**: Connects with MongoDB to deploy Twitch data to the respective collection.
- **Client-Side Rendering**: Utilizes HTML/CSS/jQuery to render data and provide interactivity.
- **Data Presentation**: Offers a static version of all data, a sample of relevant streamer objects, and graphical summaries of key statistics.

## Updates in Iteration 3
- **New Functionalities**:
  - Static data listing and updating with current values for the 'Streamer' collection.
  - Sample data display to optimize performance and reduce API requests.
  - Graphical summary of statistics using Charts.js.
- **Client-Side Enhancements**:
  - Extensive use of flexbox for responsive design.
  - Integration of Charts.js for data visualization.
  - Google Fonts for improved typography.
- **Data Management**:
  - Streamer data can be refreshed with updated values using the 'List' button.
  - Dismissed the implementation of sorting functionality and customized multi-parameter search.

## Future Considerations
- Implementing customized searches for non-numerical fields to group streamers by specific criteria.

## Views
The views section includes HTML, CSS, and JavaScript/jQuery scripts for event handling and component management.

### Scripts
- `add.js`: Event handling for creating new streamer entries.
- `find.js`: Retrieval, update, and deletion of collection documents.
- `list.js`: Dynamic table generation and data refresh.
- `graphs.js`: Creation and display of charts.
- `main.js`: Display logic for main tab functionality.

## Frontend Components
The webpage features responsive HTML elements, organized with flexbox and Charts.js. It includes forms for data entry, tables for data display, and charts for data summarization.

## Animation Effects
While minimal, the application uses Charts.js for sleek, responsive graph animations.



