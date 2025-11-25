# SoC-Estimation-Model-Development-For-Lithium-Ion-Battery-Packs
This project aims to develop a state estimation model for LIB and LiBat systems using both conventional methods, such as the extended Kalman filter (EKF) and unscented Kalman filter (UKF), and data-driven approaches, including backpropagation neural network (BPNN), convolutional neural network (CNN), long short-term memory (LSTM), and gated recurrent unit (GRU). The research will provide a detailed comparison of these SoC estimation methods based on coefficient of determination (R2), mean absolute error (MAE), and root mean square error (RMSE), determining the necessity for implementing data-driven models and the best-performing data-driven model for LIB and LiBat systems in the AMR sector. To achieve this, the following objectives must be completed:
1) Collected and Pre-Processed Internal Parameter Datasets Under Various Operating Conditions:
– Parameters: Terminal Voltage, Open-Circuit Voltage, Load Current, Cell Temperature, and SoC.
– Battery Types: Li-FP, Li-NMC, Li-NCA, Li-PO, and Li-Ion (Graphite).
2) Developed and Fine-Tuned the Estimation Methods and Models:
– Model-Based Methods: EKF and UKF.
– Data-Driven Models: BPNN, CNN, LSTM, and GRU.
3) Evaluated and Benchmarked to Identify the Most Effective SoC Estimation Model:
– Performance Metrics: MAE, RMSE, and R².
– Development Factors: Training Time and Number of Parameters/Hyperparameters.

1) Examine existing conventional and data-driven estimation models for SoC estimation in LIB and LiBat systems.
2) Identify and collect relevant datasets for developing the SoC estimation models for LIB and LiBat systems.
3) Develop and optimize SoC estimation models to achieve an R2 greater than 0.8, a MAE less than 10, and a RMSE below 15.
4) Evaluate the accuracy of the optimised SoC estimation models using key metrics such as R², MAE, and RMSE.
5) Identify the best-performing data-driven model, evaluating its necessity for implementation for LIB and LiBat systems in AMR sector based on R², MAE, and RMSE.
