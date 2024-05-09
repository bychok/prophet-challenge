![A conceptual image representing data analysis and forecasting in e-commerce](MercadoLibre_Predictions.webp)

# MercadoLibre Search Trend Forecasting

## Table of Contents

1. [Introduction](#introduction)
2. [Data](#data)
3. [Forecasting Model](#forecasting-model)
4. [Results and Discussion](#results-and-discussion)

## Introduction

This project focuses on analyzing and forecasting search trends for MercadoLibre using the Prophet time series forecasting tool. The goal is to understand search pattern dynamics over time and predict future trends which can assist in strategic business decisions and marketing.

## Data

The dataset includes hourly search trends data from MercadoLibre, structured to reflect various metrics of search intensity over several years. The data has been manipulated to fit the requirements of the Prophet model, involving preprocessing steps such as setting the datetime index and handling missing values.

## Forecasting Model

We employ Facebook's Prophet forecasting model, which is robust to missing data and shifts in the trend, and typically works well with daily periodicity data. The model settings have been tailored to capture the seasonality and trends accurately.

## Results and Discussion

### Data Insights

- **Trend Analysis**: The trend component revealed a generally increasing trend in Google search activity over the years, suggesting a growing interest in MercadoLibre's offerings. Notably, there was a sharp increase around 2020, possibly linked to the COVID-19 pandemic, which accelerated online commerce activities.

- **Seasonality Insights**:
  - **Weekly Trends**: Tuesday emerged as the peak day for search activities, indicating heightened user engagement at the start of the week. This might be used to time marketing campaigns or promotional activities to maximize visibility and engagement.
  - **Yearly Trends**: There was a noticeable dip in search activities at the beginning of each year, particularly in January, which could reflect a post-holiday slowdown. This period might be optimal for planning and implementing new strategies or maintenance tasks.
  - **Daily Trends**: Searches peaked around 8:30 PM to midnight, suggesting that evenings are when most users are active on MercadoLibre. This insight can guide the scheduling of live events, auctions, or special promotions to capture the maximum audience.

### Forecasting and Predictions

The forecasting model predicted a slight decline in search trends immediately following a recent peak, likely indicating a transient correction after a surge. The predictions also included uncertainty intervals which widened over time, reflecting growing unpredictability in long-term forecasts.

### Concluding Thoughts

This analysis has provided crucial insights into the search behavior on MercadoLibre, underlining the importance of temporal dynamics in e-commerce. Going forward, continually updating the forecasting models with new data and refining the predictions will be key to staying ahead in a competitive landscape.

The detailed component analysis from Prophet also highlights the model's robustness in handling different types of seasonality, making it a valuable tool for similar analyses in other domains or platforms.
