# Print the 3DVerkstan face shield the fastway
Some files and documentation on how to print the Face Shield by 3DVerkstan really fast.

In this repository I used the guide by [Yannic Schröder](https://github.com/yschroeder) and improved printing experience of the model by [Erik Cederberg / 3DVerkstan](https://www.youmagine.com/designs/protective-visor-by-3dverkstan/).

The model is under the [CC-BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/deed.en_US) licence. 

All files are designed for a *ISO838 A6* face shield.  

## Disclaimer
These design files are provided "AS IS" WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied, including, without limitation, any warranties or conditions of TITLE, NON-INFRINGEMENT, MERCHANTABILITY, or FITNESS FOR A PARTICULAR PURPOSE.

This not a medical device. Consider it a Halloween constume! It is neither certified nor fit for any purpose.

All Parts are forks of the originals by Erik Cederberg.

## short instruction
* Use `PrusaSlicer`
* Set all speeds (except for `Support material`, `Bridges`, `Gap fill`, and `First layer speed`) to your `Travel` speed. The speeds in reality are limited by the slicer automatically by the `Max. Volumetric Speed` of the filament. So the printer will not print that fast, but as fast as possible.
* Set the `Max. Volumetric Speed` of the filament to set the real print speed. With a 0.4 mm nozzle, start at 8 mm³/s, increase to find the maximum of your printer. 17 mm³/s work for a E3D V6 with 0.8mm nozzle.
* Set 0% infill
* Set 0.87 mm extrusion width and set elephant foot compensation to 0. 
* Layerhight must be 0.28 to work perfeklty.
* If the extruder skips steps (loud clacking noise), lower the `Max. Volumetric Speed`. Or try to increase the nozzle temp, so the filament melts faster.
* If you can't seperate the Parts afterwards probably lower the nozzle temp, and if neccasary the `Max. Volumetric Speed`.

A more indepth guide on maximising your printing speed can be found at Yannic's repository: [RC3 Faceshield](https://github.com/yschroeder/face-shield)
## files
* All files where copied from 3DVerkstan, and remodelt in Fusion 360
* You can find the origininal files here: [Fusion 360 Cloud](https://a360.co/2V6acd1)
  If you don't wont to leave your E-Mail adress to Autodesk just use the files provides in this repository or ask me for other versions. 
* I trie my best to comment any changes I make, here on github and inside the fusion cloud. 

Files in the repository:
* stl files for printing.
* step files for all of you who want to further change this part. Keep in mind, that I won't be able to accept any pull request if you don't use Fusion 360 to change the file. But of course you can fork your own version :)
* printing files, this is a place where I keep my gcode versions, aswell as my printer settings. 
I use a anycubic I3 Mega with a 0.8 mm nozzle. Which runs at `Max. Volumetric Speed` of up to 14,5 mm³/s. Feel free to look into my settings for reference if you like. Don't run the gcode unless you are super sure of what you are doing! Otherwise always slice the part yourself to avoid demaging your printer. 
There are also settings for a Prusa MK3S which can be used as reference aswell. (This where generadet for Timo)

## seperation
I seperate the parts by cutting the Pins with an ~electronics diagonal cutter~. This splits the Parts at the pins, where I use a scaper to further split the parts. 

## versions
The version consist of two Parts. 
The first part is equvalent to the file version in Fusion 360 (at this moment v11) the second part will be increased everytime I update this github repository. 
Here is an exampleple:
The initial release of my github repo will be version v11.0 as the file version in Fusion is already at 11.
Nextup I will add a licence to this repository this will be v11.1. 
Maybe I decide to add a Stack of 30, this will change the Fusion file and therefore result in Version v12.0. 