# 🌍 Mapping Using OpenStreetMap

A **mapping and routing web application** built with **React**, **Spring Boot**, and **OpenStreetMap (OSM)**.  
It enables users to get directions, visualize real-time routes, and estimate travel details between their current location and any destination.

---

## ✨ Features

- 🧭 **User Location Access** – Fetch your current location with one click.  
- 🔍 **Search for Destination** – Enter a destination name, and the backend fetches its coordinates via OSM.  
- 🗺️ **Route Display** – Draws a live route between your start and end points.  
- 🚘 **Travel Estimation** – Displays travel distance and estimated time.  
- 🔄 **Real-Time Updates** – Automatically updates as you move or change destinations.  

---

## 🧰 Tech Stack

### 🖥️ Frontend
- **React** (for UI)  
- **React-Leaflet** (for map rendering)  
- **Leaflet.js** (for routing and overlays)  

### ⚙️ Backend
- **Spring Boot** (for REST API & geolocation queries)  
- **OpenStreetMap (OSM) API** (for geocoding & location data)  

---

## ⚡ Installation & Setup

### 🧩 Prerequisites
Make sure you have the following installed:
- [Node.js](https://nodejs.org/)
- [Java JDK 17+](https://adoptium.net/)
- [Maven](https://maven.apache.org/)

---

### 🔧 Clone the Repository
```bash
git clone https://github.com/vishal20csu/MappingUsingOpenStreetMap.git
cd MappingUsingOpenStreetMap

### 🔧 Backend Setup
cd MapperFunctionality
mvn spring-boot:run


### 🔧 Frontend Setup

cd bootReact
npm install
npm start


🧭 Usage

Open the React app in your browser → http://localhost:3000
Click “Get Current Location” to fetch your location.
Enter a destination name and click “Find Destination”.
The map will display your route and estimated travel details.


