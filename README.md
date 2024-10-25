# ToDo List Dashboard

## Overview
The **ToDo List Dashboard** is a sleek and modern web application that integrates multiple features to help you stay organized and informed. It combines a task management system with useful daily widgets like weather updates, news headlines, and an inspirational "Quote of the Day." The dashboard is designed with a clean user interface and responsive design, ensuring it looks great on all devices.

### Features:
- **Current Date and Time:** The dashboard displays the current date and time, which updates in real-time.
- **Weather Updates:** Fetches and displays current weather information for a specified location using the OpenWeatherMap API.
- **Quote of the Day:** Displays a daily motivational quote to inspire users.
- **Picture of the Day:** Fetches an inspirational image of the day from NASA's Astronomy Picture of the Day (APOD) API.
- **Latest News Headlines:** Shows the top news headlines by fetching data from the NewsAPI.
- **To-Do List:** A fully functional task management tool that allows you to:
  - Add tasks with due dates and priorities (Low, Medium, High).
  - Mark tasks as complete or incomplete.
  - Edit or remove tasks.
  - Filter tasks by status (All, Completed, Incomplete).
  - Search tasks by name.
  - Clear all tasks.
  - Tasks are stored in the browser using `localStorage`, so they persist across sessions.

### Technologies Used:
- **HTML5** and **CSS3** for the structure and styling of the dashboard.
- **JavaScript** for handling dynamic content updates, such as fetching external API data and managing the To-Do list.
- **OpenWeatherMap API**, **NASA APOD API**, and **NewsAPI** for external data integration.

### How to Use:
1. **Clone the Repository:**
   ```bash
   git clone https://github.com/yourusername/todo-list-dashboard.git
   ```
2. **Open `index.html` in your browser to view the dashboard.**
3. Replace the placeholder API keys in the `script.js` file with your own from:
   - [OpenWeatherMap](https://openweathermap.org/)
   - [NASA APOD](https://api.nasa.gov/)
   - [NewsAPI](https://newsapi.org/)
