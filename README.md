# STTT
official repository for paper 《LEVERAGING SPATIAL TEMPORAL TRANSFORMER FOR ENHANCED PREDICTION OF TRUCK DEMANDS IN URBAN AREA》


 * To be updated * 

![Heatmap Animation](https://github.com/Perseus1993/STTT/blob/main/n.gif)

# Traffic Volume Prediction using GCN + Transformer

## Project Overview

This project aims to predict the traffic volume in a specific geographic area. The prediction is based on historical traffic data and various other features related to the geographic grid, such as points of interest (POIs), land use, and road capacity.

The model was trained using data from different time periods, and it has been designed to predict traffic volume for future time steps.

## Dependencies

- PyTorch
- osmnx
- moving pandas
- Node2Vec
- Word2Vec

## Usage

To run the prediction model, follow these steps:

```bash
# Clone the repository
git clone https://github.com/Perseus1993/STTT.git

# Navigate into the repository
cd STTT

# Run the model
python main.py
