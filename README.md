# Kerala Flood Supplementary Material – MSc Thesis
Code and notebooks for MSc thesis on the 2018 Kerala Floods

This repository contains the Python Jupyter Notebooks used for data processing and analysis in the MSc thesis titled:

**"Climatic and Atmospheric Drivers of the 2018 Kerala Flood: A Synoptic-Scale Perspective using ERA5 Reanalysis"**

## 📂 Contents

| File Name                     | Description                                                                 |
|------------------------------|-----------------------------------------------------------------------------|
| `Daily averages.ipynb`       | Calculates daily total rainfall, wind and MSLP from hourly ERA5 and ERA5-Land data                  |
| `daily Vs climatology.ipynb` | Compares daily anomlaies in August 2018 with 1979–2017 climatology           |
| `wind speed and direction.ipynb` | Computes and visualizes 850 hPa wind speed and direction, comparison of flood period vs climatology |
| `vertical motion(Omega).ipynb`   | Analyzes vertical motion (omega) at 500 hPa to detect convection potential |
| `MJO.ipynb`                  | Extracts and visualizes MJO phase data (RMM index)                          |
| `IOD.ipynb`                  | Plots Indian Ocean Dipole using DMI values                                 |
| `ENSO.ipynb`                 | Analyzes ENSO (Niño 3.4 SST anomalies) using ERSSTv5 data                   |

## 📦 Requirements

These notebooks use the following Python libraries:

- xarray
- numpy
- pandas
- matplotlib
- cartopy
- seaborn
- cdsapi (for ERA5 downloads)

Install them via pip:

```bash
pip install xarray numpy pandas matplotlib cartopy seaborn cdsapi
