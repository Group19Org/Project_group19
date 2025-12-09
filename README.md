# Project_group19

# Smart Travel Itinerary Planner

A full-stack web application designed to help users plan multi-city trips with integrated, real-time weather insights. This project orchestrates travel itineraries by synchronizing destinations with forecast data, ensuring travelers are prepared for the weather at each leg of their journey.

## 🎓 Academic Context

This project was developed as part of the **Bachelor's Degree in Computer Science** at the **University of Trento**.

**Team Members:**
*   **Giacomo Catelan**
*   **Nicolo Monico**
*   **Francesco Weikman**
*   **Leonardo d'Incau**

## 🚀 Features

*   **Multi-City Itineraries**: Create and manage complex trips involving multiple destinations.
*   **Weather Synchronization**: Automatically fetches and displays weather forecasts for specific dates and locations within an itinerary.
*   **User Management**: Secure user registration and authentication system linked to personal itineraries.
*   **Historical & Forecast Data**: Aggregates 3-hour forecast intervals into daily summaries for easy reading.
*   **Interactive UI**: Dynamic dashboard to visualize trip timelines and associated weather conditions.

## 🛠 Tech Stack

*   **Backend**: Node.js, Express.js
*   **Database**: MongoDB, Mongoose
*   **Frontend**: HTML5, CSS3, JavaScript (ES6+), jQuery
*   **External APIs**: OpenWeatherMap API
*   **Documentation**: OpenAPI 3.0 (Swagger)

## 📦 Installation & Usage

1.  **Clone the repository:**
    git clone <repository-url>
    cd wag/group_19
    2.  **Install dependencies:**
    npm install
    3.  **Configure Environment Variables:**
    Create a `.env` file in the `group_19` directory with the following keys:
    API_KEY=your_openweathermap_api_key
    DB_CONNECTION_ONLINE=your_mongodb_connection_string
    4.  **Run the application:**
    node server.js
        The server will start on `http://localhost:3000` (or the port defined in your environment).

## 📄 API Documentation

The API specification is available in the `oas3.yaml` file located in the root directory. It follows the OpenAPI 3.0 standard.