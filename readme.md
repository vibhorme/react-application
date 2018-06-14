# React Weather



The following services are used to obtain weather and location data:

* WeatherService - A wrapper that is responsible for integrating with the [OpenWeather Api]. It provides an interface that allows one to obtain current weather, daily forecast, and hourly forecast information.

* GeolocationService - A wrapper that is responsible for integrating with the [Google Geolocation API]. It provide an interface that allows one to obtain the current GPS coordinates. These coordinates are used by the _WeatherService_ to obtain weather information.


Features:

* Display current weather
* Display 7 day weather forecast
* Display 24 hour weather forecast

This project also demonstrates:

* a typcial React project layout structure
* babel setup and configuration
* webpack setup and configuration
  * dotenv setup included
* Third party React component integration using _'[React Owl Carousel 2]'_
* eslint setup and configuration
* SCSS setup and configuration
* [OpenWeather API] integration
* [Google Geolocation API] integration



## Developed With

* [Visual Studio Code](https://code.visualstudio.com/) - A source code editor developed by Microsoft for Windows, Linux and macOS. It includes support for debugging, embedded Git control, syntax highlighting, intelligent code completion, snippets, and code refactoring
* [Node.js](https://nodejs.org/en/) - Javascript runtime
* [React](https://reactjs.org/) - A javascript library for building user interfaces
* [Babel](https://babeljs.io/) - A transpiler for javascript
* [Webpack](https://webpack.js.org/) - A module bundler
* [SCSS](http://sass-lang.com/) - A css metalanguage
* [Bootstrap 4](https://getbootstrap.com/) - Bootstrap is an open source toolkit for developing with HTML, CSS, and JS
* [Axios](https://github.com/axios/axios) - Promise based HTTP client for the browser and node.js
* [OpenWeather API] - Provides weather information
* [Google Geolocation API] - Provides geolocation information
* [React Owl Carousel 2] - A third party react carousel component
* [Surge] - Static web publishing for Front-End Developers

---



Before continuing, the following steps are required:

1. Get API keys

   * OpenWeather API

     Have a look at [OpenWeather API](http://openweathermap.org/api)

     Get an API key [here](http://openweathermap.org/appid)

   * Google Geolocation API

     Have a look at [Google Geolocation API]

     Get an API key [here](https://developers.google.com/maps/documentation/geolocation/get-api-key)






