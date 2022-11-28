# HARDWARE - TBA
Sensors:

Accelerometer:
    Requirements:
      -Analog
      -3 axes
      -High sensitivity
      -High bandwidth
      -Low output impedance
      
    Option chosen:
      -ADXL345    



Microphone:
    Requirements:
      -Works well both indoors and outdoors
      -Can run for long periods of time
      -Pressure mounted
      -Inexpensive
      -Small and easy to connect to the board externally.
      
    Option chosen: 
      -Piezo discs (https://www.amazon.com/dp/B07FX6GXB7/)
        These microphones meet our requiemtents if planning to attach later on. 
      -Will use a Ziltek ZTS6117 microphone to have all components printed on the PCB. 




 Microprocessor/Bluetooth and WiFi Module:

    ESP32-WROOM-32D
    
    USB Type-B: CP2102-GMR_NRAND
    
    
 Buck converter: TPS54331DR 
    -Implemented over a linear regulator since we want to reduce the amount of heat from the board. 
    -Still inexpensive but linear regulator will still be functional.
    
Amplifier: LMV321


    
