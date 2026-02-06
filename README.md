# Energy Bill Predictor

![Energy Saving](https://via.placeholder.com/800x400?text=Energy+Bill+Predictor+App)  
*A Desktop GUI Application to Track, Analyze, and Predict Your Electricity Bills*

## Overview

**Energy Bill Predictor** is a Python-based desktop application built with **Tkinter** that helps users manage their household electricity consumption, predict future bills, and get personalized energy-saving recommendations.

It combines simple data entry, **machine learning** (linear regression), **data visualization** (Matplotlib charts), and an **AI-powered chatbot** (using Google Gemini) to provide actionable insights into energy usage.

## Key Features

- **Add & Manage Appliances**  
  Add common household appliances (Fan, AC, Refrigerator, TV, Washing Machine, LED) with daily usage hours.

- **Predict Next Month's Bill**  
  Enter your last 3 months' electricity bill amounts → The app uses **Linear Regression** to forecast the next month's bill and estimated units (based on typical Indian slab rates).

- **Visual Reports & Analysis**  
  - Bar charts, pie charts, scatter plots with regression lines  
  - Daily cost estimation per appliance  
  - Usage distribution and trends

- **ML-Powered Insights**  
  - Identifies high-usage appliances  
  - Predicts potential daily savings by reducing usage  
  - Color-coded visualizations (red for high, green for low)

- **AI Chatbot (Powered by Google Gemini)**  
  Ask questions about energy saving, high bills, appliance efficiency, etc.  
  Fallback to Gemini model for advanced or custom queries.

- **Multiple Tabs/Pages**  
  Clean navigation with sections: Home, Predict Bill, Add Appliance, Usage Report, Analysis, ML Report, Chatbot.

## Screenshots

*(Add actual screenshots here later)*
- Home Page with welcome image
- Predict Bill page with charts
- Analysis page with bar & scatter plots
- ML Report with bar + pie chart
- Chatbot interface

## Requirements

- Python 3.8+
- Required libraries:
  ```bash
  pip install tkinter numpy scikit-learn matplotlib pandas google-generativeai
