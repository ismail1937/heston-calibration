# Heston Calibration (EUR/USD)

Calibration du modèle d’Heston (θ, σ, ρ, v₀) sur options EUR/USD.  
Pricing semi-analytique/FFT, objectif RMSE, optimisation (Adam + L-BFGS-B).

## Installation
```bash
python -m venv .venv && source .venv/bin/activate
pip install -r requirements.txt
