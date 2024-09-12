# 6s - Slave BMS      
## Design Language   
-> Scalable       
-> Simple design (2-Layer board)           
-> dedicated current sensing port      
-> Small in size

## Features     
-> Analog Devices AFE: LTC6810         
-> 0 - 5V voltage measurement of cells (NMC, LFP, LTO, Na-ion, Zn-air etc...)
-> SPI or Iso-SPI configurable          
-> External Power connector (Powering IC from external source instead of battery, useful for cells with low voltages like Zn-air)
-> 3s to 100s      
-> 4x temperature sensing (thermistor based)         
                      (or)              
-> 3x temperature sensing (thermistor based) & 1x current sensing       
-> Interface with any microcontroller (via SPI upto 6s)        
-> Configurable for temperature measurement via 10K thermistor or ADC for current measurement.         

## PCB Sections & Connectors       
![image](https://github.com/user-attachments/assets/8ae48af9-9fad-4699-90f0-e71d09dea454)        

![image](https://github.com/user-attachments/assets/9032f799-3414-4744-aa52-934e92501624)

## PCB Configurations      
![image](https://github.com/user-attachments/assets/3940d4b3-3a8a-4547-bb9a-3853c64f3ef7)




