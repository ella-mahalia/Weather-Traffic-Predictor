Use weather and historical traffic accident data to build a model predicting traffic incident likelihood based on forecasted conditions. This script enables a dataset of traffic accidents with real-time weather data using geographical coordinates. The dataset can be used for analyis, such as understanding the impact of weather conditions on incidents. Optimize the data preprocessing pipeline to handle larger datasets more efficiently 

Key Features 
- Fetches weather data for each incident location using OpenWeatherMAP API.
- Handles API failures by appending default None values when requests fails.
- Outputs a dataset with additional weather-related columns for analysis. 
