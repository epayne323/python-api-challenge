---
noteId: "1d1c6f8008bf11ea88c3dde764e4f982"
tags: []

---

# python-api-challenge
## Homework 06 - Python APIs

This notebook plots weather data for a randomly generated list of cities.

First, a list is generated of random (latitude, longitude) pairs selected from U(-90, 90) and U(-180, 180) distributions. Using the citipy library, each pair is matched to its closest city, discarding any duplicates. Each city is looked up in the openweathermap api for that city's current temperature, humidity, cloudiness, and windspeed (if the city is not found, it is excluded from further analysis). Each of these variables is plotted in separate figures against the city's latitude.