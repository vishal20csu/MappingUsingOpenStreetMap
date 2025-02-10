Mapping Using OpenStreetMap

Overview

This project is a mapping and routing application that uses OpenStreetMap (OSM) along with React, Leaflet, and Spring Boot. It allows users to:

Get directions from their current location to a destination.

Display real-time routes and travel estimates.

Features

User Location Access: Users can fetch their current location.

Search for Destination: Users can enter a destination name, and the backend fetches its coordinates.

Route Display: A route is drawn between the start and end locations.

Tech Stack

Frontend

React with React-Leaflet for map rendering

Leaflet.js for routing and overlays

Backend

Spring Boot for geolocation queries

OpenStreetMap (OSM) APIs for location search

Installation and Setup

Prerequisites

Make sure you have the following installed:

Node.js (for frontend)

Java & Spring Boot (for backend)

Clone the Repository

git clone https://github.com/vishal20csu/MappingUsingOpenStreetMap.git
cd MappingUsingOpenStreetMap

Backend Setup (Spring Boot)

Navigate to the backend directory:

cd MapperFunctionality

Build and run the Spring Boot application:

mvn spring-boot:run

Frontend Setup (React)

Navigate to the frontend directory:

cd bootReact

Install dependencies:

npm install

Start the development server:

npm start

Usage

Open the frontend in your browser (http://localhost:3000).

Click "Get Current Location" to fetch your location.

Enter a destination name and click "Find Destination".

The map will display the route from your current location to the destination.

API Endpoints

Method

Endpoint

Description

GET

/location?query={destination}

Fetch geolocation for a given destination

Troubleshooting

Module Not Found Error: Run npm install in the frontend directory.

Backend Not Responding: Ensure your Spring Boot application is running on localhost:8080.
