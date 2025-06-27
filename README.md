# Product-Demand-forecasting

# 📦 Product Demand Forecasting App

A machine learning-powered web app that predicts future product demand based on various market and product factors. Built with Python, Scikit-learn, and deployed using Gradio.

---

## 🚀 Features

- Predicts demand using a trained Random Forest model
- Easy-to-use web interface with dropdowns and sliders
- Inputs include product category, sales history, promotions, economic indicators, and market trends
- Live predictions without needing to write code
- Clean, customized UI with no Gradio branding

---

## 🧠 ML Model Details

- **Model Used**: Random Forest Regressor
- **Target Variable**: `predicted_demand_units`
- **Training Features**:
  - Product Category
  - Historical Sales
  - Seasonality Level
  - Promotional Activity
  - Economic Index
  - Market Trend Score

---

## 📊 Input Fields (via Gradio)

| Feature                | Type        | Description |
|------------------------|-------------|-------------|
| Product Category       | Dropdown    | Product type (Electronics, Furniture, Toys) |
| Historical Sales       | Number      | Total past sales for the product |
| Seasonality            | Dropdown    | High, Medium, or Low seasonal demand |
| Promotional Activity   | Dropdown    | Whether promotion is active (Yes/No) |
| Economic Index         | Number      | Score indicating current economic strength |
| Market Trend Score     | Number (0–1)| Score indicating market favorability |

---
