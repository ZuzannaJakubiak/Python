### Introduction

This repository implements an artificial neural network (ANN) algorithm to predict electricity prices on the Polish Next Day Market (NDM). The goal is to forecast prices 24 hours in advance based on historical data, including trading volumes and time-related features. The ANN model learns from patterns in the data to make accurate predictions for electricity prices.

### Conclusions

1. **Model Performance**: The ANN effectively predicts electricity prices with a notable level of accuracy, showcasing the model's capacity to learn from historical trading data.

2. **Feature Importance**: Time-shifted features, such as previous day's prices and hourly data, play a crucial role in improving the model's predictive capabilities.

3. **Training Efficiency**: The training process, which utilizes backpropagation and an Adam optimizer, demonstrates efficiency in converging towards lower loss values, indicating successful learning.

4. **Visualization Insights**: Visualizing the predicted vs. actual prices enhances the understanding of the model's performance and highlights areas where predictions align well with real values.

5. **Future Improvements**: There is potential for model enhancement by experimenting with different network architectures, hyperparameter tuning, and incorporating additional relevant features to improve prediction accuracy.
