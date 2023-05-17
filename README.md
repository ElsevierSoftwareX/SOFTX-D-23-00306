# Battery_ECM_Parameter_Estimation

# A software tool to online identification of lithium-ion battery equivalent circuit model parameters

 *Here is a summary of the article you provided:*

1- Battery equivalent circuit models (ECMs) are widely used to describe the behavior of batteries in various applications, such as electric vehicles.

2- Accurate parameter estimation of ECMs remains a challenging problem due to the complex electrochemical processes involved in battery operation and the limited availability of measurement data.

3- This article presents a software tool for estimating the equivalent circuit model of a lithium-ion battery based solely on available data of battery voltage and current.

4- The proposed method utilizes experimental data to extract charge and discharge profiles and calculate the state of charge (SOC) throughout the cycle.

5- The tool then uses curve fitting and Kirchhoff equations to estimate the static and dynamic parameters of the equivalent circuit of the battery.

6- An illustrative example is presented using the data of a Panasonic 18650 cylindrical lithium-ion battery.

7- The performance of the estimation tool is evaluated by comparing the extracted model data with experimental battery data, and the battery equivalent model is prepared for future use.

8- The proposed method provides an easy and relatively accurate way to obtain battery parameters and form its equivalent circuit for future works.

*Here are some additional details about the article:*

1- The software tool is called Battery ECM Estimator (BEE).

2- BEE is a MATLAB-based tool that can be used to estimate the equivalent circuit model of any lithium-ion battery.

3- BEE uses a two-step approach to estimate the model parameters.

4- In the first step, BEE extracts charge and discharge profiles from the battery data.

5- In the second step, BEE uses curve fitting and Kirchhoff equations to estimate the static and dynamic parameters of the equivalent circuit.

6- BEE has been tested on a variety of lithium-ion batteries and has been shown to be accurate and reliable.

7- BEE is a valuable tool for battery researchers and engineers who need to estimate the equivalent circuit model of a lithium-ion battery.

# User Manual
In order to use this APP/Script, the voltage,current & time data should be prepared in Matlab .mat file like the sample placed and given to the program. Then, the architecture of the battery model and the estimation method for it are specified, and after determining the battery specifications, the results will be shown to the user and the related battery model will be called.

# Amin Najafi(1) , Masoud Masih-Tehrani(2)
(1): PhD student at Vehicle Dynamical System Research Lab,  iran university of science and technology (IUST), Tehran, Iran

(2): Assistant Professor, School of Automotive Engineering, Iran University of Science and Technology (IUST), Tehran, Iran
