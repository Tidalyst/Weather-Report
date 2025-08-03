# Weather-Report

This project is a real-time weather dashboard built in Power BI, connected to a weather API to display up-to-date weather conditions and forecasts for selected locations.

🚀 **Features**

- Live weather updates (temperature, humidity, wind speed, etc.)
- 3–7 day weather forecast
- Location-specific data
- Automatic refresh using API connection
- Clean and interactive Power BI visuals

🔧 **Tools & Tech**

- Platform: Power BI
- Data Source: Weather API (https://www.weatherapi.com/)
- Data Handling: Power Query (M Language), Web API connector

🔗 **API Integration**

- Weather data fetched via REST API
- Example endpoint: http://api.weatherapi.com/v1/forecast.json?key=f7c16155aa424e8abc173944253007&q=Port Harcourt&days=7&aqi=yes&alerts=no
- API key is securely stored within the Power BI web connector setup

📊 **How It Works**

1. User selects a location
2. Power Query triggers API call
3. Real-time data is pulled and transformed
4. Visuals update automatically on refresh

📍 **Future Enhancements**

- Create mobile-optimized version
- Enable alerts for extreme weather conditions

📎 **Access**

- 🌐 Live version : https://app.powerbi.com/view?r=eyJrIjoiNzMwMGIxODctNWEwMy00MGQ4LWFlMDUtNjU2ZGQzMmE1OTkwIiwidCI6ImMzMTIwMjdlLTFmYWUtNDIwYi04NGI4LTJjOTBjOTFmNGI5YyJ9
