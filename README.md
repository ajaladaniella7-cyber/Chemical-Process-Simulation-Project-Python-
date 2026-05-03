# Chemical-Process-Simulation-Project-Python-
# Flash Drum VLE Simulator (Benzene–Toluene)

## Overview
This project models vapor-liquid equilibrium (VLE) in a flash drum using a binary mixture of benzene and toluene.

The simulator predicts:
- Vapor fraction 
- Liquid fraction
- Vapor composition
- Liquid composition

An interactive web application was built using Streamlit to allow users to adjust temperature, pressure, and feed composition.


## Features
- Flash drum simulation for benzene–toluene system
- Numerical solver using SciPy (`fsolve`)
- Phase stability checks (all-liquid, all-vapor, two-phase)
- Sensitivity analysis (temperature vs vapor fraction)
- Interactive Streamlit web app

---

## Technologies Used

- Python
- NumPy / SciPy
- Matplotlib
- Streamlit

---

## How to Run

### 1. Install dependencies
```bash
pip install scipy matplotlib streamlit
