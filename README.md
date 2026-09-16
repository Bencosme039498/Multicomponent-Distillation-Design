# ⚗️ Multicomponent Distillation Design — Python Engineering Analysis

Python-based chemical engineering project developed to perform preliminary design calculations for the separation of a multicomponent hydrocarbon mixture using a distillation column.

## 🔎 Project Overview

This project applies Python and numerical methods to a multicomponent distillation design problem involving a hydrocarbon mixture containing methane, ethylene, ethane, propane, butane, and hexane.

The analysis evaluates key thermodynamic and design parameters required for the preliminary sizing and operation of a distillation column.

## 🎯 Engineering Objectives

The project was designed to:

- Determine distillate dew-point temperature
- Determine residue bubble-point temperature
- Calculate relative volatilities for the mixture components
- Evaluate component distribution between distillate and residue
- Determine the thermodynamic condition of the feed
- Calculate vapor fraction at feed conditions
- Estimate the minimum reflux ratio
- Calculate the minimum number of theoretical stages
- Estimate the actual number of theoretical stages
- Determine the approximate feed-stage location

## 🛠️ Tools & Libraries

- **Python** — Engineering and numerical programming
- **NumPy** — Array operations, mathematical calculations, and numerical processing
- **SciPy** — Nonlinear equation solving using `scipy.optimize.fsolve`
- **Chemical Engineering Methods** — Vapor-liquid equilibrium and distillation design calculations

## 🧮 Methodology

The analysis begins with the feed composition and specified distillate and residue compositions.

Temperature-dependent equilibrium constants are calculated for the hydrocarbon components and used to determine dew-point and bubble-point conditions.

Relative volatilities are then calculated and used in subsequent separation calculations.

The computational workflow includes:

1. Calculation of vapor-liquid equilibrium constants
2. Dew-point and bubble-point estimation
3. Relative volatility calculations
4. Component distribution analysis
5. Feed thermodynamic condition evaluation
6. Numerical solution of vapor fraction using `fsolve`
7. Minimum reflux ratio calculation
8. Minimum theoretical stage estimation
9. Actual theoretical stage estimation
10. Feed-stage location estimation

## 🔢 Numerical Methods

SciPy's `fsolve` is used to solve nonlinear equations involved in the calculation of:

- Feed vapor fraction
- Minimum reflux conditions

NumPy is used throughout the project for array-based calculations, mathematical operations, and processing the properties of the multicomponent mixture.

## 💡 Skills Demonstrated

This project demonstrates the application of programming to chemical engineering design and quantitative problem-solving, including:

- Python programming
- NumPy
- SciPy
- Nonlinear equation solving
- Numerical analysis
- Thermodynamic calculations
- Vapor-liquid equilibrium
- Multicomponent distillation
- Process engineering calculations

## 📁 Project Files

- `multicomponent_distillation_design.py` — Python script containing the thermodynamic and distillation design calculations.
- `distillation-design-problem-statement.pdf` — Original engineering problem statement used as the basis for the analysis.

## 👥 Authors

**Erny Encarnacion & Juan Alejandro Bencosme Diaz**

## 👤 Portfolio

**Juan Alejandro Bencosme Diaz**  
Data Analyst | Power BI | Python | Chemical Engineering Background
