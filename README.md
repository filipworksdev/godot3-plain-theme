# Godot 3 Simple Theme

This theme changes the look of Godot Editor itself. 

This is a Complete modification of Jay7c/jc.godot.plane-editor-theme. 
- Tested using Godot 3.4 rc2

This also includes the 2 fonts I am using in the look below 
- pixelfont is made by me and has a special license check under fonts/
- ubuntu is a monospace libre font that i use for my script since is smooth and readable

Also in the package you will find godot3-classic.tet. 
- This gives a more classic Godot 3 look of the text editor code style using before things like if, elif, else became their own colors for example all keywords used to be just red. 
- The node operator $ used to be blue and rest of node path folling was gray but this is no longer possible so I made all $nodepath a more subdued brown since blue looked too jarring
- I also changed the code line colors to be less pronounced

--------------------------------------------------

## Changes 

- Removes the forced blue accents allowing the color accent you defined in Editor settings to show though
- Fixed a lot of issues with inconsistent styles such as (tabs, tab container and debugger tabs and others)
- Most editor items are consistent and a show a gray background when selected (includes menu items, trees, editor and project settings, inspector properties, tabs and others)
- Removed all the forced fonts
- Fixed all the blue accents for vertical and horizontal scrollbars 
- There is still an issue present with 

--------------------------------------------------

## Install

- Clone repo 
- Set Editor->EditorSettings->Theme->CustomTheme to simple_theme.tres
    
--------------------------------------------------

## Look

<img src="https://raw.githubusercontent.com/filipworksdev/godot3-simple-theme/master/look.png">

