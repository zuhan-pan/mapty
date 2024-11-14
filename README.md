# 🗺️ Mapty – Track Your Workouts!

Mapty is a **workout tracker application** that combines modern JavaScript, **Leaflet.js**, and browser **local storage** to deliver an engaging user experience. It lets users log their running and cycling workouts on a map, store their data, and manage their progress over time.

---

## 🚀 Features
- **Interactive Map**: View and log workouts directly by clicking on the map.
- **Dynamic Workout Details**: Track distance, duration, and additional metrics like pace (running) or speed (cycling).
- **Persistent Data**: Workouts are saved to your browser's local storage and retrieved when you revisit.
- **Seamless UI**: Dynamic form toggling, real-time updates, and responsive design.
- **Activity Visualization**: Custom popups and markers to visually represent your workouts on the map.

---

## 🔧 Technologies Used
- **JavaScript (ES6+)**
- **HTML5 & CSS3**
- **SCSS**
- **Leaflet.js** for interactive maps
- **Browser Local Storage** for data persistence

---

## 🏋️‍♂️ How It Works
1. **Locate Yourself**: The app centers the map on your current location using the **Geolocation API**.
2. **Add Workouts**:
   - Click on the map to add a new workout.
   - Fill out the form with workout details like distance and duration.
3. **Dynamic Metrics**:
   - **Running**: Calculate pace (min/km) and cadence (steps/min).
   - **Cycling**: Calculate speed (km/h) and elevation gain.
4. **Save & Retrieve**: Workouts are saved in local storage for future sessions.
5. **Visualize**: See your workouts as markers on the map, complete with custom popups.

---

## 🛠️ Key Functionalities
- **Geolocation API Integration**: Automatically fetches your location for a personalized experience.
- **Leaflet.js Map**: Displays an interactive map with user-added workout markers and custom styles.
- **Object-Oriented Architecture**:
  - Base class for shared functionality.
  - Child classes for activity-specific logic.
- **State Management**: Ensures workouts are saved, retrieved, and displayed consistently.
- **Responsive Design**: Works seamlessly across devices with intuitive UI updates.

---

## 📦 Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/mapty.git
