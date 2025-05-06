# 🗺️ Mapty – Map Your Workouts

Mapty is a geolocation-based workout tracker built with vanilla JavaScript, HTML, and CSS. It allows users to log their running and cycling activities by clicking on the map. Workouts are stored in local storage and visualized both on the map and in a side list.

📍 **Live Preview:** [https://begriper.github.io/mapty/](https://begriper.github.io/mapty/)

## 🚀 Features

- 📍 **Geolocation**: Automatically gets your current position using the browser's Geolocation API.
- 🗺️ **Interactive Map**: Built with [Leaflet.js](https://leafletjs.com/) and OpenStreetMap tiles.
- 🏃‍♀️ **Running & Cycling Modes**: Supports two workout types with different metrics:
  - Running: Distance, Duration, Cadence, Pace
  - Cycling: Distance, Duration, Elevation Gain, Speed
- 📝 **Custom Workout Descriptions** based on date and type.
- 🧠 **OOP-based architecture**: Clean JavaScript using ES6+ classes.
- 💾 **Local Storage**: Saves workouts to the browser's local storage.
- 📌 **Map Markers**: Each workout is shown with a custom popup on the map.
- 🎯 **Smooth Zoom** to workout location when clicked in the list.

## 📦 Technologies Used

- HTML5 + CSS3
- Vanilla JavaScript (ES6+)
- Leaflet.js for map rendering
- OpenStreetMap tile layer

📁 File Structure

📦 mapty/
├── index.html
├── style.css
├── script.js
├── logo.png
├── icon.png
├── other.js (optional - for testing)
├── Mapty-architecture-part-1.png
├── Mapty-architecture-final.png
└── Mapty-flowchart.png

🧠 Built as part of the Complete JavaScript Course by Jonas Schmedtmann.
