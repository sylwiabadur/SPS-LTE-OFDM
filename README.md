# SPS-LTE-OFDM


## How to run - prerequisites
To run the app you will need to download LTE Toolbox and Communications Toolbox packages in Matlab.

## How to run - step by step
First run *ltemodgui.m* file. The app will open. 
Click *Load data from txt* button. Then load appropriate txt file with modulated data.

Then in command line you will see a modulation - please click it on the list box (it's an issue we will try to fix).
Then you can display OFDM modulation properties by clicking *Show OFDM properties* button.

You can manage base station parameters. Then click *Create LTE OFDM Modulation*. First of all an xml file with modulation params will be created and modulation will be proceeded in the background. After that you will see message box. Please select button *Write data to txt* at the end to write data stream to txt and pass it to the channel group.

Written files will be named:
*dataToChannel.xml* and *dataOutOfdm.txt*