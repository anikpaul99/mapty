# Mapty

Mapty is a web application designed to help you log and track your workouts on a map. Whether you're running downtown or cycling in the mountains, Mapty lets you record your activities with ease. The app uses geolocation to automatically detect your location and allows you to input workout details like distance, duration, and more. Your workouts are stored locally, enabling you to view your workout history and easily navigate to each workout on the map.

## Table of Contents

- [Features](#features)
- [Screenshots](#screenshots)
- [Technologies Used](#technologies-used)
- [Getting Started](#getting-started)
- [Contact](#contact)

## Features

- **Interactive Map:** The main interface is a map, loaded using the Leaflet library. The map is displayed on the right side of the screen, while a sidebar on the left shows your logged workouts.
- **Geolocation:** The app automatically detects your current location using the browser's geolocation API.
- **Workout Logging:** Log your workouts by clicking on the map. A form will appear, allowing you to input details such as type (running or cycling), distance, duration, cadence, or elevation gain.
  - **Running:** Input `Distance`, `Duration`, and `Cadence`.
  - **Cycling:** Input `Distance`, `Duration`, and `Elev Gain` (elevation gain).
- **Workout Statistics:** Once a workout is logged, a summary of the workout is displayed in the sidebar. The map also shows a pin at the workout location, with a popup displaying the workout details.
- **Persistent State:** The app stores your workouts in local storage, so your data remains intact even after you refresh or close the browser.
- **Map Navigation:** Click on any workout listed in the sidebar to automatically move the map to that workout location.

## Screenshots

1. **Screenshot of the Mapty App:**  
   ![Mapty Screenshot](screenshots/screenshot%20app.png)

## Technologies Used

- ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black) Vanilla JavaScript
- ![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white) HTML5
- ![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white) CSS3
- ![Leaflet](https://img.shields.io/badge/Leaflet-199900?style=flat&logo=leaflet&logoColor=white) Leaflet

## Getting Started

### Prerequisites

To run this project locally, you'll need a basic understanding of HTML, CSS, and JavaScript. No additional libraries or frameworks are required.

### Installation

1. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/yourusername/mapty.git
   ```
2. Navigate to the project directory:
   ```bash
   cd mapty
   ```
3. Open the `index.html` file in your preferred browser to start using the application.

## Contact

- 📧 **Email**: [hello@paulanik.com](mailto:hello@paulanik.com)
- 🌐 **Portfolio**: [paulanik.com](https://paulanik.com)
- 💼 **LinkedIn**: [LinkedIn Profile](https://www.linkedin.com/in/anik-paul-dev/)
- 📝 **Dev.to**: [Dev.to Profile](https://dev.to/anikpaul)
