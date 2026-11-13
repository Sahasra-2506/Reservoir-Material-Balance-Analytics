# 🛢️ Gas Reservoir Material Balance & Drive Mechanism Diagnostic Pipeline

A subsurface data pipeline and diagnostic workflow built in Python and Power BI to evaluate gas reserves and model reservoir pressure depletion.

---

## 📌 Project Summary
When estimating Original Gas-in-Place (OGIP), conventional linear $P/Z$ extrapolation assumes a closed reservoir. However, if an active aquifer is present, water encroachment supports reservoir pressure—flattening the $P/Z$ curve and severely overestimating reserves.

This project processes multi-year field production data to evaluate PVT properties, isolate cumulative water influx, and correct reserve estimation errors for better field development planning.

---

## 🛠️ Tech Stack
* **Programming & Analytics:** Python (`pandas`, `numpy`, `scipy`, `matplotlib`) via Google Colab
* **Data Visualization:** Power BI (Dynamic DAX measures, KPI cards, interactive slicers)
* **Engineering Concepts:** Real-Gas PVT ($Z$-Factor, $B_g$, $E_g$), Material Balance ($P/Z$, Havlena-Odeh $F/E_g$)

---

## 🔬 Key Engineering Results
* **Dual-Method Analysis:** Compares uncorrected volumetric $P/Z$ trends against Havlena-Odeh water-drive models.
* **Aquifer Isolation:** Identifies active water-drive support using underground withdrawal calculations ($F$).
* **Reserve Accuracy:** Eliminates a **~35–40% OGIP overestimation** inherent in uncorrected volumetric extrapolation.

---

## 📁 Repository Files

- `MBAL_Project.ipynb` – Jupyter notebook (runs in Google Colab) with PVT calculations, material balance and diagnostic plots.
- `MBAL_Data.csv` – Production dataset (pressure, Gp, Wp, PVT properties).
- `MBAL_Analysis.pbix` – Power BI dashboard with interactive KPIs and slicers.
---

## 
**Pasupuleti Sahasra**  
*Petroleum Engineering Candidate*  
