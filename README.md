📘 Overview

This mini-project uses Machine Learning to predict ocean wave height based on atmospheric and oceanographic variables such as wind speed, wind direction, fetch, and atmospheric pressure.

The objective is to demonstrate how simple ML models can capture fundamental physical relationships in the marine environment—similar to how numerical models (like WaveWatch III – WW3) operate, but in a much faster and more interpretable way.

This project was designed to be:

Quick to build (completed in one day)

Scientifically grounded

Perfect for academic reports and portfolios

Relevant to naval operations and marine forecasting

🎯 Project Goals

Build a synthetic but physically realistic dataset representing ocean conditions

Train two regression models:

Linear Regression

Random Forest Regressor

Compare their performance

Visualize real vs. predicted wave heights

Demonstrate a practical ML workflow applied to the ocean domain

🌬️ Dataset Description

The dataset is generated synthetically using realistic ranges:

Variable	Description	Range
vento_vel	Wind speed (m/s)	2 – 25
vento_dir	Wind direction (degrees)	0 – 360
fetch	Distance wind blows over the water	5 – 300 km
pressao	Atmospheric pressure (hPa)	990 – 1030
altura_onda	Target: wave height (m)	generated

The wave height formula includes:

positive influence of wind speed

positive influence of fetch

slight negative influence of high pressure

random noise to mimic natural ocean variability

🧠 Methodology

Generate a synthetic oceanographic dataset

Split into training (80%) and testing (20%)

Train:

Linear Regression

Random Forest Regressor

Evaluate using:

RMSE

R² score

Plot predictions vs. true values


RMSE

R² score
