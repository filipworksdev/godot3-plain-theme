# Godot 3 Simple Theme + Godot 3 Classic text editor theme

This theme changes the look of Godot Editor itself. 

This is a Complete modification of Jay7c/jc.godot.plane-editor-theme
- Tested using Godot 3.4 rc1

This repo also includes the 2 fonts I used in the look below 
- pixelfont.ttf is made by me and has a special license check under fonts/ folder
- ubuntu.ttf was not made by me and is a monospace libre font that I used as a code font

Also in the package you will find godot3-classic.tet which is for the Script text editor
- This gives a more classic Godot 3 look of the text editor code style. For example in recent Godot versions if, elif, else became their own colors and this style brings back the original look making all keywords same red color.
- The node operator $ used to be blue and rest of node path following was gray but this is no longer possible so I made all $nodepath a more subdued brown since blue and default green looked too jarring
- I also changed the code line text color to a more subdued gray

--------------------------------------------------

## Changes 

- Removes all the new blue checkmarks, radio buttons and switches (the sliders are still blue)
- Removes the forced blue accents allowing the color accent you defined in Editor settings to show though
- Fixed a lot of issues with inconsistent styles such as (tabs, tab container and debugger tabs and others)
- Most editor items are consistent and a show a gray background when selected (includes menu items, trees, editor and project settings, inspector properties, tabs and others)
- Removed all the forced fonts
- Fixed all the blue accents for vertical and horizontal scrollbars 

--------------------------------------------------

## Known Issues

- There is still an issue present with the sliders look off and use the new forced blue accented highlights.
- Changing borders from Editor settings doesn't work correctly with this theme (is both by design since it aims to be minimal and by limitation of the theme system because I cannot set border color to the chosen color accent I either set no borders or just gray) 
- Feel free to report any issues or suggestions in this repo

--------------------------------------------------

## Install

- Clone or download this repo 

For Godot3 Simple Theme
- Set Editor->EditorSettings->Theme->CustomTheme to godot3-simple-theme.tres file

For Godot3 Classic tet
- Go to Script tab and File->Themes->ImportTheme and import the godot3-classic.tet file 
    
--------------------------------------------------

## Look

<img src="https://raw.githubusercontent.com/filipworksdev/godot3-simple-theme/master/look.png">

Enjoy.
filipworksdev

