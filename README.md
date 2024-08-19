# MSc Dissertation Project - University of Edinburgh in Collaboration with ECFIN

## Overview

Welcome to the GitHub repository for my MSc Dissertation at the University of Edinburgh, developed in collaboration with ECFIN. This project represents the culmination of my research on implementing and evaluating various financial models, with a focus on the Unscented Kalman Filter (UKF) applied to term structure modeling of interest rates and macroeconomic factors.

## Project Summary

The primary objective of this project was to develop a robust framework for estimating parameters of affine term structure models (ATSMs) using the Unscented Kalman Filter. The project encompasses several key components:

- **Data Processing:** Preprocessing and manipulation of economic and financial datasets, including time series data of Euro Area bond yields, inflation, GDP growth, and volatility metrics.
  
- **Model Implementation:** Development and implementation of the UKF to estimate the state variables and parameters of the ATSMs. The codebase integrates the Kalman filter within the broader context of term structure modeling, enabling real-time estimation as new data is available.

- **Parameter Estimation and Optimization:** A comprehensive effort was put into fine-tuning the UKF parameters. This includes implementing 100 iterations of the optimization method, run 100 times, to ensure the stability and accuracy of the parameter estimates.

- **Analysis and Results:** The project includes detailed analysis of the estimation results, discussing the goodness-of-fit metrics, and providing insights into the behavior of the estimated parameters compared to theoretical expectations and previous empirical findings.

## Repository Structure

This repository is organized into several key directories and scripts:

- **`data/`**: Contains all the scripts used for data collection, preprocessing, and transformation.
- **`models/`**: Houses the implementation of the term structure models and the Unscented Kalman Filter.
- **`optimization/`**: Includes scripts for parameter estimation and optimization procedures.
- **`analysis/`**: Scripts and notebooks used for analyzing the results, generating plots, and computing statistical metrics.
- **`results/`**: Contains the output files, including estimated parameters, model diagnostics, and other relevant results.

## Code Summary

- **Lines of Code:** The project contains approximately `X` lines of code, meticulously developed and tested to ensure the reliability and accuracy of the results.
- **Effort:** Significant effort was dedicated to optimizing the performance of the UKF, ensuring that it runs efficiently even with the complexity of the models involved. A single minimization run takes under 3 minutes, showcasing the depth and complexity of the implementation.
- **Development Time:** This project represents months of dedicated work, combining rigorous theoretical research with extensive coding and testing.

## Getting Started

To get started with this repository:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/dissertation-project.git
   ```
2. **Install required packages:**
   Ensure you have all the dependencies installed as listed in `requirements.txt`.
   ```bash
   pip install -r requirements.txt
   ```
3. **Run the models:**
   You can start by running the UKF models found in the `models/` directory. All the necessary configuration files and sample datasets are provided.

4. **Analyze the results:**
   Use the scripts in the `analysis/` directory to reproduce the figures and tables presented in the dissertation.

## Acknowledgements

This project was completed as part of my MSc dissertation at the University of Edinburgh, with the guidance and collaboration of ECFIN. I would like to extend my gratitude to my supervisors and colleagues for their invaluable support throughout this research.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.
