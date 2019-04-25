<h1 align="center">
   <img src="https://github.com/auto-chess-ui-mod/download/raw/master/images/banner_img.PNG" alt="UI Mod for Dota 2 Auto Chess" title="UI Mod for Dota 2 Auto Chess" />
</h1>
<p align="center">  
 <a href="https://opensource.org/licenses/MIT"><img src="https://img.shields.io/badge/license-MIT-blue.svg"></a>
 <a href="https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=2UKM4JREAPTBG"><img src="https://img.shields.io/badge/buy%20me%20some-candy-yellow.svg"></a>
 
</p>

<p align="center">
  This UI mod for Dota 2 Auto Chess adds several QoL improvements to the UI. <br> <br>
  <span><strong>Source code: </strong><a href="https://github.com/auto-chess-ui-mod/source ">repository </a></span><br>
  <span><strong>Generator: </strong><a href="https://github.com/auto-chess-ui-mod/generator">repository</a></span>
</p>

## Disclaimer

This is just a hobby project and **using any of the provided code / files is at your own risk!**

In my interpretation, this UI mod falls under the category of "Cosmetic UI mods" which should not result in VAC ban (see for example: [link](https://dota2.gamepedia.com/Ban#Exceptions)). But to reiterate, using it is your own responsibility. 

I will remove the download links if the DAC developers request me to do so. 

**Note:** the `lite` version of the mod does not include any of the code relating to the draw probabilities, so it is on the safer side (I guess). 

## Instructions + download links

You can install the mod following these steps:  

1. Download the version with the modifications you want:  
a. [Full version](https://github.com/auto-chess-ui-mod/download/raw/master/vpk/full/pak01_dir.vpk): *Gold to level up + PVE Warning + Draw probabilities*   
b. [Lite version](https://github.com/auto-chess-ui-mod/download/raw/master/vpk/lite/pak01_dir.vpk): *Gold to level up + PVE Warning*   
c. [Full version + Tier indicator](https://github.com/auto-chess-ui-mod/download/raw/master/vpk/full_tier/pak01_dir.vpk) (Tiers from [qihl.gg tier list](https://qihl.gg/tierlist))

2. Find your Dota 2 installation directory  
   *For example:* `D:\Steam\steamapps\common\dota 2 beta`
   
3. Create a folder called `custom_dac_ui` in the `game` folder  
*For example:* `D:\Steam\steamapps\common\dota 2 beta\game\custom_dac_ui`

4. Copy the  `pak01_dir.vpk` file that you downloaded in step 1 into the `custom_dac_ui` folder

5. Open the `gameinfo.gi` file located in the `game > dota` folder with a text editor (e.g. notepad)  

6. Modify the `gameinfo.gi` file by adding the following two lines:

![](https://github.com/auto-chess-ui-mod/download/raw/master/images/modify_gameinfo.PNG)

**Two notes:**  
a. The positioning of the lines is important  
b. Any major Dota 2 updates might reset the `gameinfo.gi` file, if that happens just repeat step 5 and 6

### Acknowledgements

When developing this mod I used the work of some other developers to figure out how to accomplish it:

* The `Divine UI Source` [repository](https://github.com/dota2-divine-ui/divine-ui-source)  
* The `Dota Auto Chess: Trainer` [website](https://dota2chess.com/)
