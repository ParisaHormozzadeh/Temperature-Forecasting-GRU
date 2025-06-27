# Forecasting Hourly Temperature: Deterministic vs. Probabilistic Approaches — A Case Study of Mashhad, Iran

This repository contains the source code, data processing scripts, model architectures, and visualizations associated with the research paper:

**"Forecasting Hourly Temperature: Deterministic vs. Probabilistic Approaches — A Case Study of Mashhad, Iran"**  
*Parisa Hormozzade, Alireza Shadman*  

## Background

This work builds upon the previous study:

**"Hourly Temperature Forecasting Using Deep Neural Networks: A Case Study of Mashhad City"**  
In that earlier work, we demonstrated that a GRU-based deep learning model can effectively forecast hourly temperature data for Mashhad using historical weather observations.

In the current study, we extend that foundation by comparing two distinct forecasting strategies:

- A **deterministic approach** using a standard GRU model
- A **probabilistic approach** using a Quantile Regression GRU (Q-GRU), which captures prediction uncertainty via conditional quantiles (e.g., P10, P50, P90)

The goal is to assess not only the accuracy of the forecasts but also the models' ability to quantify uncertainty in temperature predictions.

## Repository Structure


## Dataset

- **Region**: Mashhad, Iran  
- **Time Period**: 2015 to 2021  
- **Temporal Resolution**: 3-hourly observations  
- **Target**: Air temperature (°C)  
- **Features**: Temperature, humidity, wind direction, solar radiation, etc.

*Note: Due to licensing restrictions, the dataset is not included in this repository.*
