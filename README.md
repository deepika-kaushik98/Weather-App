
 #  React Weather App

A simple weather application built with **React.js** that allows users to check the current weather conditions of any city using a weather API.

---

##  Features
-  Search weather by city name
-  Fetch real-time weather data from an API
-  Displays temperature, humidity, wind speed, and weather condition
-  Responsive UI for desktop and mobile
-  Built with **React** and **OpenWeatherMap API**

---

##  Tech Stack
- **Frontend:** React.js, CSS
- **API:** [OpenWeatherMap API](https://openweathermap.org/api)
- **Build Tool:** Create React App (or Vite if you migrated)
- **Styling:** CSS / Tailwind 

---

##  Project Structure
```

weather-now/
│── public/              # Static files
│── src/
│   ├── components/      # React components
│   │   └── Weather.jsx
│   ├── App.js           # Root component
│   ├── App.css          # Styles
│   └── index.js         # Entry point
│── package.json
│── README.md

````

---

## ⚙️ Installation & Setup

1. Clone the repository
   ```bash
   git clone https://github.com/your-username/weather-app.git
   cd weather-app
````

2. Install dependencies

   ```bash
   npm install
   ```

3. Create a `.env` file in the root and add your API key:

   ```
   REACT_APP_WEATHER_API_KEY=your_api_key_here
   ```

4. Start the development server

   ```bash
   npm start
   ```

   App will run on  [http://localhost:3000](http://localhost:3000)

---

## API Key Setup

* Sign up at [OpenWeatherMap](https://openweathermap.org/api)
* Generate a free API key
* Add it in `.env` as shown above

---

##  Screenshots

<img width="1901" height="949" alt="Screenshot 2025-09-03 083252" src="https://github.com/user-attachments/assets/68a91b7a-0277-437d-942f-df7dd06772c0" />



---

##  To-Do / Future Enhancements

* Add 5-day forecast
* Improve UI/UX with Tailwind or Material UI
* Detect location automatically using Geolocation API
* Add PWA support for mobile

---

##  Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss what you’d like to change.

---




