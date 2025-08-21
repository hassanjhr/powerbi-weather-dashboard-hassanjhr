# 🌦 Power BI Weather Dashboard

This project is a **Power BI Dashboard** built using data from the [WeatherAPI](https://www.weatherapi.com/).  
The dashboard provides daily updated weather insights for six major cities in Pakistan:

- 🌆 Karachi  
- 🏙 Islamabad  
- 🏘 Hyderabad  
- 🕌 Lahore  
- 🏞 Multan  
- 🏡 Rawalpindi  

The purpose of this project is to demonstrate **data extraction from an API**, **data transformation in Power BI**, and **dynamic visualization for real-time insights**.

---

## 📊 Dashboard Features

- ✅ Current weather updates for six major Pakistani cities  
- ✅ Visualizations of temperature, humidity, and condition trends  
- ✅ Comparison of weather metrics across different cities  
- ✅ Automatically refreshed data (ensuring daily updates)  
- ✅ User-friendly design for quick insights  

---

## ⚙️ Technical Details

- **Data Source:** [WeatherAPI](https://www.weatherapi.com/)  
- **Tool Used:** Microsoft Power BI Desktop  
- **File Type:** `.pbix` (Power BI Report File)  
- **Data Refresh:** Configured for daily updates when refreshed  

---

## 📐 DAX Measures Used

The following measures were created in Power BI to enhance insights and interactivity:

- **Curr_Temp_C** → Current temperature in °C  
- **Last_Updated_Date_Curr** → Displays last updated date from API  
- **For_Temp_C** → Average forecast temperature in °C  
- **Wind_Speed** → Current wind speed in Kph  
- **Left_Value_PM10** → Remaining AQI value for PM10 (against MaxValue=300)  
- **Left_Value_Rain** → Remaining % chance of rain (100 – forecasted %)  
- **MaxValue** → Reference value for AQI scale (300)

### 🏭 Air Quality Index (AQI) Measures
- **NO2 Color, O3 Color, PM10 Color, PM2.5 Color, SO2 Color, CO Color** → Color coding of AQI levels  
- **PM10 Status** → Categorizes AQI into "Good", "Moderate", "Unhealthy", etc.  
- **PM10 Suggestion** → Provides health/safety advice based on AQI level  

These measures make the dashboard more **interactive** and help visualize air quality along with actionable insights (e.g., when to avoid outdoor activity).


## 📸 Dashboard Preview

### Day-Before-Yesterday (Old Data Snapshot)
![Old Dashboard](images/dashboard-old.png)

### Today’s Dashboard (After Refresh)
![New Dashboard](images/dashboard-today.png)

The dashboard updates when refreshed in Power BI, always pulling the latest data from WeatherAPI.  


---

## 🚀 How to Use
1. Download the `.pbix` file (`WeatherDashboard.pbix`) from this repo.  
2. Open it in **Power BI Desktop**.  
3. Click **Refresh** to fetch the latest weather data from WeatherAPI.  

---

## ⚙️ Technologies Used
- **Power BI Desktop** (for data modeling & visualization)  
- **DAX Measures** (for calculations & forecast insights)  
- **WeatherAPI** (for live weather data)  

---

## 📌 Author
- **Muhammad Hassan Jawaid**  
- MS Data Science Student | Power BI Developer  
