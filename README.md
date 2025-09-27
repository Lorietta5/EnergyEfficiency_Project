# Energy Efficiency Prediction Project

**Author:** Larysa Kholodnytska  
**Email:** lorietta@meta.ua

## Project Overview
This project aims to predict Heating and Cooling Load of buildings based on architectural features and provide 
data-driven recommendations for energy-efficient building design.

## Repository Structure
EnergyEfficiency2/
├── notebooks/
│   ├── EnergyEfficiency_Project.ipynb   # Main notebook with analysis, models, and visualizations
│   └── ENB2012_data.xlsx                # Dataset used for modeling
│
├── data/                                # (optional) additional data
│
├── plots/                               # Saved plots from the notebook
│   ├── heating_distribution.png
│   ├── cooling_distribution.png
│   ├─- feature_importance_heating_load.png
│   ├── feature_importance_cooling_load.png
│
├── results/                             # Stored modeling results
│
├── scripts/                             # Python helper scripts
│
├── use_case_documentation/              # Screenshots of appliedAI Use Case Template
│   ├── Main_Page_1.png
│   └── Main_Page_2.png
│   └── Main_Page_3.png
│   └── Use_Case_Overview.png
│   └── Actors_Stakeholders_1.png
│   └── Actors_Stakeholders_2.png
│   └── Tech_Data.png
│   └── Risk classification.png
│   └── Additional_Notes.png
│   └─  instruction.pdf
│
│
└── README.md

## How to Run
1.	Clone the repository:
2.	git clone https://github.com/lorietta5/EnergyEfficiency2.git
3.	cd EnergyEfficiency2/notebooks
4.	Open EnergyEfficiency_Project.ipynb in Jupyter Notebook / JupyterLab.
5.	Ensure that ENB2012_data.xlsx is located inside the notebooks/ folder.


## Key Findings
- Random Forest outperforms Linear Regression (R² ~ 0.95, RMSE ~2 for Heating Load)
- Top 3 influential features: Overall Height, Relative Compactness, Surface Area
- Practical recommendation: optimize compactness, roof/wall areas, and glazing orientation
