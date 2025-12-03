# Weather-API
🌦️ Live Weather Dashboard for Egypt – Power BI + WeatherAPI

<img width="2752" height="1494" alt="unnamed" src="https://github.com/user-attachments/assets/684cd382-667d-4b7f-ba82-9d6d8c769f50" />


This project is a fully dynamic and automated Weather Dashboard built in Power BI, powered by real-time data from WeatherAPI.
It includes current conditions, hourly forecasts, 7-day forecasts, air quality metrics, and astronomy data.

🚀 Features

Live Weather Data (Auto-refresh)

7-Day Forecast Visualization

Hourly Rain Probability

Air Quality Gauge (PM10, PM2.5, CO, etc.)

Sunrise & Sunset Cards

Modern Dark UI with custom weather icons

Optimized data model using Star Schema

🔗 API Integration

Connected Power BI to WeatherAPI using GET requests:

Example:

https://api.weatherapi.com/v1/forecast.json?key=YOUR_KEY&q=CITY&days=7&aqi=yes&alerts=yes


Pulled:

Current weather

Forecast (daily & hourly)

Air quality

Astronomy data

🧩 Data Model

The model is organized into four main tables:

Locations

Current

Forecast_Day

Forecast_Hour

Designed using a Star Schema for clarity and performance.


📊 Dashboard Preview
<img width="1378" height="771" alt="Screenshot 2025-12-03 191316" src="https://github.com/user-attachments/assets/d97dfdfc-c620-42e9-8c16-12ca50330e41" />


📄 Project Files

PDF Version → [/PDF/Weather_Report.pdf
](https://github.com/mabdelkarem72/Weather-API/blob/main/Weather%20(1).pdf)
Power BI File (PBIX) → [/PBIX/Weather_Dashboard.pbix
](https://github.com/mabdelkarem72/Weather-API/blob/main/Weather.pbix)
Relationships  → [/API/api_request_example.txt](https://github.com/mabdelkarem72/Weather-API/blob/main/Screenshot%202025-12-03%20160703.png)

Everything is included for reproduction or learning.

🎯 Purpose

To practice:

API integration

Data modeling

Dashboard design

Automation

Real-world analytics workflow

📝 Technologies Used

Power BI

WeatherAPI

JSON

DAX

Power Query

⭐ Feel free to fork, explore, or leave a star!
