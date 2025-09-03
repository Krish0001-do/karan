# Aura Weather Forecast

**Category:** Web / Frontend  
**Author:** karan  
**Difficulty:** Beginner / Intermediate  

---

## Description

Aura Weather Forecast is a responsive, modern weather application built using **HTML**, **CSS**, and **JavaScript**.  
It fetches real-time weather data and a 5-day forecast using the [WeatherAPI](https://www.weatherapi.com/) and displays it in both chart and card formats.  

The app features:
- Current weather information (temperature, humidity, wind, condition)
- 5-day forecast displayed as a chart for desktop and cards for mobile
- Dark / Light theme toggle with local storage
- Geolocation fallback to fetch weather for the current location
- Responsive design for both desktop and mobile
- Smooth glassmorphism effect for UI cards
- Error handling for invalid cities or geolocation issues

---

## Project Structure

AuraWeather/
├── index.html # Main HTML file
├── styles.css # CSS styling
├── scripts.js # JavaScript for API calls, theme, and dynamic content
├── night-mode.png # Icon for theme toggle button
└── README.md 


---

## Features

- **Current Weather:** Displays city, country, weather icon, temperature, feels like, humidity, wind speed, and local date/time.
- **Forecast:** Shows a 5-day forecast as:
  - **Chart** on desktop (line chart using Chart.js)
  - **Cards** on mobile (responsive flexbox)
- **Theme Toggle:** Light/Dark mode toggle with preference stored in localStorage.
- **Geolocation Support:** Automatically fetches weather for current location if no city is set.
- **Error Handling:** Displays messages for invalid input or failed API requests.

---

## How to Use

1. **Clone the repository** or download the project.
2. **Open `index.html`** in a browser (no server needed for basic usage).
3. **Enter a city name** in the search box or allow geolocation access.
4. **Toggle theme** using the button at the top right.
5. **View current weather and 5-day forecast.**

---

## Dependencies

- [WeatherAPI](https://www.weatherapi.com/) (API key required)
- [Chart.js](https://www.chartjs.org/) (for the forecast chart)
- Google Fonts - Raleway
- Font Awesome (for icons)

---

## Notes

- Ensure you replace `apiKey` in `scripts.js` with your valid WeatherAPI key.
- Works best in modern browsers (Chrome, Firefox, Edge, Safari).

---

## Credits

- **Frontend & JS:** karan  
- **Icons:** [WeatherAPI](https://www.weatherapi.com/)  
- **Fonts:** Google Fonts (Raleway)  
- **Charting:** Chart.js

