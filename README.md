About
------
version 1.0<br>
QT theme (stylesheet) specially developed for FreeCAD (http://www.freecadweb.org/).<br>
It might work with other software that uses QT styling.

Installation
------
1. Place the .qss files and /images/ folder in the path that fits your OS:
  - OSX = /Users/[YOUR_USER_NAME]/Library/Preferences/FreeCAD/Gui/Stylesheets/images/
  - WINDOWS = C:/[INSTALLATION_PATH]/FreeCAD/data/Gui/Stylesheets/
  - LINUX = /home/[YOUR_USER_NAME]/.FreeCAD/Gui/Stylesheets/
2. Images used in the theme need full paths to be found by FreeCAD, so you should search the string  **[PATH_TO_IMAGES]**  and replace with the real path your computer needs to target the /images/ folder. Example:
  - **find** = [PATH_TO_IMAGES] <br>
  - **replace** = /Users/myName/Library/Preferences/FreeCAD/Gui/Stylesheets/images/

Customization
------
If you would like to change the overall look/style of the theme, just find and replace the "palette colors" listed in the start of the file:
- background darker
- background dark
- background normal and slightly darker
- background normal
- background light
- background ligher
- lists backgound
- lists backgound (alternate)
- selection darker
- selection dark
- selection normal
- selection light
- selection lighter

Caveats
------
- as said in Installation, full paths to images are needed, that means all these .qss files should be edited per user. I hope FreeCAD developers make a workaround about it.
- the "Task panel" is not stylable right now (FreeCAD 0.15), I hope it changes in the near future
- in app icons-buttons are designed in svg but are not stylable, that is, it's not possible to change them... I hope it also changes in the near future

Known bugs
------
- In OSX, height and width in "QMainWindow::separator:horizontal" and "QMainWindow::separator:vertical" produces a weird line when moving the separators

License
------
Copyright (c) 2015 Pablo Gil Fernández.<br>
The stylesheet uses some code from Colin Duquesnoy generic QT stylesheet

![Attribution-ShareAlike 4.0 International](http://i.creativecommons.org/l/by-sa/3.0/88x31.png)
This work is licensed under a [Creative Commons Attribution-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-sa/4.0/).
