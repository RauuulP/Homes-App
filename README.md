# HomesApp
This app allows users to explore a list of available housing locations, view detailed information about each property, and search for specific locations. The application leverages Angular's routing, services, and components to provide a seamless and responsive user experience.
This project was generated with Angular CLI version 17.3.11.

## Features
**Housing Locations Display**: View a list of housing locations with key details such as city, state, and availability.
**Search Functionality**: Filter housing locations based on city names to quickly find properties of interest.
**Details Component**: Access detailed information about a selected housing location, including property features and specifications.
**Routing**: Navigate between different views (e.g., housing list and details) using Angular's routing module.
**Service Integration**: Fetch and manage housing location data through a dedicated HousingService.
**JSON Server Integration**: The app retrieves data from a local JSON server, simulating a real API backend.

## JSON Server Setup
To serve housing location data, a JSON server is used. The data is stored in a db.json file and served from http://localhost:3000/.
**Steps to set up the JSON Server**:
1. Install JSON Server globally if you haven’t already: **npm install -g json-server**
2. Start the JSON Server with the following command: **json-server --watch db.json**
3. Once started, the server will be available at:
    **Index: http://localhost:3000/
    Endpoints: http://localhost:3000/locations**
4. JSON Server watches for changes in the db.json file and updates automatically.

## Installation and Setup:
Prerequisites:
Make sure you have Node.js and npm installed on your machine.

## Steps to run the application:

**Clone the repository**:
git clone https://github.com/RauuulP/Homes-App

**Navigate to the project directory**:
cd homes-app

**Run the following command to install all necessary dependencies**:
npm install

**Start the JSON Server**:
json-server --watch db.json

**Start the development server with**:
ng serve
