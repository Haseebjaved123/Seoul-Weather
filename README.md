# 🌤️ Seoul Weather Tracker

<div align="center">

![Seoul Skyline](https://img.shields.io/badge/Seoul-Weather%20Tracker-blue?style=for-the-badge&logo=github)
![Python](https://img.shields.io/badge/Python-3.9+-yellow?style=for-the-badge&logo=python)

*A beautiful README that shows Seoul's current weather. Update it whenever you like.*

</div>

---

## 🌦️ Current Weather in Seoul

<div align="center">

| 🌡️ Temperature | 🌤️ Weather | 💨 Wind | 🌡️ Feels Like |
|:---:|:---:|:---:|:---:|
| **23°C** | ⛅ Partly Cloudy | 5.4 m/s | 23°C |

</div>

---
:|:---:|:---:|:---:|
| **24°C** | 🌤️ Mainly Clear | 5.4 m/s | 24°C |

</div>

---
:|:---:|:---:|:---:|
| **25°C** | ☀️ Clear Sky | 7.1 m/s | 25°C |
</div>

---

## 🚀 Features

- **Simple, clean layout** that looks good even between updates
- **Weather data** from Open-Meteo API (free)
- **Emoji-based weather display**
- **Responsive design** for all devices
- **Error handling** for API failures

## 🛠️ Setup Instructions

### 1. No API Key Required! 🎉
This project uses the completely free [Open-Meteo API](https://open-meteo.com/) - no registration or API key needed!

### 2. Update Manually (when you want)
Run the script locally whenever you want to refresh the data:

```bash
python update_weather.py
```

## 📁 Project Structure

```
Seoul-Weather/
├── .github/
│   └── workflows/
│       └── weather-update.yml    # GitHub Actions workflow
├── update_weather.py             # Python script for weather updates
├── requirements.txt              # Python dependencies
├── .gitignore                    # Git ignore file
└── README.md                     # This file
```

## 🔧 How It Works

1. Run the Python script when you choose
2. The script fetches weather data from Open-Meteo
3. The script updates the table in `README.md`

## 🌟 Customization

You can easily customize this for any city by:
- Changing the coordinates in `update_weather.py`
- Modifying the emoji mappings
- Adjusting the update frequency in the workflow
- Customizing the README layout

## 📊 Weather Data Includes

- 🌡️ Current temperature
- 🌤️ Weather conditions with emojis
- 💨 Wind speed
- 🌡️ "Feels like" temperature

---

<div align="center">

**Made with ❤️ for Seoul weather enthusiasts**

[![GitHub](https://img.shields.io/badge/GitHub-Profile-black?style=for-the-badge&logo=github)](https://github.com)
[![Open-Meteo](https://img.shields.io/badge/Weather%20Data-Open--Meteo%20(Free!)-green?style=for-the-badge)](https://open-meteo.com/)

</div>
