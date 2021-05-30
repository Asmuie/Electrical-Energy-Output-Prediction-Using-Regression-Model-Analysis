# Regression

* **[Combined Cycle Power Plant Data Set](https://archive.ics.uci.edu/ml/datasets/combined+cycle+power+plant#)** : The dataset contains 9568 data points collected from a Combined Cycle Power Plant over 6 years (2006-2011), when the power plant was set to work with full load. Features consist of hourly average ambient variables Temperature (T), Ambient Pressure (AP), Relative Humidity (RH) and Exhaust Vacuum (V) to predict the net hourly electrical energy output (EP) of the plant.
A combined cycle power plant (CCPP) is composed of gas turbines (GT), steam turbines (ST) and heat recovery steam generators. In a CCPP, the electricity is generated by gas and steam turbines, which are combined in one cycle, and is transferred from one turbine to another. While the Vacuum is colected from and has effect on the Steam Turbine, he other three of the ambient variables effect the GT performance.
For comparability with our baseline studies, and to allow 5x2 fold statistical tests be carried out, we provide the data shuffled five times. For each shuffling 2-fold CV is carried out and the resulting 10 measurements are used for statistical testing.
* 
* 
* Using the data provided, I had predict the Energy Output (PE) using regression model below. Finally i compare the r2_score to find the best possible model for this project.
 
  * Multiple Linear Regression
 
  * Polynomial Regression
 
  * Support Vector Regresion (SVR)
 
  * Decision Tree Regression

  * Random Forest Regression
 
By using r2_score method we can evaluate our regression model preformance and compare it with other model. The r2_score show that, with a Random Forest Regression model, we can predict Energy Produced with 96.15% of accuracy. 
 
 **Project Repository:** [Regression](https://github.com/Asmuie/Data-Science-Portfolio/tree/main/Regression)
 
