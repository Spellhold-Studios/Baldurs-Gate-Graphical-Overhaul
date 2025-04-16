<hr>

:warning: **The maintenance and support of this project has been moved to a [new repository](https://github.com/Spellhold-Studios/Baldurs-Gate-Graphical-Overhaul).**

<hr><br>

![Platform](https://img.shields.io/static/v1?label=Platform&message=Windows%20%7C%20Mac%20%7C%20Linux&color=informational)
![Language](https://img.shields.io/static/v1?label=Language&message=every%20language&color=limegreen)
![SupportedGames](https://img.shields.io/static/v1?label=Supported%20games&message=EET%20%7C%20BGT%20%7C%20BG2%3AEE%20%7C%20TOB%20%7C%20BG1%3AEE%20%7C%20TuTu_TOSC&color=blue)

<div align="center"><h1>Baldur's Gate Graphical Overhaul</h1>

<h3>A Spellhold Studios mod for Baldur's Gate II:ToB, Baldur's Gate Trilogy, BG1:EE, BG2:EE, EET and TuTu<h3>

</div><br />


**Author:** Yovaneth, Weigo<br>
**Mod Website:** <a href="https://www.gibberlings3.net/">Gibberlings 3</a>  
**Mod Forum:** <a href="https://www.gibberlings3.net/forums/topic/36946-baldurs-gate-graphical-overhaul-bggo-for-eet-bgt-tutu-bgee/">Baldur's Gate Graphical Overhaul BGGO</a>  


<!--[Read the mod's readme](http://spellholdstudios.github.io/readmes/sos-readme-english.html).

[Download the mod at Spellhold Studios](http://www.shsforums.net/files/category/40-shadows-over-soubar/).<br> -->

&nbsp;

<div align="center">
<a href="#intro">Overview</a> &#8226; <a href="#compat">Compatibility</a> &#8226; <a href="#installation">Installation</a> &#8226; <a href="#credits">Credits and Acknowledgements</a>&#8226; <a href="#modding">Modding</a> &#8226; <a href="#versions">Version History</a></br>
</div>

<hr>


## <a name="intro" id="intro"></a>Overview

This mod is probably the biggest visual overhaul of the game since it was released. It reinstates the extended night areas that are missing from **all** main areas. Now, when you open doors at night they show light from inside the building. Buildings actually have windows that are lit up. 
Many night maps have their own lighting map and interiors are equipped with candles, torches and lights.<br>
As luck would have it, two met by chance in the Beamdog and Gibberlings 3 forums, respectively. The thanks here goes to Jastey. 
One was trying to deal with all the problems of the two versions not working properly for both engine variants. The other was just tweaking and beautifying the graphics further. 
Fortunately, when they finally got in contact, there was an incredible synergy effect. They understood each other right away and joined forces.
Not only were all the old graphics from BG1 reworked, but they also decided to add all the areas from BG2, ToB, SoD, BG1EE and BG2EE without the original night map.
This means that there are now 83 new night maps. In total 636 maps will be improved.
These are the night maps and also day maps. Light maps are added, graphical bugs are fixed, animated water areas are added, over 7000 animated candles, torches and lights are added.
Especially with the animated candles, torches and lights, old maps can be improved at any time.

<div align="right"><a href="#top">Back to top</a></div>


<hr>


## <a name="compat" id="compat"></a>Compatibility

This mod is compatible with both Infinity Engine variants.
Therefore, almost all Baldur's Gate variants are compatible with this version. Primarily with EET and BGT of course, but also with ToB (SoA is not enough) and BG2EE and also with BG1EE with or without SoD. TuTu_TotSC should also be compatible with BGGO, but has not been tested yet.<br>
This mod is compatible with all mods that do not overwrite are, wed, tis, pvrz and bmp files. are and wed files should be patched then. <br>
Additional built-in mod compatibility: <br>
 -Lure of Sirines Call<br>
 -Baldurans Seatower<br>
 -Gavin NPC<br>
 -TDDz<br>

<div align="right"><a href="#top">Back to top</a></div>


<hr>


## <a name="installation" id="installation"></a>Installation

#### Notes

*If you've previously installed the mod, remove it before extracting the new version. To do this, run **`setup-bggo.exe`**, un-install all previously installed components and delete the :file_folder: **bggo** folder.*

*When installing or un-installing, **do not close the DOS window** by clicking on the **X** button! Instead, press the **Enter** key whenever instructed to do so.*

*__Disable any antivirus__ or other memory-resident software before installing this or any other mod. Some (particularly avast and Norton!) have a tendency to report false positives with mod activity, resulting in failed installs.*

## 

#### Windows

Baldur's Gate Graphical Overhaul for Windows is distributed as an extractable compressed archive and includes a WeiDU installer.

Extract the contents of the mod archive into the folder of the game you wish to modify (*the folder which contains the "CHITIN.KEY" file*), using <a href="http://www.7-zip.org/download.html">7zip</a>, <a href="http://www.rarlab.com/download.htm">WinRAR</a>, or another file compression utility that handles .zip files. On successful extraction, there should be a :file_folder: bggo folder and a setup-bggo.exe file in your game folder. To install, simply double-click **`setup-bggo.exe`** and follow the instructions on screen.

Run **`setup-bggo.exe`** in your game folder to reinstall, un-install or otherwise change the components settings.

## 

#### Mac OS X

Baldur's Gate Graphical Overhaul for Mac OS X is distributed is distributed in the same compressed archive and includes a WeiDU installer.

First, extract the files from the archive into your game directory. On successful extraction, there should be a :file_folder: bggo folder, setup-bggo and setup-bggo.command files in your game folder. To install, simply double-click **`setup-bggo.command`** and follow the instructions on screen.

Run **`setup-bggo.command`** in your game folder to reinstall, un-install or otherwise change the components settings.

## 

#### Linux

Baldur's Gate Graphical Overhaul for Linux is distributed as a compressed tarball and does not include a WeiDU installer.

Extract the contents of the mod to the folder of the game you wish to modify.

Download the latest version of WeiDU for Linux from <a href="https://github.com/WeiDUorg/weidu/releases">WeiDU.org</a> and copy WeiDU and WeInstall to /usr/bin. Following that, open a terminal, **cd** to your game installation directory, run tolower and answer 'Y' to both queries. You can avoid running the second option (linux.ini) if you've already ran it once in the same directory. To save time, the archive is already tolowered, so there's no need to run the first option (lowercasing file names) either if you've extracted only this mod since the last time you lowercased file names. If you're unsure, running tolower and choosing both options is the safe bet.

To install, run **`WeInstall setup-bggo`** in your game folder. Then run **`wine BGMain.exe`** and start playing.

## 

#### Note for Complete Un-installation

In addition to the methods above for removing individual components, you can completely un-install the mod using **`setup-bggo --uninstall`** at the command line to remove all components without wading through prompts.</br>
<div align="right"><a href="#top">Back to top</a></div>


<hr>


## <a name="credits" id="credits"></a>Credits and Acknowledgements

**Original author:** <a href="http://www.shsforums.net/user/3378-cbisson/">Yovaneth</a> (incredible graphic artist)   
**Coders:** <a href="http://www.shsforums.net/user/3958-weigo/">Weigo</a> (completely revised version)  


#### Special Acknowledgements to:

- <a href="http://www.spellholdstudios.net/">Spellhold Studios</a> team for hosting the mod (<a href="http://www.shsforums.net">Forums</a>).
- <a href="https://www.gibberlings3.net/">Gibberlings3</a> team for hosting the mod (<a href="https://www.gibberlings3.net/forums">Forums</a>).
- The creators of the Baldur's Gate series: <a href="http://www.bioware.com/">Bioware</a> and <a href="http://www.obsidian.net/">Black Isle Studios</a>.
- For the great support and help: **Galactygon**, **Jastey**, **Salk**, **Sam**, **TotoR**, **ALIENQuake**, **skellytz** ... without the constant feedback, everything would not have been so possible<br> and many more, which I can't look up now, because the SHSForum is down. Should it work again, I will add all the others here, or they should contact me :)
- Everyone else from the <a href="http://gibberlings3.net/forums/">The Gibberlings Three</a>, <a href="http://www.shsforums.net/">Spellhold Studios</a> forums, and the other Infinity Engine gaming and modding communities who offered their help and support.

## 

#### Programs/Tools used in creation:

- <a href="https://github.com/WeiDUorg/weidu/releases"><acronym title="Weimer Dialogue Utility">WeiDU</acronym></a>, by Wes Weimer, the bigg and Wisp.
- <a href="https://github.com/Argent77/NearInfinity/releases">Near Infinity</a>, by Jon Olav Hauglid, FredSRichardson, and Argent77.
- <a href="http://www.shsforums.net/topic/31285-infinity-explorer-v085/">Infinity Explorer</a>, by Dmitry Jemerov / bigmoshi.
- <a href="http://www.gibberlings3.net/tools/dltcep.php"><acronym title="Dragonlance Total Conversion Editor Pro">DLTCEP</acronym></a>, by Avenger.
- <a href="https://gibberlings3.github.io/iesdp/"><acronym title="Infinity Engine Structures Description Project">IESDP</acronym></a>, maintained by igi and lynx.
- <a href="http://www.teambg.eu/?page=tools&amp;cat=32">BAM Workshop</a>, by Glenn Flansburg.
- <a href="http://www.shsforums.net/topic/57564-bamworkshop/">BAMWorkshop 2</a>, by Andrew Bridges.
- <a href="http://notepad-plus-plus.org/">Notepad++</a>, by the Notepad++ team, Don Ho, and the spellcheck plug-in.
- <a href="http://www.shsforums.net/files/file/1048-weidu-highlighter-for-notepad/">WeiDU Notepad++ Highlighters </a>, by Argent77.
- <a href="https://code.visualstudio.com/">Visual Studio Code</a>, modern, cross-platform editor.
- <a href="https://marketplace.visualstudio.com/items?itemName=BGforge.bgforge-mls/">Visual Studio Code - BGforge MLS</a> - Syntax highlighting and more.
- <a href="https://github.com/InfinityTools/InfinityAutoPackager/">Infinity Auto Packager</a>, automatically generates Infinity Engine mod packages.
## 

#### Copyright Information

###### Baldur's Gate Graphical Overhaul is not developed, supported, or endorsed by BioWare&trade; or Interplay/BlackIsle, Overhaul, Beamdog or the Wizards of the Coast. It was developed by AUTHOR, based on material from the game Baldur's Gate II and its expansion.
###### All mod content is &copy;AUTHOR.
###### Baldur's Gate II: Shadows of Amn and Baldur's Gate II: Throne of Bhaal &copy; TSR, Inc. The BioWare Infinity Engine is &copy; BioWare Corp. All other trademarks and copyrights are property of their respective owners.

###### This mod was created to be freely enjoyed by all Baldur's Gate II players, and its content is free of rights. However, it should not be sold, published, compiled or redistributed in any form without the consent of the author.
###### Please note that any and all redistribution and/or hosting of this mod is prohibited without permission from the author.

###### If there are any copyright issues or this statement needs revision, then please contact me and advise me what to do about it. Most notably, if you see any artwork in this mod that might conflict with Copyright rules, please let me know as soon as possible, and I will remove the conflicting content immediately.

###### The modding community for the Infinity Engine has been going strong for more than 10 years now, and is the culmination of thousands of unpaid modding hours by fellow fans of the game. Modders produce their best work and players get the best, well-supported mods when we all work together.
###### There are two big ways to upset this harmony. One is to claim someone else's work as your own. The second is to host and redistribute a mod without permission from the author(s).
###### Be kind to your fellow players and modders. Don't do either.</br></br>
<div align="right"><a href="#top">Back to top</a></div>


<hr>

## <a name="modding" id="intro"></a>Modding

The new version is very modular. This makes it not too difficult to add new content for areas.<br>
Is the area already included in the mod?<br>
Yes: Just add the new files to the appropriate folders under  :file_folder: bggo/base/... as well. <br>
No: Open the bggo.tp2 with a text editor and add the name of the area in the corresponding table ("bg1_areas", "bg2_tob_areas", "sod_areas", "bgee_areas", "bg2ee_areas"). Then the new files will be installed automatically. <br>
For the naming of the BG1 areas the labeling of EET is taken (BG0100), because the clarity of the area names is easier.<br><br>
For example, if we want to add new candles to an interior map:<br>
Create in the  :file_folder: bggo/base/are_patch/... a file with the name ARXXXX_are.tpa where ARXXXX is the name of the area.<br> Copy the code <br>
<sub><code>PATCH_DEFINE_ARRAY x_coord BEGIN 1235 235 785 END
PATCH_DEFINE_ARRAY y_coord BEGIN  847 333 753 END
PATCH_PHP_EACH x_coord AS index => x BEGIN
	LPM ~DELETE_EXISTING_ANIMATIONS~
	LPF fj_are_structure
	INT_VAR
		fj_loc_x = $x_coord("%index%")
		fj_loc_y = $y_coord("%index%")
		fj_schedule = 0b111111111111111111111111 //Hours All
		fj_flags = 0b00000000000000000001000001000011	// Visible, blend colours, not covered by wall, don't remove in combat
		STR_VAR
		fj_structure_type = animation
		fj_name = FLAME2S
		fj_bam_resref = FLAME2S
	END
END
LPM ~CLEAR_ARRAY~</code></sub> <br>
and add the correct coordinates. Now you have to check if the map appears in the lists of bggo.tp2. If not, you have to add the map to the list. Have a look at the examples in the existing files, there you can see different variants. <br>

Compatibility with other mods is also taken care of. For this you can use the above mentioned ARXXXX_are.tpa or also the ARXXXX_wed.tpa in the  :file_folder: bggo/base/wed_patch/... directory. Depending on what the compatibility requires, you can choose the appropriate files.
Example:<br>
TDDz: Here the are files must be patched. So we use for example the BG2900_are.tpa.<br>
GavinNPC: Here a door must be added to the wed file, so we use the BG3300_wed.tpa.<br>

Also with the searchmap you can prevent overwriting the files by using the SRmap_modding_tool. The ARXXXXSR.2da file created with this tool is always preferred to the corresponding ARXXXXSR.bmp. So only the changed pixels are added to the bmp file.


<hr>

## <a name="versions" id="versions"></a>Version History

#### Version 3.0 (Upcoming version)

By Yovaneth, Weigo

-completely revised version

- Initial release (Yovaneth).
<div align="right"><a href="#top">Back to top</a></div>
