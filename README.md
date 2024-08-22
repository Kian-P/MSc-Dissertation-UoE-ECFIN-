# MSc Dissertation Project - University of Edinburgh in Collaboration with ECFIN

## Overview

Welcome to the GitHub repository for my MSc Dissertation at the University of Edinburgh, developed in collaboration with ECFIN. This project represents the culmination of my research on implementing and evaluating various financial models, with a focus on the Unscented Kalman Filter (UKF) applied to term structure modeling of interest rates and macroeconomic factors.

## Project Summary

The primary objective of this project was to develop a robust framework for estimating parameters of affine term structure models (ATSMs) using the Unscented Kalman Filter. The project encompasses several key components:

- **Data Processing:** Preprocessing and manipulation of economic and financial datasets, including time series data of Euro Area bond yields, inflation, GDP growth, and volatility metrics.
  
- **Model Implementation:** Development and implementation of the UKF to estimate the state variables and parameters of the ATSMs. The codebase integrates the Kalman filter within the broader context of term structure modeling, enabling real-time estimation as new data is available.

- **Parameter Estimation and Optimization:** A comprehensive effort was put into fine-tuning the UKF parameters. This includes implementing 100 iterations of the optimization method, run 100 times, to ensure the stability and accuracy of the parameter estimates.

- **Analysis and Results:** The project includes detailed analysis of the estimation results, discussing the goodness-of-fit metrics, and providing insights into the behavior of the estimated parameters compared to theoretical expectations and previous empirical findings.

## Code Summary

- **Lines of Code:** The project contains approximately `5000` lines of code, meticulously developed and tested to ensure the reliability and accuracy of the results.
- **Effort:** Significant effort was dedicated to optimizing the performance of the UKF, ensuring that it runs efficiently even with the complexity of the models involved. A single minimization run takes under 3 minutes, showcasing the depth and complexity of the implementation.
- **Development Time:** This project represents months of dedicated work, combining rigorous theoretical research with extensive coding and testing.

## Acknowledgements

This project was completed as part of my MSc dissertation at the University of Edinburgh, with the guidance and collaboration of ECFIN. I would like to extend my gratitude to my supervisors for their invaluable support throughout this research.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.
