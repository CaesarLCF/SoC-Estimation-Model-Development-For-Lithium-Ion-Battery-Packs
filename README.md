# SoC-Estimation-Model-Development-For-Lithium-Ion-Battery-Packs
This project aims to develop a state estimation model for LIB and LiBat systems using both conventional methods, such as the extended Kalman filter (EKF) and unscented Kalman filter (UKF), and data-driven approaches, including backpropagation neural network (BPNN), convolutional neural network (CNN), long short-term memory (LSTM), and gated recurrent unit (GRU). The research will provide a detailed comparison of these SoC estimation methods based on coefficient of determination (R2), mean absolute error (MAE), and root mean square error (RMSE), determining the necessity for implementing data-driven models and the best-performing data-driven model for LIB and LiBat systems in the AMR sector.

1) Collected and pre-processed internal parameter datasets under various operating conditions:
   • Parameters: Terminal Voltage, Open-Circuit Voltage, Load Current, Cell Temperature, and SoC.
   • Battery Types: Li-FP, Li-NMC, Li-NCA, Li-PO, and Li-Ion (Graphite).

2) Developed and Fine-Tuned the Estimation Methods and Models:
   • Model-Based Methods: EKF and UKF.
   • Data-Driven Models: BPNN, CNN, LSTM, and GRU.

3) Evaluated and Benchmarked to Identify the Most Effective SoC Estimation Model:
   • Performance Metrics: MAE, RMSE, and R².
   • Development Factors: Training Time and Number of Parameters/Hyperparameters.
