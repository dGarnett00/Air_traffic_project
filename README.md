# Air Traffic Data Analysis

This project analyzes air traffic passenger and landing statistics using Python, pandas, and visualization libraries. It also demonstrates how to enrich analysis with real-time data from the OpenSky Network API.

## Project Structure

- `data/` — Contains all dataset CSV files
- `notebooks/` — Contains the main Jupyter notebook (`traffic.ipynb`)

## Setup Instructions

1. Clone the repository:
   ```
   git clone https://github.com/dGarnett00/Air_traffic_project.git
   cd Air_traffic_project
   ```
2. Create and activate a virtual environment (Windows):
   ```
   python -m venv .venv
   .venv\Scripts\activate
   ```
   Or (macOS/Linux):
   ```
   python3 -m venv .venv
   source .venv/bin/activate
   ```
3. Install requirements:
   ```
   pip install -r requirements.txt
   ```
4. Launch Jupyter and open the notebook:
   ```
   jupyter notebook notebooks/traffic.ipynb
   ```

## Data Sources
- [Air Traffic Passenger Statistics](data/Air_Traffic_Passenger_Statistics.csv)
- [Air Traffic Landings Statistics](data/Air_Traffic_Landings_Statistics.csv)
- [OpenSky Network API](https://opensky-network.org/apidoc/index.html)

## Main Questions
- Which airlines have the highest passenger counts and landings?
- What trends or patterns are visible in the data?
- How can real-time data from OpenSky enhance the analysis?

## Acknowledgements
- pandas, matplotlib, seaborn, requests
- OpenSky Network for API access

## License
MIT License
