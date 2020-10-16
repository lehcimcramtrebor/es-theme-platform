In each system folder, you can customize your theme illustrations and positionning and add a custom background, logo, controller or video snap without any modification in theme.xml.

IMPORTANT: 

You can duplicate a theme folder and add "_alt", for examples: "mame_alt", "snes_alt", "wonderswancolor_alt" etc..
If an alternative version exists, Emulationstation will use it. So you can modify, test and if you are not satisfied, delete your "_alt" folder.
If you are satisfied you can delete original folder and rename your or use both.


ADDING CUSTOM ARTWORKS:


	You can add multiple custom files in each folder, see readme.txt in appropriate folders.
	
	REGIONS: For custom logos, illustrations and controllers you can use different regions, see Readme.txt in different folders.



ILLUSTRATIONS:


	Illustrations are transparent ".png" files, you can place different illustrations in different zones:

		-Back left
		-Back center
		-Back right

		-Left
		-Right



	All files must be named "art.png", "art_us.png" or "art_jp.png" and must be placed in appropriate folder in the "illustrations" folder.


	Illustrations use region settings, for console image you can name files:

		-"art.png" (by default for EUR)

		-"art_us.png" (for US Region)

		-"art_jp.png" (for Japan Region)


LAYOUT SETTINGS:


	Edit "_LAYOUT_SETTINGS.xml" file to use different options for color, positionning etc.. and don't forget to specify if your system's theme
	is 16:9 or 4:3 system (Example: snes is 4:3 system, wiiU is 16:9 system)

	"_LAYOUT_SETTINGS.xml" file is not a standard .xml file, it's a variable system i've created to simplify using by beginners.

	These settings have effect on both FULLHD or VGA theme ratio, so if you modify the theme for your use only, you will problably working
	on the same system you play.

	But if you want to SHARE YOUR WORK WITH OTHERS, you can specify special shifting for 4:3 screens, to do this you must work on 16:9 system to
	edit "_LAYOUT_SETTINGS.xml" , and if after testing you are not satisfied by 4:3 result you must edit "VGA_LAYOUT_SETTINGS.xml" and edit shifting variables in this file for theme's vga mode.

	All variables are detailed in these files.


Note for vga mode, "_VGA_LAYOUT_SETTINGS.xml" have only parameters you should need, but if you are advanced user and you want more control you can duplicate "_LAYOUT_SETTINGS.xml" and rename it "_VGA_LAYOUT_SETTINGS.xml", and edit your file.






Why i haved do all these settings? First because it's fun, seriously, you can create many different looks with this system and you can share a theme folder
with others.



For theme settings, you can overwrite general parameters for only one system, just edit "_SYSTEM_THEME_SETTINGS.xml" file in "specifics" folder.