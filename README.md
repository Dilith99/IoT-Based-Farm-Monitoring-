Name  : Wijethilake D.L

EN No.: EN18352054

# Coding for ELectronic components

The codes used for the Electronic Components are available

The electronic omponents used are;

1. NodeMCU - Microcontroller with in-built Wi-Fi chip
2. DHT11 - Air temperature and humidity sensor
3. Soil Moisture sensor - Sensing the amount of moisture in the soil
4. DS18B20 - Temperature sensor probe to measure soil temperature
5. Neo-6M GPS module - For GPS coordinates, time and date information
6. TP4056 - Lithium battery charding module
7. DC USB 0.9V 5V to 5V DC boost step-up module - Powering of the NodeMCU from the mini-USB port
8. SD card module - To store data to the SD card

# ARIMA model algorithm

The ARIMA model is characterized by the 3 terms which are;
1. p which is the number of AR terms
2. d which is the number of differencing required for the series to be stationary
3. q which is the number of MA terms

Using Autocorrelation method(ACF) and Passive Autocorrelation method(PACF), the varibales best for the ARIMA model was identified.

The values obtained were;

d = 1, this value was obtained from the ACF plot 

p = 2, which can be taken by the PACF plot by observing the number of significant lags which are above the signficance level.

q = 2, which tells the number of MA terms needed to remove any correlation terms and this value is found using the PACF plot.

The current python code has been uploaded.
