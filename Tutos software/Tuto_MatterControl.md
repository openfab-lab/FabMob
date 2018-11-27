## What can you do with MatterControl ?
Matter Control is an open source source software that allow to pilote a 3D printer. It has some advantages over more classic software like Cura. Firstly you can control the printer in real time, during the job. Secondly the printer settings can be synchronised with an online account.

Find the project here https://github.com/MatterHackers/MatterControl

Printing with Matter Control happens in a few steps that we will detail further on.
- [1. Connect the printer](https://github.com/openfab-lab/FabMob/blob/master/Tutos%20software/MatterControl.md#1-connect-the-printer)
- [2. Import the 3D model and edit if needed](https://github.com/openfab-lab/FabMob/blob/master/Tutos%20software/MatterControl.md#2-import-the-3d-model)
- [3. Adjust the settings to your needs](https://github.com/openfab-lab/FabMob/blob/master/Tutos%20software/MatterControl.md#3-adjust-the-settings)
- [4. Print and control the printing process](https://github.com/openfab-lab/FabMob/blob/master/Tutos%20software/MatterControl.md#4-print-and-control-the-printing-process)

![](https://github.com/openfab-lab/FabMob/blob/master/Tutos%20software/MatterControlscreen.PNG)


### 1. Connect the printer
The printer is ready in the software. You can connect with the button **Connect** and follow the instructions if asked. 

Select the right printer profile at the top next to connect.

If the printer won't connect, see [What if the printer won't connect ?](https://github.com/openfab-lab/FabMob/blob/master/FAQ/FAQ_3Dprinting-module.md#what-if-the-printer-wont-connect-)

### 2. Import the 3D model 
Your model can be .stl or .gcode. Click left below on **Add** to import the 3D model. 

You can edit the model at the right. You can scale and rotate. Don't forget to push **Save** right below when you are done. 

You can also preview the printing at the right. Click right at the top on **LAYER VIEW** and then **Generate** to check the time of printing. Slide the bar to check the layers.

### 3. Adjust the settings
Go to **Settings & Controls** to adjust the settings to your needs. You have all the options in **SETTINGS**. 
Check in SETTINGS/GENERAL/Raft Priming if you are ok with the Skirt (usually we put 5mm touching). 
Check in SETTINGS/GENERAL/Support Material if the support is activated or not.

If the setting is put in **blue** it means it is changed in comparison to the original settings.

*Tip : if you are not sure of a setting, open Cura and read the instructions of the equivalent setting.*

To change the filament, see [How to change the filament ?](https://github.com/openfab-lab/FabMob/blob/master/FAQ/FAQ_3Dprinting-module.md#how-to-change-the-filament-)

### 4. Print and control the printing process
If you are ready with the settings, you can click **PRINT**. It is important to check if the first layer is printing well. 

During the printing, you can control the printer. Go to **CONTROLS**. 
- You can change the temperature of the extruder and the bed. 
- You can change the Z offset. This is interesting if the first layer is not thick enough. 
- You can also lower or higher the speed of printing and the exstrusion. This is interesting if there is not enough filament coming out of the head.

If the filament won't stick to the bed, see [What if the print gets loosened from the bed (le print décolle)](https://github.com/openfab-lab/FabMob/blob/master/FAQ/FAQ_3Dprinting-module.md#what-if-the-print-gets-loosened-from-the-bed-le-print-d%C3%A9colle)
