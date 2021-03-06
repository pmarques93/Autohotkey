# Mappin' Auto Cast Ragnarok Online (M.A.C.R.O)
Let user assign a macro to a button by drag the thumbnail image into the desired keyboard button.

blog post: [http://ragindex.blogspot.com/2016/09/new-mappin-auto-cast-ragnarok-online.html](http://ragindex.blogspot.com/2016/09/new-mappin-auto-cast-ragnarok-online.html)

## Description
**M.A.C.R.O Setting.ahk** - A GUI to help user configure 'M.A.C.R.O.ini'

**M.A.C.R.O.ahk** - Read from 'M.A.C.R.O.ini' and assign macro to keyboard buttons

I seperated the scripts here to maximize in-game performance.

### Picture
![GUI](https://github.com/thanhn062/Autohotkey/blob/master/Ragnarok%20Online/Mappin%20Auto%20Cast/screen_shot.png?raw=true "Screenshot")

# Guide

_How to use_
1. Drag icons from the stacks to a button.
2. Click "**SAVE CHANGES**"
3. Click "**Run 'M.A.C.R.O.exe'**"

## Note
I will use the button **F1** and **100ms** delay for all the macro examples below.
( *1000ms = 1s )

1. **Skill Macro**

* ![SM](https://github.com/thanhn062/Autohotkey/blob/master/Ragnarok%20Online/Mappin%20Auto%20Cast/Mode/SpamMacro.bmp?raw=true "Spam Macro")

* _Note_: good for smart casting abilities that let you pick a target.

* _Function_: When F1 press, Loop(F1 -> click -> wait 100ms) until F1 release

2. **Usable Macro**

* ![UM](https://github.com/thanhn062/Autohotkey/blob/master/Ragnarok%20Online/Mappin%20Auto%20Cast/Mode/Usable.bmp?raw=true "Usable Macro")

* _Note_: good for using potions.

* _Function_: When F1 press, Loop(F1 -> wait 100ms) until F1 release

3. **Chain Macro**

* ![CM](https://github.com/thanhn062/Autohotkey/blob/master/Ragnarok%20Online/Mappin%20Auto%20Cast/Mode/Chain.bmp?raw=true "Chain Macro")

* _Note_: press a chain of buttons with delay of your choice. "Q, W, E" will be use as an example.

* _Function_: When F1 press, Loop(Q -> wait 100ms -> W -> wait 30ms -> E -> wait 200ms) until F1 release

4. **Self Cast**

* ![SC](https://github.com/thanhn062/Autohotkey/blob/master/Ragnarok%20Online/Mappin%20Auto%20Cast/Mode/SelfCast.bmp?raw=true "Self Cast Macro")

* _Note_: Cast at self / center of screen

* _Function_: When double press F1, cast at yourself

5. **2-Hotkey Bar**

* ![SC](https://github.com/thanhn062/Autohotkey/blob/master/Ragnarok%20Online/Mappin%20Auto%20Cast/Mode/2HK.bmp?raw=true "Macro")

* _Note_: this hotkey bar was design to be manually click, but you now assign hotkey too.

* _Function_: double click at the recorded coordinate
