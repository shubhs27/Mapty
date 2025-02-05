# Mapty - Map Your Workouts

Mapty is a web application that allows users to log their running and cycling workouts on an interactive map. Built with JavaScript and the Leaflet.js library, it leverages geolocation to pinpoint the user's position and store workout data in the browser's local storage.

## Features

- **Geolocation**: Automatically fetches the user's location to place workout markers.
- **Workout Logging**: Users can log running or cycling workouts with details like distance, duration, and additional metrics.
- **Dynamic Map Rendering**: Uses Leaflet.js to display an interactive map.
- **Persistent Storage**: Saves workouts to local storage so data is retained between sessions.
- **Smooth UI Interactions**: Toggle input fields based on workout type and hide forms dynamically.

## Technologies Used

- **HTML, CSS, JavaScript**: For building the front-end.
- **Leaflet.js**: To handle interactive map functionalities.
- **Local Storage**: To persist workout data across sessions.

## Getting Started

### Prerequisites
- A modern web browser (Chrome, Firefox, Edge, etc.)

### Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/shubhs27/Mapty.git
   ```
2. Navigate to the project folder:
   ```sh
   cd mapty
   ```
3. Open `index.html` in a browser.

## Usage

1. Allow location access when prompted.
2. Click on the map to log a new workout.
3. Choose between "Running" or "Cycling."
4. Enter the required details and submit.
5. View your workouts in the sidebar and interact with the map markers.
6. Refresh the page to see your data persist.

## Resetting Data
To clear all stored workouts, open the browser console and run:
```js
app.reset();
```

## Screenshots
![image](https://github.com/user-attachments/assets/7bdb1f31-d8eb-4ed2-b5a5-9788be1e0597)



## Future Enhancements
- Ability to delete or edit workouts.
- Integration with fitness APIs for additional workout tracking.
- User authentication for cloud storage.


## Acknowledgments
- This project is part of Jonas Schmedtmann's Udemy course - The Complete JavaScript Course 2025: From Zero to Expert!
- All assets and UI components are inspired by the course material.

## License
This project is licensed under the MIT License.

---
Feel free to modify and enhance this project as needed!
