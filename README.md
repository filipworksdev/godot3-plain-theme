# Godot 3 Simple Theme

This theme changes the look of Godot Editor itself. 

This is a Complete modification of Jay7c/jc.godot.plane-editor-theme. 
- Tested using Godot 3.4 rc2

This also includes the 2 fonts I am using in the look below 
- pixelfont is made by me and has a special license check under fonts/
- ubuntu is a monospace libre font that i use for my script since is smooth and readable

Also in the package you will find godot3-classic.tet. 
- This gives a more classic Godot 3 look of the text editor code style using before things like if, elif, else became their own colors for example all keywords used to be just red. 
- The node operator $ used to be blue and rest of node path following was gray but this is no longer possible so I made all $nodepath a more subdued brown since blue looked too jarring
- I also changed the code line colors to be less pronounced

--------------------------------------------------

## Changes 

- Removes the forced blue accents allowing the color accent you defined in Editor settings to show though
- Fixed a lot of issues with inconsistent styles such as (tabs, tab container and debugger tabs and others)
- Most editor items are consistent and a show a gray background when selected (includes menu items, trees, editor and project settings, inspector properties, tabs and others)
- Removed all the forced fonts
- Fixed all the blue accents for vertical and horizontal scrollbars 
- There is still an issue present with the sliders
- Feel free to report any issues or improvements here
- Changing borders from Editor settings doesn't work correctly with this theme (is both by design since it aims to be minimal and by limitation of the theme system because I cannot set border color to the chosen color accent I either set no borders or just gray) 

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

