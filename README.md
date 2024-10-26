# Crime-prediction
Dataset Description:

The data refers to State/UT wise persons arrested under crime against children by crime head. The various crime categories under the crime head are Infanticide, Murder Of Children, Rape Of Children, Kidnapping And Abduction Of Children, Foeticide, Abetment Of Suicide, Exposure And Abandonment, Procuration Of Minor Girls, Buying Of Girls For Prostitution, Selling Of Girls For Prostitution, Prohibition Of Child Marriage Act and Other Crimes Against Children.

Dataset source: data.world

Objective: The goal of this project is to develop a robust predictive model that forecasts future trends in crimes against children. By leveraging historical data and employing a Long Short-Term Memory (LSTM) model, the aim is to predict the future number of arrests across various crime categories related to children.
Model architecture:

Input Layer:

Input Shape: (sequence_length, X.shape[2]) sequence_length: Number of past years (e.g., 5 years) used to predict the next year's crime data. X.shape[2]: Number of crime categories being predicted (features).

2)LSTM Layer:

Units: 50 Activation Function: ReLU ('relu') This layer captures temporal dependencies in the time series data related to crimes against children.

3)Dense Layer:

Units: 1 A fully connected layer that outputs the prediction for the next time step. Output: The model outputs a single prediction for the number of arrests in a specific crime category for the next year. Compilation Details: Optimizer: Adam
By the end of the project, the crime clusters are mapped onto Indian Map.  

