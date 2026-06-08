# 🚇 Nagpur Metro Rail — Punctuality, Commuter Perception & Urban Mobility

**A statistical research project by BSc Statistics students, Institute of Science, Nagpur (2025–26)**

---

## 📌 Project Overview

This project investigates the **punctuality performance** and **commuter satisfaction** of the Nagpur Metro Rail system, operated by MahaMetro. As one of India's first Tier-2 city metros, Nagpur Metro offers a unique case study in urban mobility for a rapidly growing Indian city.

We combined **primary survey data** (82 commuter responses via Google Forms) with **secondary data** from MahaMetro performance reports, RITES surveys, and DMRC annual reports to build a complete picture of how the metro is performing — and where it can improve.

---

## 🎯 Objectives

- Analyse arrival and delay patterns experienced by Nagpur Metro commuters
- Measure commuter satisfaction and perception of service quality
- Compare Nagpur Metro's punctuality against Delhi Metro and Tokyo Metro benchmarks
- Identify socio-economic impact on different commuter groups
- Provide data-backed recommendations for MahaMetro

---

## 🔍 Key Findings

| Metric | Value |
|--------|-------|
| Survey Responses | 82 valid responses |
| Commuters facing some delay | **73.2%** |
| Most common delay range | 1–5 minutes (46.3%) |
| Mean punctuality rating | **3.83 / 5** |
| Overall satisfaction score | **4.09 / 5 (weighted average)** |
| Commuters rating punctuality Good/Excellent | 67.1% |
| Nagpur Metro punctuality | ~90% |
| Delhi Metro punctuality | ~95% |
| Tokyo Metro punctuality | ~98% |
| Primary commuter group | Students (76.8%) |

> **Key insight:** Despite 73.2% of commuters experiencing delays, overall satisfaction remains high at 4.09/5 — a pattern consistent with "tolerance absorption" in transport research, where reliability and safety outweigh minor delays in commuter perception.

---

## 🛠️ Tools & Methods Used

- **Python** — NumPy, Pandas, Matplotlib, SciPy
- **Excel** — Data cleaning, frequency tables, percentage analysis
- **Statistical Methods** — Mean, Variance, Standard Deviation, Weighted Average, Chi-Square Test, Frequency Distribution

---

## 📊 Statistical Highlights

### Chi-Square Test — Delay vs Gender
```python
from scipy.stats import chi2_contingency

observed = [[19, 52],  # Female: 19 no delay, 52 with delay
            [3,  8]]   # Male:    3 no delay,  8 with delay

chi2, p, dof, expected = chi2_contingency(observed)
# Result: Chi2 = 0.0000, p-value = 1.0000
# Conclusion: Delay experience is INDEPENDENT of gender
```

### Punctuality Rating — Descriptive Stats
```python
import numpy as np

ratings = [1]*3 + [2]*6 + [3]*18 + [4]*30 + [5]*25
# Mean: 3.83 | Variance: 1.12 | Std Dev: 1.06
```

---

## 📁 Repository Contents

| File | Description |
|------|-------------|
| `INSTITUTE_OF_SCIENCE_CORRECTED (3).docx` | Full project report including methodology, analysis, conclusions, and recommendations |

---

## 💡 Recommendations (Summary)

- Increase train frequency during afternoon peak (10 AM–4 PM), which accounts for 51.2% of all travel
- Introduce real-time delay notifications via the MahaMetro app and station display boards
- Improve last-mile connectivity (feeder buses, e-rickshaws) — 46.3% of commuters spend 10–30 minutes just reaching a station
- Adopt predictive maintenance protocols (benchmarked against Delhi Metro) to close the 5–8% punctuality gap

---

## 👥 Team

- Farhin Baig
- Anamika Panday
- Mushira Ansari
- Tinu Dhole

**Guide:** Dr. Pritee Singh, Department of Statistics, Institute of Science, Nagpur

---

## 📚 Data Sources

- MahaMetro Official Performance Report 2022–23
- RITES Comprehensive Mobility Plan for Nagpur
- DMRC Annual Report 2022–23
- Tokyo Metro Annual Report 2022
- Primary Survey (Google Forms, 2025–26)

  
