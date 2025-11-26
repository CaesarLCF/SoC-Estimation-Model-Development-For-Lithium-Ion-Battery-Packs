# SoC-Estimation-Model-Development-For-Lithium-Ion-Battery-Packs
1) This project aims to develop a State of Charge (SoC) estimation model for lithium-ion battery pack systems using both conventional methods, such as the extended Kalman filter (EKF) and unscented Kalman filter (UKF), and data-driven approaches, including backpropagation neural network (BPNN), convolutional neural network (CNN), long short-term memory (LSTM), and gated recurrent unit (GRU). 

2) The internal parameter datasets of Li-FP, Li-NMC, Li-NCA, Li-PO, and Li-Ion Graphite Batteries under various operating conditions will be collected. The collected internal parameter datasets including Terminal Voltage, Open-Circuit Voltage, Load Current, and Cell Temperature. Meanwhile, the SoC datasets will be pre-processed through the Coulomb Counting Method.

3) The research will provide a detailed comparison of these SoC estimation methods based on the performance metrics of coefficient of determination (R²), mean absolute error (MAE), and root mean square error (RMSE) and development factors of developing time and number of parameters/hyperparameters to determine the necessity for implementing data-driven models and the best-performing data-driven model for lithium-ion battery pack systems in the AMR sector. 

# Pre-Processed Internal Parameter Datasets:
• Li-FP (A123): https://drive.google.com/file/d/1sGcC1O47gPme6iKt8WdfF4Iu0F_xbCK5/view?usp=sharing

• LI-NMC (LG): https://drive.google.com/file/d/19sk92SagF0IP6pBl42qDQPNfWPF0FGtj/view?usp=sharing

• Li-PO (Turnigy Graphene): https://drive.google.com/file/d/1BE_8xuFxCHwbP18pTP5369PNXEHvMpHd/view?usp=sharing

• Li-Ion (Samsung): https://drive.google.com/file/d/1f3V9BbzPpBYM7rrYOd48zW-sjLtVzTqj/view?usp=sharing

• Li-NCM-NCA (SB LiMotive): https://drive.google.com/file/d/1VTxeTXvBItdrGtiuHZFEEQJ_LK1WEiq0/view?usp=drive_link
