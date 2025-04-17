# Interactive Simple Climate Model

This repository contains a simple Python-based climate model demonstrating the near-term future effects of CO2 emissions, climate sensitivity, and aerosol masking, implemented in a Google Colab notebook. The model uses `ipywidgets` and `Plotly` for interactive exploration.

## Model Overview

The model simulates two scenarios:
1.  **Business-as-Usual (BAU):** CO2 increases exponentially, and aerosols/masking are generated based on the rate of CO2 increase (capped after 2015).
2.  **World Without Us (WWU):** A divergent scenario starting when BAU CO2 hits 400 ppm. All human CO2 emissions and aerosol production stop instantly. CO2 levels slowly decay towards a new equilibrium, while aerosols disappear immediately.

The key uncertainties you can explore interactively are:
*   **Climate Sensitivity (ΔT_2x):** The equilibrium temperature change (°C) for a doubling of CO2 (relative to 280 ppm).
*   **Present-Day Aerosol RF:** The estimated cooling effect (in W/m²) of industrial aerosols and other short-lived pollutants around the year 2015.

## How to Run Interactively

The easiest way to run this interactive notebook is using Google Colab or Binder:

*   **Using Google Colab:** (Recommended, as the notebook was developed here)
    [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Binamraaa/climate-near-future/blob/main/Climate_Model_Future_Days.ipynb)
    *(Click the badge above. You'll need a Google account. Run all cells, including the one enabling the custom widget manager.)*

*   **Using Binder:**
    [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/Binamraaa/climate-near-future/HEAD?filepath=Climate_Model_Future_Days.ipynb)
    *(Click the badge above! Note: Binder can take a few minutes to build the environment the first time. If plots don't appear interactive, you might need to adjust the Plotly renderer setting in the notebook code to `'notebook'` or `'notebook_connected'` and push the change.)*

## Dependencies

Listed in `requirements.txt`.
