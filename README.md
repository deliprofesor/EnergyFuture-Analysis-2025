# 🌍 Global Energy Transition Analysis (WEO 2025)

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![License](https://img.shields.io/badge/License-CC_BY_4.0-lightgrey?style=for-the-badge)

---

### Project Overview 

This project is an end-to-end data engineering and business intelligence study based on the **IEA World Energy Outlook 2025**. As an Electronics and Communications Engineer, I have developed this platform to analyze global energy supply-demand dynamics, emission trends, and cost-based technological assumptions across various decarbonization scenarios.

---

###  Repository Structure 

* `data/raw/`: Original IEA datasets (CSV, XLSX, XLSB).
* `src/`: Python scripts for ETL (Extract, Transform, Load) processes.
* `notebooks/`: Exploratory Data Analysis (EDA) and visualization drafts.
* `power_bi/`: `.pbix` files and dashboard screenshots.

---

###  Datasets 

| File  | Description |
| :--- | :--- |
| `WEO2025_Free_Dataset.xlsx` | Main global indicators (Supply, Demand, CO2). |
| `World.csv` | Global historical and projected time-series data. |
| `Regions.csv` | Regional energy breakdown and indicators. |
| `Assumptions.xlsb` | Technical & economic assumptions (LCOE, Efficiency). |

---

### ⚖️ License & Attribution

#### English (Legal Notice)
This project utilizes material from the International Energy Agency (IEA). 
* **Ownership:** The OECD/IEA remains the owner of any intellectual property rights in the CC-licensed Content.
* **Attribution:** IEA 2025; World Energy Outlook 2025.
* **Adaptations Disclaimer:** *This is a work derived by **[İlknur_Yılmaz]** from IEA material and **[İlknur_Yılmaz]** is solely liable and responsible for this derived work. The derived work is not endorsed by the IEA or its Member countries in any manner.*

---

### Tech Stack

* **Python (Pandas, Pyxlsb, Openpyxl):** For processing multi-format datasets.
* **Power BI (DAX):** For building interactive energy scenarios and KPI dashboards.
* **Git:** Version control and documentation.



---

###  Getting Started / Başlangıç

1.  Clone the repository: `git clone https://github.com/yourusername/repo-name.git`
2.  Install requirements: `pip install -r requirements.txt`
3.  Run the cleaner script: `python src/data_cleaning.py`
