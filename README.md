# Weather
An app that gets a user’s location and displays their current weather information

**Project 7** - [Vanilla JS Academy](https://vanillajsacademy.com/) (Fall 2019)


### Part 1

**Weather App**  [Demo](https://letioneill.github.io/weather/01-weather-app.html)

*Use free [ipapi service](https://ipapi.co/) to get user's location and use returned location data to get the weather data*

### Part 2

**Weather App Plugin**  [Demo](https://letioneill.github.io/weather/02-weather-app-plugin.html)

*Modify weather app script to convert it into a plugin. *

Customizable Options [located in the footer of html files]

```
getWeather({
  apiKey: '',
  convertTemp: false,
  location: '{{city}}, {{state}}',
  description: '☃ {{description}}',
  showFeels: false,
  showSunrise:false,
  showSunset: false,
  showVisibility: false,
  showWind: false,
  showHumidity: false,
  noWeather: 'No weather available where you are!',
  showIcon: false
});
```
