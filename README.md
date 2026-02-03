💻 Supported LaTeX Platforms

This LaTeX project can be compiled and viewed using the following platforms:

Overleaf (Online LaTeX Editor)
🌐 https://www.overleaf.com

(Recommended – no installation required, cloud-based, beginner friendly)

TeX Live (Windows / Linux / macOS)
🌐 https://www.tug.org/texlive/

(Full LaTeX distribution for offline compilation)

MiKTeX (Windows)
🌐 https://miktex.org

(Lightweight and auto-package installer)

MacTeX (macOS)
🌐 https://www.tug.org/mactex/

(Official TeX distribution for macOS)

ShareLaTeX (via Overleaf)
🌐 https://www.sharelatex.com

(Now merged with Overleaf)

Visual Studio Code + LaTeX Workshop Extension
🌐 https://code.visualstudio.com

🔧 Extension: LaTeX Workshop
(Recommended for developers and offline users)

# Hydrological Analysis and Infrastructure Design  
### Rainfall Intensity at Tribhuvan International Airport (2015–2024)

## 📌 Project Overview
This project analyzes **daily rainfall data from Tribhuvan International Airport (TIA), Kathmandu** over a ten-year period (2015–2024) to understand rainfall intensity patterns, extreme events, and their implications for **urban drainage and airport infrastructure design**.

The study emphasizes the **hydrological dominance of extreme rainfall events** and provides **design rainfall thresholds** for resilient stormwater system planning.

---

## 🎯 Objectives
- Classify daily rainfall using **Indian Meteorological Department (IMD)** standards  
- Analyze frequency and volumetric contribution of rainfall intensity classes  
- Identify hydrologically significant **Heavy and Very Heavy rainfall events**  
- Determine **95th and 99th percentile design rainfall values**  
- Support drainage, flood mitigation, and airport infrastructure planning  

---

## 📂 Dataset Description
- **Location:** Tribhuvan International Airport (TIA), Kathmandu Valley, Nepal  
- **Time Period:** 2015 – 2024  
- **Data Type:** Daily rainfall (mm/day)  
- **Total Records:** 3,653 days (including dry days)  
- **Source:** Department of Hydrology and Meteorology (DHM), Nepal  

Dry days (0 mm rainfall) were retained to ensure realistic hydrological assessment.

---

## 🌧️ Rainfall Intensity Classification (IMD Standards)
| Category      | Rainfall Range (mm/day) |
|--------------|-------------------------|
| No Rain      | 0                       |
| Light        | 2.5 – 10                |
| Moderate     | 10 – 35                 |
| Heavy        | 35 – 65                 |
| Very Heavy   | > 65                    |

---

## ⚙️ Methodology
- Data cleaning and validation
- Classification of rainfall into IMD intensity categories
- Frequency and percentage contribution analysis
- Percentile-based extreme rainfall estimation
- Wet and dry spell duration analysis

### Tools Used
- **Python**
  - `pandas`
  - `numpy`
  - `matplotlib`
- **LaTeX** for technical documentation and reporting

---

## 📊 Key Results
- **Heavy & Very Heavy rainfall**
  - Occur on only **15.33% of days**
  - Contribute **over 68% of total rainfall**
- **Maximum 24-hour rainfall:** 166.7 mm  
- **Design rainfall values:**
  - 95th percentile: **66.1 mm/day**
  - 99th percentile: **97.2 mm/day**
- **Average wet spell:** 2.20 days  
- **Average dry spell:** 3.31 days  
- **Annual rainfall trend:** Not statistically significant  

---

## 🏗️ Engineering Implications
- Drainage systems must be designed based on **extreme rainfall**, not averages  
- **95th percentile rainfall** suitable for secondary urban drains  
- **99th percentile rainfall** recommended for primary drainage and airport safety  
- Historical maximum rainfall should be used as a **check flood** for critical infrastructure  
- Implementation of **Sustainable Urban Drainage Systems (SuDS)** is recommended  

---

## 📁 Project Structure

📦 Rainfall-Intensity-TIA
┣ 📜 main.tex
┣ 📜 php.py
┣ 📁 figures
┃ ┣ img_1.png
┃ ┗ figure5_statistical_analysis.png
┣ 📜 README.md


---

## 📚 References
- India Meteorological Department (IMD), *Rainfall Classification Standards*, 2023  
- Chow, V. T., Maidment, D. R., & Mays, L. W., *Applied Hydrology*, McGraw-Hill, 1988  

---

## 👤 Authors
- Kishor Prashad Bhatt  
- Bhawana Karki  
- Aarati Bhatt  
- Asmita Awasthi  
- Jeevan Bhatta  
- Sumit Rokaya  

---

## ⭐ Acknowledgements
This project was prepared as part of the **NSSR Scientific Writing & LaTeX Workshop**.
