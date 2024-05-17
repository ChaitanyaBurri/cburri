Causality of Airbnb Superhost Status
Backdrop
Airbnb's Superhost certification program distinguishes hosts who provide exceptional service. The criteria for earning Superhost status requires hosts to meet specific standards over the preceding year.
![image](https://github.com/ChaitanyaBurri/cburri/assets/60335511/7d87f262-04b7-49e7-8da2-e90362bb6c05)


Problem Statement:
This project aims to investigate whether having Superhost status on Airbnb influences occupancy rates.


Dataset Overview:
The analysis utilizes Airbnb booking data across eight Superhost evaluation periods between 2016 and 2018. The dataset consists of records from New York with a total of 64,104 rows of data for the periods considered.

Methodology:
To isolate the impact of Superhost status on occupancy, the analysis focuses on properties that nearly missed or just gained Superhost status between two consecutive evaluation periods. The study identifies control (just missed) and treatment (just gained) groups to compare occupancy changes.
![image](https://github.com/ChaitanyaBurri/cburri/assets/60335511/fc542589-693d-40af-bbc2-ecf184113c7e)

![image](https://github.com/ChaitanyaBurri/cburri/assets/60335511/dbdda791-0065-4128-88ed-bcb24456fbce)

After extracting the required set of data, we have determined the treatment and control group for analysis.

Control Group: Properties that just Miss superhost status in period 11 Treatment Group: Properties that just Pass superhost status in period 11

![image](https://github.com/ChaitanyaBurri/cburri/assets/60335511/3ecc3036-f0bd-44a1-a033-08a4a33c065a)

From the initial analysis, we have observed that occupancy rates of treatment group have increased in period 11 compared to period 10
![image](https://github.com/ChaitanyaBurri/cburri/assets/60335511/fbe56961-9203-4454-8ebe-1af2b7dff5e8)


But how much of this increase is caused by ‘Superhost’ status?

So, to further determine the effect of superhost status, we would be performing the following regression analysis:
![image](https://github.com/ChaitanyaBurri/cburri/assets/60335511/869cea5d-e3e4-401e-852f-2c10ed352de0)



Linear Regression Equation with Interaction term:
![image](https://github.com/ChaitanyaBurri/cburri/assets/60335511/7df1ad8a-65d1-4ea7-a7f3-5cea05c874ab)


Superhost Effect:
![image](https://github.com/ChaitanyaBurri/cburri/assets/60335511/0ba5cb8e-bb65-4b52-ab33-5664de702852)


Analysis:
The initial findings suggest an increase in occupancy rates for the treatment group in the latest evaluation period. Further regression analysis with an interaction term will be conducted to quantify the effect of Superhost status on occupancy rates.

