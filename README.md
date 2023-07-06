# Travel Advisor

Travel Advisor is a web application that allows users to explore various travel destinations, find places of interest such as restaurants, and get real-time weather information. The application is built using React and integrates with external APIs to fetch data.

## Features

- Explore different types of places such as restaurants, hotels, attractions, etc.
- Filter places based on user ratings.
- View places on an interactive map.
- Get real-time weather information for the selected location.
- Autocomplete search functionality for easy place selection.

## Getting Started

To run the Travel Advisor application locally, follow these steps:

1. Clone the repository:

    - git clone https://github.com/your-username/travel-advisor.git

2. Install dependencies:
    ```
    cd travel-advisor
    npm install
    ```

3. Obtain API keys:

    - Get a Google Maps API key and enable the Places API and Geocoding API.
    - Obtain a Weather API key from [a weather data provider.](https://rapidapi.com/hub)

4. Configure API keys:

    - Create a `.env` file in the root directory.
    - Add the following lines to the `.env` file:

     ```
     REACT_APP_GOOGLE_MAPS_API_KEY=your-google-maps-api-key
     REACT_APP_WEATHER_API_KEY=your-weather-api-key
     ```

5. Start the development server:
    ```
    npm start
    ```
6. Open the application in your browser:

    http://localhost:3000

## Dependencies

The Travel Advisor application uses the following dependencies:
    
    React: A JavaScript library for building user interfaces.
    @material-ui/core: A popular UI component library for React applications.
    @material-ui/icons: Material Design icons for use with Material-UI components.

## Contributing

    Contributions are welcome! If you find a bug or want to add a new feature, feel free to open an issue or submit a pull request.
