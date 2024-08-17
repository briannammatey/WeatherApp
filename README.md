# Weather App 🌤️
## Welcome to my weather app !!! 🌸🌺🌞🌚
 <!-- Add a gif that would be fun -->
  <img src= "https://raw.githubusercontent.com/briannammatey/WeatherApp/main/dancing_sun.webp" alt="gif" width="150">
  
## Motivation
My primary motivation for developing this weatherapp was to practice using APIs, and deepen my understanding about API usage and implementation.

## Purpose
The purpose of the Weather App, is to give real time data of the weather based on the inputted City.

## HOW DO YOU USE:
It's very simple, Open the AppLauncher and input the city that you want to look up
### This is an example if I wanted to see the weather for Boston:
<br>
<br>
 <img src= "https://raw.githubusercontent.com/briannammatey/WeatherApp/main/weatherexample.png"  width="600">
<br>

### This is an example for Sacremento:


 <img src= "https://raw.githubusercontent.com/briannammatey/WeatherApp/main/secondweatherexample.png"  width="600">

## HOW IT WORKS
After you input your City, State, or Country, based on the weather the GUI, will change colors, or the image displayed, with the updated weather temperature, time, humidity, and precipitation.

 - Cloudy 🌥️ - Gray Background, with a word displayed *Cloudy*
 - Sunny ☀️ - Bright Blue Background with a word displayed *Clear*
 - Rainy 🌨️ - Dark Blue Background with a word displayed *Rainy*
 - Snowy ❄️ - A white Background with a word displayed *Snowy*

## API USED
This Weather App leverages the OpenWeatherMap API to provide real-time weather information based on user input. By integrating the Geolocation API, the app accurately retrieves and displays weather data for cities around the world.

### API Features
Real-Time Weather Tracking: Retrieve up-to-date weather information for any city using OpenWeatherMap API's GET methods.
City-Based Data Retrieval: Utilize Geolocation API to obtain precise weather data for specified locations.

## Features
### MAIN
  This is the Main method, that displays the Graphical user Interface using classes from Java Swing, and this is where we are going to display the information
### WeatherAPI
The WeatherAPI class handles all interactions with the OpenWeatherMap API. It manages API key authentication, establishes an HTTP connection, retrieves weather data, and parses the JSON response. This class ensures that weather data is accurately fetched and processed for display in the GUI.
 ### AppLauncher
 The AppLauncher class is responsible for initializing and launching the application. It sets up the necessary components, prepares the GUI, and ensures that the application starts smoothly.
 







