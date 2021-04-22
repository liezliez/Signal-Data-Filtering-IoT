# Signal-Data-Filtering-IoT
Removing Noises from Raw Gait Angle Data Signal using LPF or MVA method

# What is it?
In this code, im implementing a Lowpass Filter and Moving Average Filter to remove unwanted signal/noise from combination of Data Accelerometer  
and Gyroscope Sensor from a Smartphone to Exclude erroneous or "bad" observations for better analysis Gait Angle Result.

# Collecting The Data
My method to collecting the data is using an app "Phyphox" while the Smartphone is tied to the Subject ankle
![image](https://user-images.githubusercontent.com/42132479/115753867-d9080b80-a3c5-11eb-8e14-bc8a7062368d.png)

To retrieve gait data using a smartphone, make sure the subject were in
conditions walking straight constantly at a speed of about 1.5 m/s - 1.75 m/s

The Data From Phyphox

![image](https://user-images.githubusercontent.com/42132479/115754223-2edcb380-a3c6-11eb-8340-27257f76ddf2.png)

# How to  
Import your Phypox Accelerometer and Gyroscope data and then Use the .csv file for the input dataset
i also provide dataset example on this project. use the 13.csv file inside this repositories
