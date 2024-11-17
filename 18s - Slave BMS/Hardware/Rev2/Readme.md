# 18s - Slave BMS      
## Design Language    
-> Simple design (2-Layer board)       
-> Easy to use       
-> Small in size (94mm x 90mm)

## Features     
-> Analog Devices AFE: LTC6813            
-> 0 - 5V voltage measurement of cells (NMC, LFP, LTO, Na-ion)        
-> Cell balancing up to 150mA per cell (External balancing)(balancing current can be increased by changing balancing resistors)       
-> SPI or Iso-SPI configurable          
-> Direct interface with any microcontroller (via SPI upto 18s)        
-> Configurable for temperature measurement via 10K thermistor or ADC for current measurement.     
-> 9x temperature sensing (thermistor based)         
                      (or)              
-> 8x temperature sensing (thermistor based) & 1x current sensing (AUX)       
-> Short circuit protection and wake-up interrupt by hardware design 

## PCB isometric
![image](https://github.com/user-attachments/assets/de3d8340-fca5-4524-a7b8-aabf1d22c7af)

## PCB Sections & Connectors
![image](https://github.com/user-attachments/assets/b212bcf6-f6ea-4189-9a01-9d58b8ea0170)

![image](https://github.com/user-attachments/assets/b562874a-5b28-4938-a200-069ede7b26ec)
