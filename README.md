# Install NVE(DEC + FEB) + Koil_Sahders
### _HUNCHO - 666_
![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)

### Results with NoPixel ReSahder + NVE
| Video/Image | LINK | Note |
| ------ | ------ | ------ |
| Youtube Video: | [Click Here](https://www.youtube.com/watch?v=sRXFzAJ2m4I&ab_channel=RPDaily)| This can only be achived if you fully add NVE FILES (==not recommanded==) |
| ScreenShots in game: | [Click Here](https://prnt.sc/zBeoelfUzIpv), [Click Here](https://prnt.sc/Sh3BsGbvs5Qu), [Click Here](https://prnt.sc/F5SLHGiiN_8y), [Click Here](https://prnt.sc/Nf9OYbyV-coM)| The Result followint the bellow tutorial |


## Downloads
Google Drive Links Bellow.

| Downloads | LINK |
| ------ | ------ |
| Virus scan - NoPixel: |[Click Here](https://www.virustotal.com/gui/file/b3456cc798864728359778a76eef7c9361f994bf863d945adddfcd7e126adf61?nocache=1)|
| Download Google Drive Link: | [Click Here](https://bit.ly/3HT2BYP)|

## Oveview

This .md file provides instructions on how to install and set up the Koil_Shader for the game "Grand Theft Auto V".

The steps include copying the "mods" folder to the FiveM mods folder and copying the GTA 5 folder to the GTA 5 directory. The instructions also mention the option to install the latest version of ReShade.

Once in FiveM, the user must allow the latest version of ReShade by pressing F8 and adding specific lines to the CitizenFX.ini file. In the game, the user must copy the RS v0.001 ReShade preset to the GTA 5 directory and load it by pressing the home key. The Enbseries can be turned on or off by pressing Shift+F12. If the user installed ReShade, they must open it by pressing the home key and load the koil_ReShade.ini file.

A note is included that sometimes the game may look strange until the map is opened and closed.

The above .md file not only provides instructions on how to install and set up the Koil_Shader for Grand Theft Auto V, but also includes the necessary tweaks to the ReShade to achieve the desired appearance as seen in the accompanying screenshots. This guide is presented in a clear and concise manner, ensuring a smooth installation process and optimal performance of the Koil_Shader.

## 1. Install NoPixel Re-Shader(Koil_Resahder)

 1. Copy mods folder to your fivem mods folder:
    Location should look something like this: (C:\Users\username\AppData\Local\FiveM\FiveM.app\mods)

 2. Copy GTA 5 Folder to your GTA 5 Directory:
    Location should look something like this: (C:\Program Files\Steam\SteamLibrary\steamapps\common\Grand Theft Auto V)

 3. Install the latest reshade @ https://reshade.me/ and select it to run off your GTA 5 exec when prompted, **you dont need to select any extras, just sweetfx**


4. Once reshade is installed, you must allow FiveM to use the latest version, OPEN FIVEM, PRESS F8 AND YOU WILL SEE A ERROR CODE LIKE BELOW
Add THOSE lines below to your C:\Users\username\AppData\Local\FiveM\FiveM.app\CitizenFX.ini -- NOT A DIRECT COPY OF THE TWO BELOW THE NUMBERS ARE DIFFERENT
[Addons]
ReShade5=ID:51521de7 acknowledged that ReShade 5.x has a bug that will lead to game crashes


5. Copy RS v0.001 reshade preset to your GTA 5 dir, then load it in game by hitting home.
Location should look something like this: (C:\Program Files\Steam\SteamLibrary\steamapps\common\Grand Theft Auto V)


6. Once you are in game, shift+F12 should toggle on or off enbseries, though, you shouldnt need to mess with this, you are free to.

##### Note:
>*If you didnt install reshade, you are done.*
*If you press home, it will open your ReShade, load koil_ReShade.ini from your GTA5 Dir and you should be set.*
*I have noticed sometimes the game looks weird until I open / close the map, unsure what thats about.*


## 2. Getting the Re-Sahde looking exactly like NO-Pixel Server
Open up ReShader by pressing **home** button activate the following options form the list, once you have them activated look at the bottom of the ReSahder and start making tweeks as follow; ==you must change the valuse in between [] - in order to have the same output==
```markdonw
Technicolor2 [technicolor2.fx] 
    - R:[55] | G:[55] | B:[55] > ColorStrength
    - [0.970] > Brightness
    - [1.048] > Saturation
    - [0.794] > Strength
    
MXA0 [qUINT_maxo.fx]
    - [Ultra 64 Samples] > Samle Quality
    - [7.000] > Sample Radius
    - [0.700] > Reder Size Scale
    Ambient Occlusion
    - [1.000] > Ambient Occlusion Amount
    Indirect Lighting
    - [4.000] > Indirect L A 
    - [4.000] > Indirect L S 
    Blending
    - [3] > Bleding Mode
    - [0.008] > Fade Out Start
    - [0.205] > Fade Out End

Levels [Levels.fx]
    - [8] > Black Point 
    - [255] > White Point
    
Curves [Curves.fx]
    - [Chroma] > Mode
    - [Half-circles] > Formula
    - [0.007] > Contrast
```
    
## 3. NVE INSTALL - Roads + White Lights    

1. From NVE - FiveM Package.zip\Main Package\mods copy bellow files:
    - a_NVE_Models_and_Textures.rpf
    - a_NVE_Models_and_Textures_2.rpf
    - z_NVE_Steet_Lights.rpf
    
2. From NVE - FiveM Package.zip\Optional Add-Ons\2.Street Lights Pack\White Street Light
copy in:
     - z_NVE_Steet_Lights.rpf
     
3. From NVE - FiveM Package.zip\Optional Add-Ons\5.Parallax Roads
copy in:
    - %localappdata%FiveM > FiveM Application Data > Mods 


4. From NVE - FiveM Package.zip\Optional Add-Ons\2.Street Lights Pack\White Street Light
    - copy entire folder => sahderinput in C:\Program Files\Steam\SteamLibrary\steamapps\common\Grand Theft Auto V


