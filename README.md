# 🌌 NGC 6397: Age Estimation Using Gaia Data

Final project for PHYS 216 (Astrophysics) at Queen’s University. This project analyzes the globular cluster **NGC 6397** using observational data from ESA’s Gaia space telescope to estimate its age and examine its stellar structure.

---

## 📁 Contents

- `EDA.ipynb` – Jupyter notebook with all data cleaning, analysis, and visualization steps
- `NGC6397_Analysis.pdf` – Full report detailing calculations, scientific context, and key findings

---

## 🔍 Overview

- Queried and extracted **66K+ stellar records** from the Gaia Archive
- Filtered based on **parallax**, **distance**, and **proper motion**
- Constructed **Color-Magnitude Diagrams (CMDs)** to visualize stellar evolution
- Estimated the cluster’s age using both:
  - **Main Sequence Turnoff (MSTO)**
  - **Tip of the Red Giant Branch (TRGB)**
- Compared derived age to NASA’s official value and analyzed sources of error

---

## 🛠 Tools & Techniques

- **SQL / ADQL** for Gaia data extraction  
- **Python**: `pandas`, `numpy`, `matplotlib`, `seaborn`  
- CMD construction, distance modulus, and astrophysical filtering  
- Error analysis and result validation

---

## 📎 References

- [ESA Gaia Archive](https://gea.esac.esa.int/archive/)
- NASA, ESA, and peer-reviewed publications (linked in report)

---

## 🚀 Future Improvements

- Isochrone fitting for enhanced age precision  
- Filtering based on proper motion clustering and photometric error margins  
