# Monitoring Forests, Peatlands, and Mangroves in Africa

This project focuses on the monitoring and mapping of **forests, peatlands, and mangroves** across Africa using remote sensing data and machine learning methods. These ecosystems are critical for climate regulation, carbon capture, and coastal protection, yet they remain under-monitored on the continent.

---

## 🌍 Project Objectives
- Monitor the **evolution of peatlands and mangroves** over time.  
- Develop **machine learning models** (e.g., Random Forest, SVM) for mapping and classification.  
- Generate a **map inventory** of mangrove forests and peatlands.  
- Support **real-time monitoring solutions** for conservation efforts.  

---

## 🛠️ Methodology
- Use **satellite imagery** (Landsat, Sentinel-2, GeoMAD).  
- Apply **Random Forest classifiers** for peatland and mangrove detection.  
- Perform **feature importance analysis** and correlation studies.  
- Improve models by incorporating data from more African countries.  

---

## 📂 Project Structure
```
monitoring-forests-peatlands-mangroves-africa/
│
├── data/                   # Shapefiles, imagery samples, training data
│   ├── peatlands/
│   ├── mangroves/
│   └── raw/
│
├── notebooks/              # Jupyter Notebooks for analysis
│   ├── 01_data_preprocessing.ipynb
│   ├── 02_feature_extraction.ipynb
│   ├── 03_random_forest_model.ipynb
│   ├── 04_results_visualization.ipynb
│   └── 05_future_work_experiments.ipynb
│
├── scripts/                # Python scripts for automation
│   ├── preprocessing.py
│   ├── train_model.py
│   ├── evaluate_model.py
│   └── visualization.py
│
├── results/                # Output figures, feature importance charts
│   ├── peatlands/
│   └── mangroves/
│
├── docs/                   # Documentation, reports, references
│   └── literature_review.md
│
├── requirements.txt        # Python dependencies
├── README.md               # Project overview (this file)
└── LICENSE                 # License information
```

---

## 📊 Sample Datasets & Resources
- [Landsat Surface Reflectance](https://github.com/digitalearthafrica/deafrica-sandbox-notebooks/blob/main/Datasets/Landsat_Surface_Reflectance.ipynb)  
- [Sentinel-2](https://github.com/digitalearthafrica/deafrica-sandbox-notebooks/blob/main/Datasets/Sentinel_2.ipynb)  
- [GeoMAD](https://github.com/digitalearthafrica/deafrica-sandbox-notebooks/blob/main/Datasets/GeoMAD.ipynb)  
- [Digital Earth Africa Documentation](https://docs.digitalearthafrica.org/en/latest/data_specs/index.html)  
- [Scalable Machine Learning Examples](https://github.com/digitalearthafrica/deafrica-sandbox-notebooks/tree/main/Real_world_examples/Scalable_machine_learning)  

---

## 👩‍💻 Team Members
- **Fanelesibonge Mbuyazi**  
- Quinta Otieno  
- Felicity Musau  
- Pfano Nemakonde  
- Alhamdulilah Adiza  

---

## 🙏 Special Thanks
We acknowledge the support and resources provided by:  
- **National Research Foundation (NRF)**  
- **South African Radio Astronomy Observatory (SARAO)**  
- **University of Stirling**  
- **DARA (Development in Africa with Radio Astronomy)**  
- **Department of Science and Innovation (DSI)**  
- **Okala**  
- **Digital Earth Africa**  
- **GeoAI Africa**

---

## 🚀 Future Work
- Expand dataset coverage across more African countries.  
- Collaborate with conservation agencies for validation.  
- Explore **deep learning approaches** for improved classification.  
- Integrate with **real-time monitoring systems**.  
=======
# Monitoring Mangroves and Peatlands in Africa

Part of NRF & SARAO (South African Radio Astronomy Observatory) Research

This project focuses on monitoring the evolution of mangroves and peatlands in Africa. It also aims to develop a model to identify areas that have not yet been monitored, contributing to efforts to reduce CO₂ levels and protect the Earth.

---

## Features

- Track the changes and evolution of mangroves and peatlands over time
- Identify unmonitored areas for further observation
- Support environmental research and conservation initiatives

---

## Data

The repository includes:

- KN_Mangroves.geojson – Geospatial data for mangrove locations
- peatlands.geojson – Geospatial data for peatlands
- Mangrove_Analysis.ipynb – Jupyter notebook for analyzing mangrove and peatland data

---

## Objective

- Monitor ecosystem evolution to detect changes over time
- Provide actionable insights for environmental conservation
- Support NRF & SARAO research initiatives and global CO₂ reduction efforts

---

## Usage

1. Clone the repository:
   git clone https://github.com/faneleedison-ux/monitoring-mangroves-peatlands-africa.git
2. Open Mangrove_Analysis.ipynb in Jupyter Notebook or VS Code
3. Run the analysis on the provided geojson datasets
4. Explore and modify the code to adapt to other regions or datasets

---

## Future Work

- Integrate machine learning models to predict unmonitored mangrove and peatland areas
- Include real-time satellite imagery for dynamic monitoring
- Expand to other ecosystems for broader environmental impact

---

## License

This project is open-source and available under the MIT License
>>>>>>> 7cf83b64d3338f4163015ae29bf3d244c59d35a4
