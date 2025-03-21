![weather app](https://github.com/user-attachments/assets/015e7296-d502-4af0-88e1-b393326d4444)

🌦️ React Weather App
📌 Project Description
This is a simple React-based Weather App that fetches real-time weather data using an API. Users can enter a city name to get current weather conditions, including temperature, humidity, and wind speed.

🚀 Features
✅ Search Weather by City – Users can input a city name to get weather data.
✅ Real-time Weather Data – Fetches and displays live weather updates.
✅ API Integration – Uses OpenWeatherMap API to retrieve weather information.
✅ Loading & Error Handling – Displays loading messages and errors if API requests fail.
✅ Component-Based Structure – Uses React functional components for modularity.

.

🔗 API Source
This app uses the OpenWeatherMap API to fetch weather data.
📌 API Documentation: https://openweathermap.org/api

To use this API, create a .env file and add your API key:

plaintext
Copy
Edit
VITE_WEATHER_API_KEY=your_api_key_here
⚛️ React Hooks Used
🟢 useState (for managing state)
Stores user input (city name)
Stores fetched weather data
🔵 useEffect (for fetching data when the city changes)
Runs when the user searches for a city
Calls the weather API



<<<<<<< HEAD
# react-weather-app
=======
# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## Expanding the ESLint configuration

If you are developing a production application, we recommend using TypeScript and enable type-aware lint rules. Check out the [TS template](https://github.com/vitejs/vite/tree/main/packages/create-vite/template-react-ts) to integrate TypeScript and [`typescript-eslint`](https://typescript-eslint.io) in your project.
>>>>>>> d2d3273 (initial commit)
