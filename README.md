# The RelhaxTIM repository consists of: 
- this [README.md]
- a folder called [CarouselIconsConfigs]. Here is where the configs for the carouselicons will be stored.
- a folder called [ContourIconsConfigs].  Here is where the configs for the contouricons will be stored. 
- a folder called [TechtreeIconsConfigs].  Here is where the configs for the techtreeicons will be stored.
- a folder called [TankIconMaker-PORTABLE] with the actual program (+ hardcoded cfgs in program-config-file)
------------------------------------------------------------------- 
 <br>
 
# What is TIM? 
TIM stands for "Tank Icon Maker".
We use this program to update/create following mods:
- ContourIcons
- TankIcons_Carousel
- TankIcons_TechTree
-------------------------------------------------------------------
------------------------------------------------------------------- 
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
------------------------------------------------------------------- 
 <br>
 
# HOW-TO 
 <br>
 
### Update TIM
- use github for source control / pull before push!
- download the new version from the source (link above).
- copy files from the downloaded archve into the [TankIconMaker-PORTABLE] folder
- inside this folder: rename the folder with the program´s versions number to [_currentVersion_DATE]. (eg: "_v061-b204_2020-11-25"). yes, with an underline at the beginning to be on first place in folderview with alphabetical order.
- push changes to github <br>
 <br>

### Use TIM
#### updating icons:
- just start the [TankIconMaker.exe] directly from the github repo! (dont forget to pull first if anyone made changes)
- the config files for icons are already loaded into TIM -> after creation/import they are hardcoded into [TankIconMaker2.Settings.xml]. 
- press bulk export into folder, select a folder and the configs you want to create.
<br>

Step-by-step:
- first pull repo
- pic 1) go to the TIM folder 
- pic 2)  start TIM
- pic 3) if not automatically, choose your wot installation (or press "+" to add your game directory)
- pic 4) click on "save as" and use the last option "haufenspeichern" (ger) / "bulk save to folder" (eng; or something similar)
- pic 5) choose a folder on your harddisk
- pic 6) choose the configs you want to create
- pic 7) creating the mods is done
- download the old file from our server. delete the image files from there and use the same folder structure to update the mod.
<br>

Pictures:

http://bigmods.relhaxmodpack.com/Medias/Pictures/01_HowToPics/TIM/1_TIM_stepByStep.png
http://bigmods.relhaxmodpack.com/Medias/Pictures/01_HowToPics/TIM/2_TIM_stepByStep.png
http://bigmods.relhaxmodpack.com/Medias/Pictures/01_HowToPics/TIM/3_TIM_stepByStep.png
http://bigmods.relhaxmodpack.com/Medias/Pictures/01_HowToPics/TIM/4_TIM_stepByStep.png
http://bigmods.relhaxmodpack.com/Medias/Pictures/01_HowToPics/TIM/5_TIM_stepByStep.png
http://bigmods.relhaxmodpack.com/Medias/Pictures/01_HowToPics/TIM/6_TIM_stepByStep.png
http://bigmods.relhaxmodpack.com/Medias/Pictures/01_HowToPics/TIM/7_TIM_stepByStep.png

#### making changes:

##### import configs:
- pull Git
- start TIM from repo
- import config from file into TIM
- copy previously imported file into the designed config folder [Carousel/Contour/TechtreeIconsConfigs] for source control
- push changes to the configurationfile folder and the TIM configuration file [TankIconMaker2.Settings.xml] to Github when you are done


##### create a new config: 
- pull Git
- start TIM from repo
- create, name and save your configuration with TIM
- export your configuration file into the designed config folder [Carousel/Contour/TechtreeIconsConfigs] for source control
- push changes to the configurationfile folder and the TIM configuration file to Github when you are done

<br>
<br>
