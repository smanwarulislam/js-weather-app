# js-weather-app

This project is a weather application that calls the OpenWeatherMap API to render the conditions of supplied countries and cities.

## Weather App

This app allows users to search for the weather in a given location. Check it out [here](https://smanwarulislam.github.io/js-weather-app/).

## Quick start

Make sure you have Node.js installed:

```node
node -v
```

If you don't have Node.js installed in your system get it from [here](https://nodejs.org). Once you're done with the installation, then type the following commands:

```git
git clone https://github.com/smanwarulislam/js-weather-app.git
cd js-weather-app
npm install
npm start
```

Runs the app in development mode.
Open [http://localhost:4444/](http://localhost:4444/) to view it in your browser.

## Instructions

To use the app, simply enter a location (city, country) in the form. The app will display the details of the current weather of that location.

However, due to the nature of GitHub Pages, the deployment will not work correctly. Please test it locally as the link above is for reference purposes only.

## API

This app uses the OpenWeatherMap API to retrieve weather data and the Rest Countries API to retrieve country names.

## Notes

1. This app was built using Bootstrap for styling and layout.
2. The frontend of this application uses REST API (also known as RESTful API). I used just normal Node.js, used Axios, and nothing else. Another thing I used is location. I used OpenWeatherMap to send requests. And some other interactivity tasks are done with normal JavaScript.
3. If I want to upload any application to the server site and if it is not a static site then what I need to do is to create a backend server. My backend server is built using Node.js.

So here (weather app) I am using the frontend:
- Vanilla JS or Core JavaScript
- Axios
- DOM Manipulation
- And the OpenWeather API

I need a database to store the history. I need a backend service. I used:
- Node.js
- body-parser middleware
- Mongoose
- MongoDB database (MongoDB Atlas)

## Development

You are welcome to make a PR for any kind of improvement to this project. If you find any issues, [let me know](https://github.com/smanwarulislam/js-weather-app/issues/new). Thank You!
