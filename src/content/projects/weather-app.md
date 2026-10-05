---
title: "Weather App"
description: "A live weather app that shows current conditions for any city in the world, using the Open-Meteo API."
publishDate: 2026-09-27
tags: ["Astro", "JavaScript", "API", "Open-Meteo"]
githubUrl: "https://github.com/joblomint/weather-app"
liveUrl: "https://weather.jkay.my.id/"
---

A real weather app built with Astro — no frameworks, no libraries, just the Open-Meteo API and vanilla JavaScript.

## Features

- **Search any city** in the world
- **Auto-detects coordinates** using Open-Meteo's geocoding API
- Shows **current temperature**, condition, and emoji icon
- **Feels like** temperature, **humidity**, and **wind speed**
- **°C / °F toggle**
- **Dynamic background** that changes based on weather
- **Handles errors** gracefully
- Auto-loads Nairobi on first visit

## What I Learned

- Fetching from an API with `async/await` and `fetch()`
- Chaining two API calls
- Loading and error states
- State management for the °C/°F toggle
- Dynamic styling based on data
