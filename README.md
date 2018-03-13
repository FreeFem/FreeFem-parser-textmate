# freefem extension for TextMate


## New users

Download TTextMate version 2.0-rc.4 or more from 

https://github.com/textmate/textmate/releases/tag/v2.0-beta.11.12

Install it

Double click on the FreeFem.tmbundle and accept the installation.

## What it does

1. Double click any .edp file and it will load in TextMate with the syntax coloring setup « freefem ».

2. Color syntax is activated. Choose your setting from menu View/Theme
It looks best with Theme Blackboard (dark background) or Mac Classic (white background) 

3 Code folding is also enabled

3. Launch freefem++ on the file displayed in the front window with the command cmd+R

Note that the file is saved before the launch.

Note that if you prefer the command cmd+shitf+r to launch FreeFem++ you must remove it from the Make Bundle.


## Technical 

The freefem TM bundle is not registered as part of the TextMate distribution so it is stored in your mac library in your partition (not in the general library) accessible by the finder menu “Go” when the keys cmd and alt are pressed together with the mouse action

/Users/YourName/Library/Application\ Support/Avian/Pristine\ Copy/Bundles/FreeFem.tmbundle

When you modify the freedom bundle from within TextMate by editing some commands, then the changes are stored in 

/Users/YourName/Library/Application\ Support/Avian/Bundles/FreeFem.tmbundle

## Upgrades and Bugs

If you double click on Freefem.tmbundle in an environment were it or an older version was already installed, it will take the place of the older version in 
/Users/YourName/Library/Application\ Support/Avian/Pristine\ Copy/Bundles/
Any changed you did to the factory settings were stored in
/Users/YourName/Library/Application\ Support/Avian/Bundles/FreeFem.tmbundle
So they will be preserved. If you want to remove them you must remove the above file.
 
 If  FreeFem.tmbundle does not install properly you can copy past this distribution of FreeFem.tmbundle into
the folder
/Users/YourName/Library/Application\ Support/Avian/Bundles/
and to be on the safe side copy also the distribution module in 
/Users/YourName/Library/Application\ Support/Avian/Bundles/


