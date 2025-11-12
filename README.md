
# 🌡️ Branched Broomrape GDD Calculator — California Processing Tomato

An interactive web dashboard for estimating **Growing Degree Day (GDD)** accumulation related to *Branched broomrape (Phelipanche ramosa)* development in California processing tomato.  
The tool visualizes temperature-driven growth stages, provides short-term forecasts, and compares current season data with 5-year historical averages.

---

## 🔍 Features
- 🌎 **Interactive map** for selecting California field locations (Open-Meteo API)  
- 📅 **Custom planting and end date** selection with 16-day forecast  
- 📈 **GDD accumulation chart** with historical comparison  
- 🌱 **Circular gauges** showing broomrape developmental stages  
- 📊 **Table of critical management dates** for decision support  

---

## ⚙️ How to Use
1. Open **`index.html`** in any modern web browser.  
2. Select your **location** from the map or use one of the quick buttons.  
3. Choose a **transplanting date** (and optionally an end date).  
4. Click **“Calculate GDD”** to view current and forecasted GDD trends.  
5. Explore visualizations and management guidance.

---

## 📁 Folder Structure
```

GDD_Calculator/
│
├── index.html                # Main web application
└── images/
└── logo_tomato_broomrape.png

```

---

## 🧠 Model Parameters
The broomrape developmental stages are modeled as temperature-dependent functions using:
- Base temperature = **10 °C (50 °F)**  
- Nonlinear parameters estimated from experimental data in California processing tomato systems.

---

## 👩‍🔬 Author
Developed by **Mesgaran Lab** (UC Davis) — advancing AI and ecological modeling for weed and invasive plant management.

---

## 🌍 License
Released under the **MIT License** — open for academic, research, and extension use with attribution.


