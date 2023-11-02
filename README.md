# VueWeatherApp

VueWeatherApp is a simple web application that allows you to check the weather conditions for a specific location. It is built with Vue.js and uses the OpenWeatherMap API to fetch weather data.

## Features

- **Current Weather:** Get the current weather information for a location.
- **Temperature in Celsius:** The temperature is displayed in Celsius.
- **Weather Description:** You can see a brief description of the weather conditions (e.g., sunny, cloudy, rainy).

## Prerequisites

Before using the WeatherApp, you need to have the following:

- Node.js: Make sure you have Node.js installed on your computer. You can download it from [nodejs.org](https://nodejs.org/).
- Vue cli 3: You need to have vuecli 3 installed on your computer. You can install it by running the following command in your terminal:
- Follow this guide, if you need help [cli.vuejs.org](https://cli.vuejs.org/guide/installation.html)

  ```bash
  npm install -g @vue/cli
  ```

- OpenWeatherMap API key: You need an API key from [OpenWeatherMap](https://openweathermap.org/api) to fetch weather data. You can sign up for a free account and get an API key.

## Getting Started

Follow these steps to run the WeatherApp on your local machine:

1. Clone the repository:

   ```bash
   git clone https://github.com/midoch/Vue-Weather-App
   ```

2. Navigate to the project directory:

   ```bash
   cd weatherapp
   ```

3. Install the project dependencies:

   ```bash
   npm install
   ```

4. Obtain an API key:

   You need an API key from [OpenWeatherMap](https://openweathermap.org/api) to fetch weather data. You can sign up for a free account and get an API key.

5. Configure your API key:

   Open the `src/App.vue` file and replace `"YOUR_API_KEY_HERE"` with your actual OpenWeatherMap API key:

   ```javascript
   api_key: "YOUR_API_KEY_HERE",
   ```

6. Run the application:

   ```bash
   npm run dev
   ```

7. Open your web browser and visit [http://localhost:8080](http://localhost:8080) to use the WeatherApp.

## Usage

1. Enter a location (e.g., a city name) in the search bar and press `Enter` to fetch the weather information.

2. The current weather details for the entered location will be displayed, including the location name, date, temperature, and weather description.

3. You can search for different locations by entering a new query in the search bar.

## Credits

WeatherApp is built with Vue.js and uses the OpenWeatherMap API to fetch weather data.
