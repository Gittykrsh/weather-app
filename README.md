# 🌦 Weather App Using API - Tkinter GUI Project

## 📌 Problem Statement
Users often need quick access to weather updates without browsing the internet or using cluttered apps.  
**Goal:** Build a clean, fast, and interactive GUI app to fetch and display weather data by city name.

---

## 🎯 Objective
Create a GUI-based Weather App that fetches weather details like temperature, humidity, visibility, etc., using an API and displays it in an interactive interface.

---

## 🛠️ Tools & Technologies

| Type         | Name / Library       |
|--------------|----------------------|
| Language     | Python               |
| GUI          | Tkinter              |
| API          | OpenWeatherMap       |
| Libraries    | `requests`, `Pillow`, `timezonefinder`, `pytz`, `configparser`, `threading` |

---

## 📥 Input & 📤 Output

| Input        | Output                                                  |
|--------------|----------------------------------------------------------|
| City Name    | 🌡 Temperature in °C                                     |
|              | 🌧 Weather description (e.g., Clear, Rain, Haze)         |
|              | 💧 Humidity (%)                                          |
|              | 🔵 Pressure (mBar)                                       |
|              | 👁 Visibility (km)                                       |
|              | 🕒 Local time based on location                          |
|              | 🌅 Sunrise and 🌇 Sunset times                            |
|              | 🌍 Weather icon based on condition                       |

---

## 🚀 Features

| Feature                        | Status |
|--------------------------------|--------|
| Search by city                | ✅     |
| Timezone-based local time     | ✅     |
| Dynamic weather icons         | ✅     |
| Reset button                  | ✅     |
| API key secured in config.ini | ✅     |
| Error handling                | ✅     |
| Window centered               | ✅     |
| Multithreading for API call   | ✅     |

---

## 🖥️ GUI Preview

![Preview](https://github.com/user-attachments/assets/58f9961b-7f94-4b56-99f8-cdb27a30b98b)

---

## 📁 Project Structure

```
WeatherApp/
├── app.py
├── config.ini
├── Icons/
│   ├── clear.png
│   ├── clouds.png
│   ├── Haze.png
│   ├── main.png
│   ├── overcast.png
│   ├── rain.png
│   ├── snow.png
│   ├── stormy.png
│   ├── sunny.png
│   └── Windy.png
├── Images/
│   ├── black_border.png
│   ├── bottom_bar.png
│   ├── location.png
│   ├── search_btn.png
│   ├── sunrise.png
│   ├── sunset.png
│   └── weather_icon.ico
└── README.md
```

---

## 🔐 config.ini Format

```
[Openweather]
api = YOUR_API_KEY_HERE
```

---

## 🧪 How It Works

1. User enters city name.
2. API call made to OpenWeatherMap.
3. Data parsed and displayed in UI.
4. TimezoneFinder determines local time of city.
5. Icons & layout update dynamically.

---

## ✅ Achievements

- Hands-on experience using real-time APIs
- Polished GUI with error handling and responsiveness
- Learned multi-threading and image handling in Tkinter

---

## 💡 Future Improvements

- 5-day forecast view
- Light/Dark mode toggle
- Option to auto-detect location via IP

---

## 📜 License

This project is open-source and free to use for learning or demo purposes.

---

## Made with ❤️ by Shakyasimha Das.
