## Flood Inundation Mapping (FIM) Enhancement Using Surrogate Modeling
The Surrogate Modeling (SM) is a U-Net based convolutional architecture that leverages the hybrid approach of integrating Low-Fidelity Physics Based (LFPB) and Response Surface Surrogate. It couples the LF-FIMs generated from the Operational NOAA Office of Water Prediction (OWP) Height Above Nearest Drainage (HAND) model as baseline, and integrates additional topographic and hydrologic forcings to enhance accuracy and improve agreement with higher-fidelity inundation products derived from Numerical Modeling.

## Usage Notes

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1tZkvFkA-35011SbrmIh_6PMXO0ZvHJSF?usp=sharing)

User can directly open the notebook in Google Colab and run it interactively.

To setup in the local machine:

- Setup virtual environment and install `fimserve[sm]` to run locally — follow the instructions here:
  https://github.com/sdmlua/FIMserv#tool-usage

### Citing This Tool
Anupal Baruah, Supath Dhital, Sagy Cohen, et al. **FIMserv v.1.0: A Tool for Streamlining Flood Inundation Mapping (FIM) Using the United States Operational Hydrological Forecasting Framework**. *Environmental Modelling & Software*, **Volume 192**, 2025, 106581. [https://doi.org/10.1016/j.envsoft.2025.106581](https://doi.org/10.1016/j.envsoft.2025.106581)

