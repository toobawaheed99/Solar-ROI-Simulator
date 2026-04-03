# Solar-ROI-Simulator
# This tool provides a deterministic model for estimating the annual energy production and financial viability of a solar PV installation. Unlike basic calculators, this script accounts for systemic derating factors to provide a realistic yield estimate.
# Engineering Specifications:
# The simulation is built on the standard Photovoltaic Performance formula:
# E = P.r.H.PR
# E (Energy):Annual yield in kWh.
# P (Capacity): Peak power of the installed array (kWp).
# r (Yield Ratio): Panel efficiency rating.
# PR (Performance Ratio): A critical engineering constant set to 0.75, accounting for:
#    Inverter/Transformer efficiency
#    Ohmic losses in DC/AC cabling
#    Thermal derating and soiling (dust) factors.
# .FeaturesDynamic ROI Analysis:
# Calculates the "Break-Even" point based on local utility tariffs.
# .Data Visualization: 
# Uses Matplotlib to generate cumulative savings curves over a 25-year lifespan.
# .Sensitivity Input: 
# Allows users to adjust Peak Sun Hours based on geographic location.
