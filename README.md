# DisableNitrosensekey
Disable the NitroSense dedicated keyboard button

I googled around for ages to find a solution to this myself without luck so made it myself.
Nitrosense is a program by acer that has been given a dedicated hardware button on its laptop keyboards. Unfortunately, they chose to replace the numlock key with it so it's a prime target for accidental hits. When pressed it opens a bloated, slow-to-open program for fan control. Something you never would want to use more than once.

There's no way to disable it, and any workarounds are sketchy at best.

This script simply hooks into the key and does nothing. I added a beep so that you knew when you'd pressed it accidentally.
I thought about remapping it, but honestly, the only thing I would ever want the button that's meant to be numlock to do is be numlock, and then you have two numlock keys next to each other, plus if I wanted it to work with CapShift I'd need to do some sort of loop to repeatedly spam the numlock sendkey to replicate being held etc. I figured just beep and do nothing was the best solution.

# Autohotkey
This is an AutoHotkey Script. To create an executable from it download AutoHotkey from autohotkey.com and use AHK2EXE to compile it into IdleLock.exe
