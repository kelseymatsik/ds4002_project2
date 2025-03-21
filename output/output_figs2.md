# Model Visualizations
## Crime Forecast

![plot1](https://github.com/user-attachments/assets/80dd0da3-611f-4877-ae9a-892e69851fb3)

## Model Seasonality Components 

#### Yearly Seasonality 
Crime slightly plateud around July 2022 but then continued to increase steadily in 2023. Our model predicts that this increase will continue though 2024 to 2026.
<img width="885" alt="Screenshot 2025-03-21 at 10 46 10 AM" src="https://github.com/user-attachments/assets/2d945e27-c2a8-4e4c-b400-c24eb365e959" />

#### Monthly Seasonality 
On an annual cycle, crime tends to peak in early September (students coming back to school) and then fall around October (students leaving for fall break). There is a steep drop in crime beginning in mid-December, and crime counts remain low until they begin increasing again in mid-February. This period of low crime activity corresponds with UVA's winter break.
<img width="889" alt="Screenshot 2025-03-21 at 10 46 40 AM" src="https://github.com/user-attachments/assets/8b1503bf-799f-4188-b21b-b360d63d8062" />

#### Weekly Seasonality
Our model shows sharp increases in crime during the weekend and less crime on Mondays and Fridays. There is moderate crime activity Tuesday through Thursday. 
<img width="888" alt="Screenshot 2025-03-21 at 10 46 28 AM" src="https://github.com/user-attachments/assets/945584d6-e04c-4b4c-80a1-865f99a4b1bd" />

# Model Evaluation 
We trained three Facebook Prophet models to analyze seasonality effects. The results show that the models using Holidays alone and InSession + Holidays produce identical performance metrics (MAE, RMSE, and MAPE). This suggests that adding InSession as an extra regressor does not provide additional predictive value.
Our best and most interpretable model is the one incorporating UVA holidays, which follows the university’s academic calendar (e.g., fall semester, winter break). This finding indicates that UVA's holiday schedule is a key seasonal factor influencing the data.

<img width="331" alt="fig1" src="https://github.com/user-attachments/assets/7fcc7632-2c3e-4381-9624-11f679b2fabe" />

