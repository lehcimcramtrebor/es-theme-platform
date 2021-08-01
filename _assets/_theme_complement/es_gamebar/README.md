# GAMEBAR_FOR_ES

---------------------------------------------------------------------------------------------------------------------------------------
This folder is a gamebar module to use in your theme creation, compatible with Retrobat4+ and BatoceraV31+.
---------------------------------------------------------------------------------------------------------------------------------------

FOR USE IN NEW THEME, if you use this on a theme where theses functions has already defined, this could  be partially unfunctionnal.

For Example add this folder at root of your theme and add this line to your theme.xml just before "</theme>" line at the end of file:

<include>./gamebar/gamebar.xml</include>

You can put the folder in the location you want, so you must adjuste the include path.



---------------------------------------------------------------------------------------------------------------------------------------
To Adapt with old themes, be sure to delete predefined occurences to: "md_developer", "md_releasedate" and "md_rating" or any other can
be in conflict with gamebar in your old code.
---------------------------------------------------------------------------------------------------------------------------------------
Open the gamebar.xml file and at head of file delte views you don't use.

For example:

<view name="detailed,video,grid,gamecarousel"> <!-- DELETE VIEW YOU DON'T HAVE IN YOUR THEME -->
---------------------------------------------------------------------------------------------------------------------------------------

![0](https://github.com/lehcimcramtrebor/GAMEBAR_FOR_ES/blob/master/screenshot.png)