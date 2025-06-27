# Forecasting Hourly Temperature: Deterministic vs. Probabilistic Approaches — A Case Study of Mashhad, Iran

This repository contains the source code, data processing scripts, model architectures, and visualizations associated with the research paper:

**"Hourly Temperature Forecasting Using Deep Neural Networks: A Case Study of Mashhad City"**  
*Parisa Hormozzade, Alireza Shadman*  
Presented at the **10th International Conference on Industrial and Systems Engineering**, 2025.

## Overview

This study evaluates the effectiveness of deep learning models for short-term temperature forecasting. Two approaches are compared:

- **Deterministic GRU Model**: A standard Gated Recurrent Unit (GRU) network that provides single-point temperature forecasts.
- **Probabilistic GRU Model (Quantile GRU)**: A quantile regression-based GRU model that estimates multiple conditional quantiles (e.g., P10, P50, P90), enabling the generation of prediction intervals and uncertainty quantification.

Both models are trained and evaluated on historical weather data for the city of Mashhad, Iran.

## Repository Structure

@article{hormozzade2025forecasting,
  title     = {Hourly Temperature Forecasting Using Deep Neural Networks: A Case Study of Mashhad City},
  author    = {Parisa Hormozzade and Alireza Shadman},
  conference = {10th International Conference on Industrial and Systems Engineering},
  year      = {2025}
}

