# Belgium Rail Network EDA

## Overview
This project explores the General Transit Feed Specification (GTFS) data for Belgium's rail network (operated by NMBS/SNCB) using Python for exploratory data analysis (EDA) and visualizations. The goal is to analyze rail routes, stops, and schedules, creating insights and maps for better understanding the transit system.

## Requirements
- Python 3.8 or higher
- Required packages (install via `pip install -r requirements.txt`):
  - pandas
  - matplotlib
  - seaborn
  - geopandas
  - folium
  - jupyter

## Setup
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/belgium-rail-gtfs.git
   cd belgium-rail-gtfs
   ```

2. Create a virtual environment:
   ```bash
   python -m venv venv
   venv\Scripts\activate
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Ensure you have the GTFS data files (stops.txt, routes.txt, etc.) in the data/ folder.

## Usage
- Open eda.ipynb in VS Code or Jupyter to run the exploratory analysis and visualizations.
- Modify scripts/notebooks as needed for deeper analysis.