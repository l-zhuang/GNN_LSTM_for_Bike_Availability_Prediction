# Toronto Bike Sharing System Prediction Model

## Abstract
With traffic congestion plaguing Toronto and a growing emphasis on sustainable transportation, bike sharing has emerged as a popular mode of transit. Toronto’s bike sharing program witnessed a record 4.6 million trips in 2022, indicating a significant shift towards eco-friendly mobility. To further optimize this system and address challenges such as bike availability prediction, we propose a robust prediction model leveraging machine learning algorithms and graph networks.

## Project Overview
This project focuses on predicting bike availability across various stations in Toronto's bike sharing network using advanced machine learning techniques. By modeling the bikeshare system as a graph and employing a Graph Attention Network (GAT) with multi-headed attention, followed by LSTM layers to incorporate temporal features, our model aims to provide accurate and scalable predictions. The ultimate goal is to improve trip planning, prevent bike shortages, and enhance the overall efficiency of the sustainable transportation system in Toronto.

## Data Source
The data used in this project is sourced from the City of Toronto’s Open Data Portal:
- **Dataset:** Bike Share Toronto Ridership Data
- **Source:** [City of Toronto Open Data Portal](https://open.toronto.ca/)

## Methodology
### 1. **Graph Attention Network (GAT)**
   - We model the bikeshare system as a graph where each station is represented as a node and the connections (edges) represent the flow of bikes between stations.
   - The GAT model is employed with multi-headed attention to capture the spatial relationships and interactions between different stations.

### 2. **LSTM Layers**
   - To incorporate temporal features, we use LSTM layers following the GAT layers.
   - This allows the model to understand time-based patterns and predict future bike availability more accurately.

### 3. **Model Evaluation**
   - The model's performance is evaluated based on its accuracy in predicting bike availability across different stations.
   - Key metrics include prediction accuracy to generalize across different time periods.

## Further Reading

For a more detailed explanation and insights, you can read our full article on Medium:

[Predicting bike availability at bike share stations in Toronto](https://medium.com/ai4sm/predicting-bike-availability-at-bike-share-stations-in-toronto-preliminary-analysis-cea5d849d631)
