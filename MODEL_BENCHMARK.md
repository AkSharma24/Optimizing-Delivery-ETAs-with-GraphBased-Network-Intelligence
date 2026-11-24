MODEL_BENCHMARK
--------------------------------------------------------------------------------
OSRM-Baseline
--- Trip-Level ETA Performance ---
Total Unique Trips Evaluated: 14817
Percentage of trips where ETA is within actual_time ±15%: 2.88%
--------------------------------------------------------------------------------
--------------------------------------------------------------------------------
Linear Regression
--- Model Performance on Pre-Split Test Data ---
R² Score (Variance Explained): 0.1154
Mean Absolute Error (MAE): 14.6936
Root Mean Squared Error (RMSE): 52.8418
--- Trip-Level ETA Performance ---
Total Unique Trips Evaluated: 4163
Percentage of trips where ETA is within actual_time ±15%: 37.50%
--------------------------------------------------------------------------------
--------------------------------------------------------------------------------
Random Forest
R² Score: 0.3751
Mean Absolute Error (MAE): 14.54 minutes
Root Mean Squared Error (RMSE): 44.41 minutes

--- Random Forest Trip-Level Performance ---
Total Unique Trips Evaluated: 4163
Percentage of trips where ETA is within actual_time ±15%: 35.82%
cutoff_factor:0.07908
actual_distance_to_destination:0.10493
osrm_time:0.14748
osrm_distance:0.16701
segment_osrm_distance:0.40088
actual_distance_to_destination:0.10062
--------------------------------------------------------------------------------
--------------------------------------------------------------------------------
XGBoost Baseline
R² Score: 0.3022
Mean Absolute Error (MAE): 14.69 minutes
Root Mean Squared Error (RMSE): 46.93 minutes

--- XGBoost Trip-Level Performance ---
Total Unique Trips Evaluated: 4163
Percentage of trips where ETA is within actual_time ±15%: 36.90%
--------------------------------------------------------------------------------
--------------------------------------------------------------------------------
////////////////////////////////////\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\
\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\////////////////////////////////////////////
GRAPH-BASED APPROACH
--------------------------------------------------------------------------------
Node2vec Approach
--- Graph-Enhanced XGBoost Trip-Level Performance ---
R² Segment Score: 0.4936
Segment MAE: 12.51 minutes
Percentage of trips within ±15% window: 47.03%
--------------------------------------------------------------------------------
--------------------------------------------------------------------------------
--- GraphSAGE Evaluation Metrics ---
Segment R² Score: 0.4395
Segment Mean Absolute Error (MAE): 14.89 minutes
Total Evaluated Unique Trips: 4107
Trip-Level Accuracy (Within ±15% Window): 40.44%
--------------------------------------------------------------------------------
--------------------------------------------------------------------------------
