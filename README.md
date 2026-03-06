# Mapty
**Mapty** is an interactive single-page web application that lets you log your running and cycling workouts directly on an interactive map. Built with vanilla JavaScript, it uses the Leaflet library for maps and browser localStorage to persist your workout data.

## Features

-  Get your current geolocation automatically on page load
-  Interactive map (Leaflet) centered on your location
-  Click anywhere on the map → open workout form
-  Running workouts: distance, duration, cadence, calculated pace
-  Cycling workouts: distance, duration, elevation gain, calculated speed
-  All workouts saved in **localStorage** (persists after refresh)
-  Clickable workout list → moves map to that workout location
-  Workout markers & popups with custom styling
- Responsive sidebar layout

## Tech Stack

- HTML5 / CSS3 (custom modern design)
- Vanilla JavaScript (ES6+)
- [Leaflet.js](https://leafletjs.com/) – open-source interactive maps
- Geolocation API (`navigator.geolocation`)
- localStorage API
- OOP approach (classes: `Workout` → `Running` & `Cycling`, `App`)
