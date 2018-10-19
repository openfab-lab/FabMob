## FAQ module 3D printing

1. [What if the printer won't connect ?](https://github.com/openfab-lab/FabMob/blob/master/FAQ/FAQ_3Dprinting-module.md#what-if-the-printer-wont-connect-)
2. [What if the print gets loosened from the bed (le print décolle)](https://github.com/openfab-lab/FabMob/blob/master/FAQ/FAQ_3Dprinting-module.md#what-if-the-print-gets-loosened-from-the-bed-le-print-d%C3%A9colle)
3. [How to change the filament ?](https://github.com/openfab-lab/FabMob/blob/master/FAQ/FAQ_3Dprinting-module.md#how-to-change-the-filament-)
4. [How to avoid and repair a clogged nozzel ?](https://github.com/openfab-lab/FabMob/blob/master/FAQ/FAQ_3Dprinting-module.md#how-to-avoid-and-repair-a-clogged-nozzel-)
5. [Which 3D printer are we using ?](https://github.com/openfab-lab/FabMob/blob/master/FAQ/FAQ_3Dprinting-module.md#which-3d-printer-are-we-using-)
6. [What is inside ?](https://github.com/openfab-lab/FabMob/blob/master/FAQ/FAQ_3Dprinting-module.md#what-is-inside-)



### What if the printer won't connect ?
Try the following sequence :
1. Connect the USB cable
2. Open the software Matter Control
3. Power the printer on
4. Connect

If the printer still doesn't, you can help by adjusting the settings. Got to **Settings & Control**/**Settings**/**Printer**/**Connection**. There you can chose the USB serial port to which to connect.  

### What if the print gets loosened from the bed (le print décolle)
There are two main causes :
- The callibration is not right
- The tape is not good

If the calibration is not right, you can calibrate the fabricator with the screws on teh bed. Use the allen keys to turn right to move the bed down (the head up), and left to move the bed up (the head down). Use a peace of paper (post-it for example) to rest the distance to the bed. It shoud be giving a little resistance. While printing, you can adjust the Z hight with MatterControl in 'CONTROLS'. Click 0.02 and then Z+ or Z-.
**Note in the notebook that you calibrated the bed**.

If the tape is not good, replace the tape with blue tape. Be carefull to cut the edges and not to fold it unter the bed. If the tape is too damaged, it is good to replace it.

Other solutions are :
- heating the bed to 50 à 60° (SETTINGS/Filament/Temperatures)
- add a raft that is touching (SETTINGS/General/RaftPriming)
- put some stick glue on the printer bed


### How to change the filament ?
It is nice to remove the filament when done with the session. You will need to do this manually.

Fist go to CONTROLS and heat the head to 215°. Do a purge, extrude 10mm (E-). When done, cool down again to 120 à 140° to pull the filament out. To pull, push the lever at the motor and pull gently the filament out. This is called a cold pull. It helps to remove impurities in the head. Put the end of the filament in one of the holes on the bobine, it will prevent entangling. **Write in the otebook when there is no filament left.** Also be kind and send a message to contact@openfab.be.

To put the filament back, simply heat the head to 210°. Cut the filament end so it has a sharp point. This will help the filament go smooth in the tube. You can gently bent the filament so the end is straigtend. Then introduce the filament in the feeder while pushing the lever.


### How to avoid and repair a clogged nozzel ?
https://www.youtube.com/watch?v=g8uvh6kvr54
ou bien https://youtu.be/g8uvh6kvr54?t=171 
- Don't overheat > pull out filament after job and turn off the heating
- Clean by cold pull > heat, push the filament manually, cool down to 120°C, pull it out cold.

> C'est bien la technique a suivre comme premier geste pour nettoyer la buse. 
Mais attention, cold c'est trop froid. Le mieux est de retirer le tube ptfe blanc, enfoncer un filament à chaux quelques instants et l'extraire d'un coup bref. 
Couper le bout , commencer et observer ce bout pour voir si des crasses sont emportées. 
Le dernier test, c'est pareil mais en laissant refroidir la buse et extraire le fil vers 160°C. Vous pouvez tester plus bas mais a un moment, le PLA va solidifier dans l'extrudeur.
Là aussi, c'est pour attacher les dernières crasses dans le PLA plus dur. 
Si après ça, ça ne va pas mieux. Le filament doit s'extruder de manière fluide, droite. Si le fil qui sort est dévié, c'est qu'une crasse bloque encore la buse directement. 
Dans ce cas, il faut chauffer et je prend un fil de cuivre. J'ai dans une boîte du fil émaillé de 0.3mm. 
Couper un morceau, 30cm suffisent, et le glisser par le trou de la buse (avec des gants ou une pince, la chaleur va passer dans le fil)
Et curer la buse en passant le fil entièrement plusieurs fois, le fil va emporter les restes de vieux plastique. 
Si après tout ça, ou si le fil de cuivre ne passe ps du tout, alors il faut démonter et changer la buse. Y en a dans une boîte au dessus de l'étagère avec les imprimantes. 
! Opération à faire à chaud aussi. Le métal se dilate et il faut bien revisser à chaud , sans serrer très fort quand même, mais à chaud pour éviter des fuites lors du print. Ce qui arrive souvent à ceux qui assemble leur extrudeur à froid.
Y a plein de vidéo sur le net. Et c'est pareil pour tout les modèles donc peu importe de trouver absolument l'info pour la fabrikator.


### Which 3D printer are we using ? 
3D printer Fabrikator mini II
https://hobbyking.com/en_us/fabrikator-mini-ii.html?___store=en_us

Specs:
- Nozzle diameter: **0.4 mm (0.015 in)**
- Positioning Precision: **XY 11 microns (0.0004 in), Z 2.5 micron (0.0001 in)**
- Layer Resolution: **100 microns (0.0039 in)**
- Input Power: 100-240V, Max:80W
- Mains plug: AU type
- Nozzle heating: **Max 250℃**
- Filaments: **1.75mm diameter PLA, ABS, PETG**
- Interface: Memory card, USB and wireless network
- Build Surface: Heated aluminium bed with PEI coating
- Supported File: **STL, OBJ/G-Code**
- OS: Windows10, Mac OS X, Linux
- Certificates: CE, ROHS, FCC, ISO 9001:2008
- Product Dimensions: 172 x 183 x 270mm
- Build Volume: **100 x 100 x 100mm**
- Shipping Box: 220 x 220 x 320mm


### What is inside ?

![img_2806](https://user-images.githubusercontent.com/31619215/45151750-72f7f700-b1cf-11e8-9a79-19c86d2d4900.jpg)

From left to right

![img_2807](https://user-images.githubusercontent.com/31619215/45151769-830fd680-b1cf-11e8-8c91-0bc05be66e1b.jpg)

- 1x lenovo helix2
- 1x power supply lenovo
- 1x souris usb

![img_2809](https://user-images.githubusercontent.com/31619215/45151906-dd109c00-b1cf-11e8-85aa-008524d95aac.jpg)

- 2x filament PLA + supports plastiques for printing
- 1x filament PET for showing
- 1x bobine 3D printed
- 1x box wit 3D printed examples

![img_2811](https://user-images.githubusercontent.com/31619215/45152153-7d66c080-b1d0-11e8-9950-0bd3130f3cf6.jpg)

- 2x power supply Fabrikator v2
- 2x multiprise noire
- 1x enrouleur multiprise
- 1x spatule
- 1x pince coupante
- 1x pince noire (type "à épiler")
- 1x rouleau de tape bleu (3Dprint)
- 2x bobines PLA + supports plastique
- 2x supports bobines metal

![img_2815](https://user-images.githubusercontent.com/31619215/45152223-b6069a00-b1d0-11e8-8eb6-139242820e21.jpg)

- 2x cable micro USB
- 2x hub usb
- adaptateur usb>microSD

![img_2816](https://user-images.githubusercontent.com/31619215/45152302-e77f6580-b1d0-11e8-8bd8-d72bcdf7846f.jpg)

- 2x Fabrikator v2

