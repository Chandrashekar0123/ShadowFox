# 🌍 Air Quality Index (AQI) Analysis  

## 📌 Overview  
This project explores the **Air Quality Index (AQI)** in **Delhi**, analyzing key pollutants, seasonal variations, and geographical factors. The goal is to identify trends and provide insights into **air pollution levels**, which can help policymakers and the public take necessary measures for improvement.  

---

## 📊 About Air Quality Index (AQI)  
**AQI** is a measure of **air pollution levels**, indicating how clean or polluted the air is. It is influenced by various pollutants, including:  
- **PM2.5** (Fine Particulate Matter)  
- **PM10** (Coarse Particulate Matter)  
- **NO₂** (Nitrogen Dioxide)  
- **SO₂** (Sulfur Dioxide)  
- **CO** (Carbon Monoxide)  
- **O₃** (Ozone)  

Higher AQI values indicate **worse air quality**, posing health risks, especially for children, the elderly, and people with respiratory issues.  

---

## 📂 Dataset  
The project uses **real-world AQI data**, sourced from:  
- **Government air quality monitoring stations**  
- **Historical AQI datasets (CSV, JSON, API sources)**  

### 🔹 **Features Analyzed**  
- **Date & Time** (Hourly/Daily AQI values)  
- **Location-wise Pollution Trends**  
- **Seasonal and Monthly Variations**  
- **Impact of Weather Conditions on AQI**  
- **Comparison Across Different Locations**  

---

## 📉 Methodology  
### **1️⃣ Data Collection & Preprocessing**  
- Acquired **historical AQI data** for Delhi.  
- Cleaned and handled **missing values**.  
- Converted timestamps and formatted data for analysis.  

### **2️⃣ Exploratory Data Analysis (EDA)**  
- Analyzed trends across different seasons (Winter, Summer, Monsoon).  
- Identified **pollution spikes** (Diwali, Crop Burning, Weather Inversions).  
- Examined correlations between **pollutants and weather conditions**.  

### **3️⃣ Data Visualization**  
Using **Matplotlib & Seaborn**, we visualized:  
- **AQI Trends Over Time** 📈  
- **Seasonal & Monthly Variations** 📊  
- **Pollutant-Wise Contributions** 🌫  
- **Location-Based AQI Levels (Heatmaps)** 🗺  

### **4️⃣ Key Findings**  
- **Winters have the highest pollution levels** due to **low temperature and atmospheric inversion**.  
- **Post-Diwali AQI spikes** due to **firecrackers and crop residue burning**.  
- **Industrial & Traffic Zones show consistently higher AQI values**.  
- **Rainfall significantly reduces PM2.5 and PM10 levels**.  

---

## 🚀 Installation  
Ensure you have Python installed, then install the required libraries:  

```bash
pip install pandas matplotlib seaborn numpy

