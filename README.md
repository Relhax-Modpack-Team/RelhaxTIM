# The RelhaxTIM repository consists of: 
- this [README.md]
- a folder called [CarouselIconsConfigs]. Here is where the configs for the carouselicons will be stored.
- a folder called [ContourIconsConfigs].  Here is where the configs for the contouricons will be stored. 
- a folder called [TechtreeIconsConfigs].  Here is where the configs for the techtreeicons will be stored.
- a folder called [TankIconMaker-PORTABLE] with the actual program (+ hardcoded cfgs in program-config-file)
------------------------------------------------------------------- <br>
 <br>
 
# What is TIM? 
TIM stands for "Tank Icon Maker".
We use this program to update/create following mods:
- ContourIcons
- TankIcons_Carousel
- TankIcons_TechTree
-------------------------------------------------------------------
------------------------------------------------------------------- <br>
 <br> 
 
# "Tank Icon Maker" Description:
Tank Icon Maker greatly simplifies the creation of icons for World of Tanks. 
Icons are created by combining different layers and effects, the properties of which depend on the properties of the tanks. 
It is enough to create a style of your choice once, after which a complete set of icons is created with the click of a button. 
No need to wait for the author of your favorite icons to release an update! <br>
 <br>
If you are not completely satisfied with any design, you have the opportunity to change anything in it. 
For example, remove the background. Change fonts and colors. Remove the picture of the tank, or use a 3D picture. 
Draw an asterisk for drum tanks. Add information about one-time damage with the top gun. Add a nation flag. 
Remove everything except the name of the car. Use your own custom names. 
In short, that's enough imagination. <br>
 <br>
 
### Program features:
- Tank properties are automatically read from the game client.
- Font anti-aliasing of your choice: either ClearType anti-aliasing or crisp pixel borders.
- Selection of the font size so that the text fits into the required frames.
- The level of the tank in Roman or Arabic numerals.
- Creation of icons of any size, at least 24x24, at least 500x300 - for example, for your site.
- Choice of interface language (translators required!)
- A bunch of built-in properties, as well as exporting these properties from the client to .csv format.
 <br>
 <br>
 
### Current URL for new versions:
https://ci.appveyor.com/project/rstarkov/tankiconmaker/build/artifacts
 <br>
 
### Original TIM Homepage (outdated):
https://roman.st/TankIconMaker?lang=ru
 <br>
 
### Old Github URL:
https://github.com/rstarkov/TankIconMaker/ <br>

-------------------------------------------------------------------
------------------------------------------------------------------- <br>
 <br>
 
# HOW-TO 
 <br>
 
### Update TIM
- use github for source control / pull before push!
- download the new version from the source (link above).
- copy files from the downloaded archve into the [TankIconMaker-PORTABLE] folder
- push changes to github <br>
 <br>
 
### Use TIM
- just start the [TankIconMaker.exe] directly from the github repo!
- the config files for icons are already loaded into TIM. 
  just press bulk export into folder, select a folder and the configs you want to create.
- adding new configs:  either create a new one or use the import function.  <br>
<br>

#### Source control:
- if a config was imported:  <br> copy the config file into the designed config folder [Carousel/Contour/TechtreeIconsConfigs]
- if a config was created new: <br> export the config file to the designed config folder [Carousel/Contour/TechtreeIconsConfigs]
