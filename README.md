# SoC-Estimation-Model-Development-For-Lithium-Ion-Battery-Packs
This project aims to develop a State of Charge (SoC) estimation model for lithium-ion battery pack systems using both conventional methods and data-driven approaches. The research will provide a detailed comparison of these SoC estimation methods based on their performance metrics and development factors, determining the necessity for implementing data-driven models and the best-performing data-driven model for lithium-ion battery pack systems in the AMR sector. To achieve this, the following objectives must be completed:

1) Examine existing conventional methods such as the extended Kalman filter (EKF) and unscented Kalman filter (UKF), and data-driven approaches, including backpropagation neural network (BPNN), convolutional neural network (CNN), long short-term memory (LSTM), and gated recurrent unit (GRU) for SoC estimation in lithium-ion battery pack systems.

2) Identify and collect relevant internal parameter datasets of Li-FP, Li-NMC, Li-NCA, Li-PO, and Li-Ion Graphite Batteries under various operating conditions. The collected internal parameter datasets including Terminal Voltage, Open-Circuit Voltage, Load Current, and Cell Temperature. Meanwhile, the SoC datasets will be pre-processed through the Coulomb Counting Method.

3) Develop and optimize SoC estimation models by fine-tuning the parameters/hyperparameters to achieve an coefficient of determination (R2) greater than 0.8, a mean absolute error (MAE) less than 10, and a root mean square error (RMSE) below 15. Then, the accuracy of the optimised SoC estimation models will be evaluated using performance metrics of as R², MAE, and RMSE and development factors of developing time and number of parameters/hyperparameters to identify the necessity for implementing data-driven models and the best-performing data-driven model for lithium-ion battery pack systems in the AMR sector. 

# Pre-Processed Internal Parameter Datasets:
1) Li-FP: https://drive.google.com/file/d/1sGcC1O47gPme6iKt8WdfF4Iu0F_xbCK5/view?usp=sharing

2) LI-NMC: https://drive.google.com/file/d/19sk92SagF0IP6pBl42qDQPNfWPF0FGtj/view?usp=sharing

3) Li-PO: https://drive.google.com/file/d/1BE_8xuFxCHwbP18pTP5369PNXEHvMpHd/view?usp=sharing

4) Li-Ion: https://drive.google.com/file/d/1f3V9BbzPpBYM7rrYOd48zW-sjLtVzTqj/view?usp=sharing

5) Li-NCM-NCA: https://drive.google.com/file/d/1VTxeTXvBItdrGtiuHZFEEQJ_LK1WEiq0/view?usp=drive_link
