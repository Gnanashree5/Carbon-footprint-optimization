# Carbon Footprint Optimization in Supply Chain Logistics 🌱🚚

This project uses deep learning to predict carbon emissions from delivery routes and suggest the most eco-friendly option based on factors like distance, cargo weight, traffic levels, weather conditions, and estimated fuel usage.

---

## 📌 Project Overview

In traditional supply chain logistics, cost and delivery time are prioritized, while environmental impact is often overlooked. This project introduces a carbon-aware route optimization system using a supervised deep learning model that predicts CO₂ emissions and suggests routes with minimal environmental footprint.

---

## 💡 Key Features

- Predicts carbon emissions from route data using a neural network.
- Uses realistic input features like fuel usage, cargo weight, and traffic.
- Suggests the greenest route among options.
- Demonstrates environmental trade-offs in route planning.
- Fully runnable in **Google Colab** or local Jupyter Notebook.

---

## 🧠 Model Overview

- Framework: **TensorFlow / Keras**
- Type: **Supervised Regression**
- Architecture: 3-layer feedforward neural network
- Loss Function: Mean Squared Error (MSE)
- Metrics: MAE, RMSE, % Error
- Input Features:
  - Distance (km)
  - Cargo Weight (kg)
  - Traffic Level (0: Low – 3: Heavy)
  - Temperature (°C)
  - Fuel Consumed (litres)
- Output: Predicted CO₂ emissions (kg)

---

## 🛠️ Project Structure

```
carbon-footprint-optimizer/
│
├── carbon_emission_prediction.ipynb   # Main notebook with full workflow
├── README.md                          # Project overview and instructions
└── requirements.txt                   # Python package dependencies
```

---

## 🚀 Getting Started

### 1. Run in Google Colab (Recommended)
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/)

- Open the notebook in Colab
- Click `Runtime > Run All`

### 2. Or Run Locally

#### 🔧 Requirements

```bash
pip install -r requirements.txt
```

#### 📦 Required Packages

```
tensorflow
pandas
numpy
scikit-learn
```

---

## 📈 Sample Workflow

1. **Data Simulation/Collection**
   - Simulated logistics data with variables affecting emissions.
2. **Preprocessing**
   - Normalization, encoding, feature selection.
3. **Model Training**
   - Trains on known emissions using supervised learning.
4. **Evaluation**
   - Uses MAE, RMSE, and % error to assess performance.
5. **Route Suggestion Engine**
   - Predicts emissions for multiple routes and selects the greenest one.

---

## 📊 Sample Output

```
MAE: 2.45 kg CO₂
RMSE: 3.20 kg CO₂
Percentage Error: 6.83%

✅ Recommended Greenest Route:
- Distance: 90 km
- Fuel Used: 13 litres
- Predicted Emission: 35.54 kg CO₂
```

---

## 🌍 Why It Matters

- Helps logistics companies reduce their environmental footprint.
- Supports sustainability goals and carbon compliance reporting.
- Encourages AI-driven green technology adoption in industry.

---

## 🧩 Future Work

- Integrate Google Maps API for real-time route fetching
- Use real GPS + fuel data from fleet management systems
- Add weather forecast APIs and elevation-based adjustments
- Build a full web dashboard for logistics operators

---

## ✨ Acknowledgements

This project was created as part of an academic assignment to explore the integration of AI with sustainability in logistics and transportation.

---
