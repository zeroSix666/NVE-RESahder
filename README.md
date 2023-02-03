# Install NVE + Koil_Sahders
### _HUNCHO - 666_
![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)


## How to install Koil_Shader aka NO-PIXEL Re-Sahder + right Settings to acctivate

#### Setup:
```sh
 - Copy mods folder to your fivem mods folder 
Location should look something like this: (C:\Users\username\AppData\Local\FiveM\FiveM.app\mods)

- Copy GTA 5 Folder to your GTA 5 Directory. (This is enbseries, be sure to save any old shit.)
Location should look something like this: (C:\Program Files\Steam\SteamLibrary\steamapps\common\Grand Theft Auto V)
```

(This is no longer required - only add this if you want more color saturation or have rtgi)
```sh
Install the latest reshade @ https://reshade.me/ and select it to run off your GTA 5 exec when prompted (you dont need to select any extras, just sweetfx)
```
Location should look something like this: (C:\Program Files\Steam\SteamLibrary\steamapps\common\Grand Theft Auto V\GTA5.exe)


> Once reshade is installed, you must allow FiveM to use the latest version, OPEN FIVEM, PRESS F8 AND YOU WILL SEE A ERROR CODE LIKE BELOW
Add THOSE lines below to your C:\Users\username\AppData\Local\FiveM\FiveM.app\CitizenFX.ini -- NOT A DIRECT COPY OF THE TWO BELOW THE NUMBERS ARE DIFFERENT

> [Addons]
ReShade5=ID:51521de7 acknowledged that ReShade 5.x has a bug that will lead to game crashes

```sh
Copy RS v0.001 reshade preset to your GTA 5 dir, then load it in game by hitting home.
Location should look something like this: (C:\Program Files\Steam\SteamLibrary\steamapps\common\Grand Theft Auto V)
```

Once you are in game, shift+F12 should toggle on or off enbseries, though, you shouldnt need to mess with this, you are free to.


If you didnt install reshade, you are done.

If you press home, it will open your ReShade, load koil_ReShade.ini from your GTA5 Dir and you should be set.
I have noticed sometimes the game looks weird until I open / close the map, unsure what thats about.


## Activate the following when the Re-Shader is on
 you must change the valuse in between [] - in order to have the same output
##### Technicolor2 [technicolor2.fx]
    - R:[55] | G:[55] | B:[55] > ColorStrength
    - [0.970] > Brightness
    - [1.048] > Saturation
    - [0.794] > Strength
##### MXA0 [qUINT_maxo.fx]
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
    
##### Levels [Levels.fx]
    - [8] > Black Point 
    - [255] > White Point
##### Curves [Curves.fx]
    - [Chroma] > Mode
    - [Half-circles] > Formula
    - [0.007] > Contrast
    
    
### NVE INSTALL - Roads + White Lights    
