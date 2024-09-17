# Geospatial Data Science - Final Project

**Authors**: Alejandro Zimmerman, Dino Toskic, Raúl Villacorta  
**Date**: March 28, 2024

## Introduction

This project studies the effects of entry and exit on diesel prices in the retail market in Madrid. It is inspired by the methodology used in the FTC v. Staples case to measure the effects of market structure on prices, as summarized by Baker (1999). The analysis utilizes a **price-concentration regression** to estimate the impacts of market structure changes on prices, focusing specifically on competitors' entry and exit within the catchment areas around gas stations.

## Key Methodology

We use a **panel dataset** and an **instrumental variables approach** to address the endogeneity of entry and exit in gas stations' catchment areas, similar to Perdiguero & Borrell (2019). Our catchment areas are defined as a **7-minute driving distance** around each gas station, and we use the number of competitors within and outside the catchment area as key variables.

## Dataset

The dataset used in this project is **Daily Prices for Spanish Gas Stations (2007-2023)**, compiled by **mauriciy** and available on [Kaggle](https://www.kaggle.com/datasets/mauriciy/daily-spanish-gas-prices/data). It includes daily price submissions from gas stations, as required by Spanish law since 2007. The analysis is based on monthly price data, using the first day of each month to reduce redundancy.
