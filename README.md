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
* `Gas_Reservoir_Material_Balance.ipynb` – Interactive Colab notebook with calculations and diagnostic plots.
* `Field_Production_Data.csv` – Field production dataset (Pressure, $G_p$, $W_p$, PVT metrics).
* `Reservoir_Dashboard.pbix` – Power BI interactive dashboard file.

---

## 👤 Author
**Your Name**  
*Petroleum Engineering Candidate*  
[LinkedIn Profile](https://linkedin.com/in/your-profile) | [GitHub Profile](https://github.com/your-username)
