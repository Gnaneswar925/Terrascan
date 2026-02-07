# TerraScan & TerraBot  
**Smart Soil Analysis and Intelligent Farming Assistant**

---

## Overview
**TerraScan** is a web-based soil analysis platform integrated with IoT hardware to evaluate soil parameters and predict soil type.  
**TerraBot** is an intelligent assistant module that provides crop recommendations and farming insights based on detected soil characteristics.

This project is designed to support **smart agriculture**, **academic research**, and **educational demonstrations** by transforming raw soil data into meaningful, actionable information.

---

## Key Features

### TerraScan – Soil Detection Interface
- Input and analyze critical soil parameters:
  - pH Value  
  - Moisture (%)  
  - Temperature (°C)  
  - Nitrogen (N)  
  - Potassium (K)  
  - Phosphorus (P)  
- Soil type prediction based on provided values  
- Clean, responsive, and user-friendly interface  
- Compatible with IoT sensor data integration  

### TerraBot – Intelligent Farming Companion
- Crop recommendations based on soil type  
- Educational insights for better agricultural decisions  
- Supports multiple soil categories:
  - Sandy Soil  
  - Clay Soil  
  - Silt Soil  
  - Loamy Soil  
  - Peaty Soil  
  - Saline Soil  
  - Chalky Soil  

---

## Project Objectives
- Bridge **IoT hardware sensing** with **web-based analytics**
- Provide accessible soil intelligence for farmers and students
- Encourage **data-driven agriculture**
- Serve as a scalable foundation for future AI-powered farming tools

---

## System Architecture

### Frontend
- HTML5  
- CSS3  
- JavaScript  

### Backend (Optional / Extendable)
- Node.js / Express  
- Python (Flask / Django)  
- Machine Learning Model for Soil Classification  

### Hardware Integration
- Arduino Uno  
- Soil Moisture Sensor  
- pH Sensor  
- Temperature Sensors (TMP36 / DHT11/DHT22)  
- LCD / OLED Displays  
- Breadboard, Resistors, and Jumpers  

---

## Workflow
1. User inputs soil parameters manually **or** receives them from sensors.
2. The system processes the input data.
3. Soil type is predicted using predefined logic or ML model.
4. TerraBot generates crop recommendations and insights.
5. User receives actionable agricultural guidance.

---

### Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/terrascan.git
