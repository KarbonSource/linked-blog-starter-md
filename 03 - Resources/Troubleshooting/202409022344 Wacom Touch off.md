---
date: 2024-09-02
tags:
  - Tech/Linux/Terminal
  - Tech/Linux/Scripting
---
# Wacom device list command
xsetwacom --list devices

# Wacom Disable Touch Command
xsetwacom set "Wacom Intuos Pro M Finger touch" touch off

# Run command on startup
1. open text editor
2. 1st line should be "#!/bin/sh"
3. 3rd line should be "xsetwacom set "Wacom Intuos Pro M Finger touch" touch off"
4. Save as .sh
5. make a new folder in home called "bin" and put your .sh in folder
6. open start up applications and select your .sh

# Links

https://www.autodesk.com/support/technical/article/caas/sfdcarticles/sfdcarticles/How-to-disable-the-Touch-Ring-and-ExpressKeys-for-a-Wacom-Tablet-on-CentOS-Linux-in-Flame.html

https://www.youtube.com/watch?v=XTnhg2PAllY