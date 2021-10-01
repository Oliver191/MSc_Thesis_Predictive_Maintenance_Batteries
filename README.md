# MSc_Thesis_Predictive_Maintenance_Batteries
The GitHub repository accompanying the MSc Thesis at Esade written by Oliver Caspers regarding the topic “Predictive Maintenance for Lithium-Ion Batteries: Predicting the Remaining Useful Life (RUL) using Data-Driven Machine Learning based on Real-World Battery Datasets”.

SNL_Final.ipynb: The main Jupyter Notebook which contains the main code used to load, clean, and transform the SNL data. Four initial models are evaluated and a RF is chosen to be optimized. The RF is trained to predict the RUL on the training data and optimized using the validation data. Finally, the model is tested using independent testing data from UL. The model is used for early and late-stage predictions, PDPs are plotted to judge model behaviour and a predicted RUL threshold is calculated as an example when to replace batteries before they reach their EOL.

Hint: The path in the created variable mypath under the header Data Analysis in the SNL_Final.ipynb has to be adjusted to reflect where and which folder the SNL data is saved.

SNL_Cycle_Timeseries_Data: Folder which contains all the cycle and timeseries data of all 86 cells cycled by SNL. It is available at: https://www.batteryarchive.org/snl_study.html

Pandas Pickle Data: Folder which contains all the saved data in pickle files after the SNL data was modified.

metadata.csv: Contains the metadata for all cells available at batteryarchive.org.

UL-PUR_R20-OV1_18650_NCA_23C_2.5-96.5_0.5-0.5C_a_cycle_data.csv: Contains the cycle data of a randomly selected cell of the UL study which was used as testing data. Also available at batteryarchive.org.

UL-PUR_R20-OV1_18650_NCA_23C_2.5-96.5_0.5-0.5C_a_timeseries.csv: Contains the timeseries data of a randomly selected cell of the UL study which was used as testing data. Also available at batteryarchive.org.

metadata_UL.csv: Contains the metadata of all cells cycled by UL.
