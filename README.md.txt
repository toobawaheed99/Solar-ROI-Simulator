# Solar PV Performance & ROI Simulator

A Python-based engineering tool designed to estimate the energy yield and financial viability of Grid-Tied Photovoltaic systems.

## Key Features
* **Energy Yield Modeling:** Uses the standard formula $E = P \cdot r \cdot H \cdot PR$ to calculate annual production.
* **Financial Analysis:** Calculates the Payback Period based on installation costs and local utility tariffs.
* **Data Visualization:** Generates a 25-year cash-flow projection using Matplotlib.

## Engineering Formulas Used
The system accounts for a **Performance Ratio (PR) of 0.75**, which covers:
1. Inverter efficiency losses.
2. DC/AC wiring losses.
3. Temperature-related derating.
4. Soiling/Dust factors.

## How to Run
1. Clone the repo: `git clone https://github.com/YOUR_USERNAME/Solar-ROI-Simulator.git`
2. Install dependencies: `pip install matplotlib`
3. Run the script: `python solar_simulator.py`