# THE-HYBRID-THING (THYNG)
![PXL_20220808_113726192 PORTRAIT](https://user-images.githubusercontent.com/88040345/183528472-f8c01683-e461-49ca-acc9-418eba13f83e.jpg)
The Hybrid Thing is an Hybrid extension for the open surce projekt The Analog Thing.
## Current functionality
In the picture above you can see the prototype. It has 30x 10Bit Digitalpotentiometers, 8x 16Bit Digital to Analog Converters and 22x 24Bit Analog to Digital Converters.
The Brain of THYNG (thanks to Dale Luck for the nickname) is an ATMega2560Pro at the moment but will be changed to an teensy4.1 in the next version.
On the back there are two Hybridports for two THATs so it is possible to have two THATs working with different timings together. In because of the ADCs and DACs it is also possible to implement delay funktions and signal generation. Sadly the SPI bus on the PCB is a bit nasty (i messed it up) and  i am only able at the moment to access 8 Potis and 8 DACs. 
## Version 2.0
At the moment all ICs are soldered directly to the main panel which makes it difficult to debug and try new components.  In the next version there will be three different PCBs connected to the main panel. The Poti board on wich will be 4 Digitalpotentiometer, the DAC board on wich one DAC with four analog outputs will be and an ADC board on wich will be one ADC with 8 analog inputs. The main panel of version 2.0 will just connect the boards with the teensy and the patchpanel. But there will also be the power supply wich is the same as used on THAT. The patchpanel of version 2.0 won't be so colorful as the  patchpanel of version 1.0 because version 2.0 will habe an PCB patchpanel wich is way cheaper and easyer to solder.   
### Main Panel

### Patch Panel

### Poti board
![Poti_board2](https://user-images.githubusercontent.com/88040345/188515353-44147fa4-1428-4020-807a-47bc91e063e7.png)

### DAC board
![DAC_board](https://user-images.githubusercontent.com/88040345/188515297-c7090d79-6e87-4d23-87d5-09beea0f45c0.png)

### ADC board
