Real-Time Weather Data Analysis using OpenWeather API
📘 Overview

This project collects live weather data from the OpenWeatherMap API for major Indian cities, analyzes it using Python (Pandas, Matplotlib, Seaborn, Plotly), and generates multiple visual insights like temperature trends, humidity levels, pressure variation, and correlation between weather parameters.

The project demonstrates data collection, preprocessing, visualization, and interpretation — a complete mini data science workflow.

🧠 Objectives

Fetch real-time weather data using OpenWeather API.

Store data in structured CSV format.

Visualize key metrics (temperature, humidity, wind, pressure).

Identify hottest, coolest, most humid, and windiest cities.

Provide insights through charts and analytics.

🧩 Technologies Used
Category	Tools/Packages
Programming	Python
Data Handling	Pandas
Visualization	Matplotlib, Seaborn, Plotly
API Integration	Requests
Output	CSV + Interactive Charts
⚙️ Setup & Installation

1️⃣ Clone or download the project

git clone https://github.com/your-username/weather-analysis.git
cd weather-analysis


2️⃣ Install dependencies

pip install pandas requests matplotlib seaborn plotly


3️⃣ Get your API key from OpenWeatherMap
 and paste it in the code:

API_KEY = "your_api_key_here"


4️⃣ Run the project

python weather_analysis.py

📊 Data Collected

Each city’s record includes:

City	Temperature (°C)	Feels Like (°C)	Humidity (%)	Pressure (hPa)	Wind Speed (m/s)	Condition

Data is saved in:

Detailed_Live_Weather.csv

📈 Visualizations
Chart	Description
🌤️ Temperature Bar Chart	Displays city-wise temperature comparison.
💧 Humidity Chart	Shows variation of humidity levels.
🧭 Pressure Line Chart	Indicates atmospheric pressure stability.
🌬️ Wind Speed Pie Chart	Proportion of wind speeds among cities.
🔥 Correlation Heatmap	Displays relationships among weather parameters.
🌡️ Radar Chart	Circular temperature comparison.
☀️ Interactive Scatter Chart	Plotly chart showing relation between temperature & humidity.
📑 Sample Output
🌍 LIVE WEATHER DATA:
      City   Temperature (°C)  Humidity (%)  Wind Speed (m/s)  Condition
0   Nagpur               26.1            55               3.2      Clear
1    Delhi               23.4            61               2.9       Haze
2   Mumbai               30.3            79               3.7     Clouds
3     Pune               21.9            68               1.8     Clouds
4 Bengaluru              22.7            75               4.1      Clear

📊 WEATHER ANALYSIS REPORT
----------------------------------------
🔥 Hottest City: Mumbai (30.3°C)
❄️ Coolest City: Pune (21.9°C)
💧 Most Humid City: Chennai (82%)
🌬️ Windiest City: Bengaluru (4.1 m/s)
🌍 Average Temperature Across Cities: 26.2°C
🌫️ Average Humidity Across Cities: 67.3%

💡 Insights

Coastal cities (like Mumbai, Chennai) show high humidity.

Inland cities (Delhi, Jaipur) experience more temperature fluctuations.

Higher wind speeds may indicate unstable weather or rain probability.

Consistent atmospheric pressure = stable climatic condition.

🧭 Future Improvements

Add 7-day forecast using the /forecast API.

Develop web dashboard (Flask + Plotly).

Automate daily weather data storage for trend analysis.

Integrate alert system (e.g., high heat or rainfall warnings).
