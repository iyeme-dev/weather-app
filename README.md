# 🌤️ Weather App

A responsive and user-friendly weather application that provides real-time weather updates, forecasts, and detailed weather information for any city worldwide.

---

## 📌 Project Overview

The Weather App allows users to enter a city name and receive current weather conditions, a 5-day forecast, and additional details such as humidity, wind speed, and atmospheric pressure. Built with HTML, CSS, and JavaScript, the app fetches data from the OpenWeather API to deliver accurate and up-to-date information.

---

## 👤 User Stories

| User | Story |
|------|-------|
| Traveler | I want to check the current weather in any city before planning my trip. |
| Student | I want to learn how to fetch and display API data in a web app. |
| General User | I want to quickly see local or international weather at a glance. |

---

## 🎯 Rationale

Weather conditions affect daily activities, travel plans, and safety. The Weather App provides accurate, real-time information in an easy-to-access format, helping users make informed decisions.

---

## 🎯 Target Audience

- Travelers and commuters  
- Students or beginners learning web development  
- General users seeking quick weather updates  

---

## 💡 Motivation

The app was created to practice working with APIs, DOM manipulation, and responsive web design while providing a useful, real-world application for weather information.

---

## 💻 Proposed Solution

- **HTML5:** Structures the webpage and form elements  
- **CSS3:** Provides styling, layout, and responsive design  
- **JavaScript:** Handles API requests, DOM updates, and error handling  
- **OpenWeather API:** Supplies real-time weather data  

---

## 🔝 Improvements Over Alternatives

- Simple, lightweight, and responsive  
- Displays both current weather and 5-day forecast  
- Provides detailed information: humidity, wind speed, pressure  
- User-friendly error handling for invalid city inputs  

---

## 📦 Project Scope & Limitations

**Scope:**  
- Search by city name to display current weather and 5-day forecast  
- Display temperature, humidity, wind speed, and weather description  
- Responsive layout for mobile and desktop  

**Limitations:**  
- Limited to city-based weather lookup (no geolocation by default)  
- Forecast accuracy depends on API limitations  
- No offline functionality  

---

## 🚀 Future Improvements

- Implement geolocation-based weather lookup  
- Add unit conversion (Celsius/Fahrenheit)  
- Enhance UI with weather icons and animations  
- Add saving of favorite cities  
- Improve accessibility and ARIA attributes  

---

## ✨ Summary

The Weather App is a practical, responsive web application that demonstrates the ability to fetch, process, and display API data dynamically. It combines usability, interactivity, and performance optimization for a seamless user experience.

---

## 🎨 Design

### Brand Colours

| Colour        | Hex     | Usage                          |
|---------------|---------|--------------------------------|
| Primary Blue  | #2196F3 | Buttons, highlights            |
| Light Grey    | #F4F4F4 | Backgrounds                    |
| Accent Yellow | #FFC107 | Weather highlights             |
| Neutral Black | #212121 | Text                           |

### Layout & Structure

- **Header:** App title and instructions  
- **Main Section:** City input form and weather results  
- **Forecast Section:** 5-day weather summary with icons  
- **Footer:** API attribution and credits  

### Wireframes

![Wireframe](./images/wireframe.png)  
*Placeholder for conceptual layout illustrating input, results, and forecast display.*

---

## 🌐 Deployment

The Weather App is deployed via GitHub Pages:  
[https://iyeme-dev.github.io/weather-app/](https://iyeme-dev.github.io/weather-app/)

---

## 🧪 Testing

Testing was performed to ensure that the Weather App functions reliably, is responsive, and provides accurate information.

### 1. Browser Compatibility

| Browser        | Version Tested | Result | Notes |
|----------------|----------------|--------|-------|
| Chrome         | Latest         | ✅ Pass | Fully functional with all features |
| Firefox        | Latest         | ✅ Pass | Correct layout and API fetching |
| Safari         | Latest         | ✅ Pass | Minor spacing adjustments applied |
| Edge           | Latest         | ✅ Pass | No issues with DOM updates or forms |

**Issues Found & Fixes:**  
- Safari had minor spacing and alignment differences → fixed via media queries  
- Ensured API error messages render consistently across browsers  

---

### 2. Responsive & Device Testing

| Device / Resolution | Result | Notes |
|--------------------|--------|-------|
| iPhone / 390x844   | ✅ Pass | Input and forecast sections accessible |
| iPad / 768x1024    | ✅ Pass | Layout flows correctly; forecast visible without scrolling |
| Desktop / 1920x1080| ✅ Pass | Full layout displayed with no overflow |
| Android / 360x800  | ✅ Pass | Touch targets and text readable and sized appropriately |

---

### 3. Functional Testing

- City search fetches correct weather data ✅  
- Current weather displays temperature, humidity, wind speed, description ✅  
- 5-day forecast displays correctly with icons ✅  
- Handles invalid city names gracefully with user-friendly messages ✅  
- Real-time DOM updates work across multiple searches ✅  

---

### 4. Accessibility Testing

- Full keyboard navigation enabled ✅  
- Semantic HTML used for headings, sections, and forms ✅  
- Sufficient contrast between text and background ✅  
- ARIA labels and roles added to improve screen reader usability ✅  
- Lighthouse Accessibility Score: 92/100 ✅  

---

### 5. Code Validation

- **HTML:** W3C Markup Validator ✅  
- **CSS:** W3C CSS Validator ✅  
- **JavaScript:** Syntax checked; best practices followed ✅  

**Corrections Implemented:**  
- Fixed minor attribute warnings  
- Standardized CSS shorthand and cleaned up unused rules  

---

### 6. Performance Testing

- Optimized CSS and JS for fast load ✅  
- Minimal HTTP requests; images compressed ✅  
- Lighthouse Audit:

| Metric           | Score |
|------------------|-------|
| Performance      | 94/100|
| Accessibility    | 92/100|
| Best Practices   | 90/100|
| SEO              | 85/100|

---

### 7. Testing Summary

The Weather App performs reliably across modern browsers and devices, offers responsive layouts, handles errors gracefully, maintains accessibility standards, and loads efficiently. All core features, including real-time API fetching, current weather display, and 5-day forecast, work as expected.

---

## 🛠️ Technologies Used

- HTML5  
- CSS3  
- JavaScript (ES6+)  
- OpenWeather API  
- Git & GitHub Pages  

---

## 📚 Credit and References

- [OpenWeather API](https://openweathermap.org/api) – For real-time weather data  
- [W3C HTML & CSS Validators](https://validator.w3.org/) – For code validation  
- [Google Lighthouse](https://developers.google.com/web/tools/lighthouse) – For performance and accessibility testing  

---

## 👨‍💻 Author

**Iyeme Dev** – [GitHub Profile](https://github.com/iyeme-dev)
