
# Mapty Workout Tracker

A web application that allows users to track their running and cycling workouts on an interactive map.

## Features
 
-   🗺️ Interactive map using  Leaflet.js
-   🏃‍♂️ Track running workouts (distance, duration, pace, cadence)
-   🚴‍♀️ Track cycling workouts (distance, duration, speed, elevation gain)
-   📍 Automatic user location detection
-   💾 Local storage persistence
-   🎯 Click-to-add workout functionality

## Project Structure

-   index.html  - Main HTML document
-   style.css  - Styling with CSS custom properties
-   script.js  - Core application logic and classes
  <br>
  
## ✈️ [Live Site](https://moatassem5.github.io/Mapty-project/)
  <br>

## Technologies

-   HTML5
-   CSS3
-   JavaScript (ES6+)
-   Leaflet.js for maps
-   Geolocation API
-   Local Storage API


## Screenshots
**Home Page**

![enter image description here](https://i.postimg.cc/VkXYfhnJ/Mapty-Mockup.png)

**Active Page**
![enter image description here](https://i.postimg.cc/fLP4j7Y4/Mapty-Active-Mockup.png)

## Getting Started

1.  Clone the repository
2.  Install dependencies:

npm  install

3.  Open  index.html  in your browser

## Core Classes

### Workout

Base class for all workout types with common properties:

-   Date
-   Coordinates
-   Distance
-   Duration

### Running

Extends Workout with:

-   Cadence
-   Pace calculation

### Cycling

Extends Workout with:

-   Elevation gain
-   Speed calculation

### App

Main application class handling:

-   Map initialization
-   Workout form management
-   Local storage operations
-   Workout rendering
-   Event handling

## Usage

1.  Allow location access when prompted
2.  Click on map to add new workout
3.  Fill in workout details
4.  Submit to save
5.  Click on workout in list to center map

## Data Persistence

Workouts are automatically saved to browser's local storage and restored on page load.

## Acknowledgments

[Jonas Schmedtmann](https://github.com/jonasschmedtmann)
