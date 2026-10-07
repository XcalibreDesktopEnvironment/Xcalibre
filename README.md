# Xcalibre Desktop Environment

The goal of Xcalibre is to be the world's greatest desktop environment, entirely customizeable and innovative, with features not found anywhere else.
This project is still in early development but it is somewhere close to half-way finished, it is not a fork of some other desktop environment, I am
one single developer building this from bare scratch in C++ for Xorg or hopefully also any other X-based server e.g (XLibre/XF86-based servers).
I've been working on this now for around 6 months and I'm somewhere around half-way finished with it.
I intend for this to be a highly capable programmer-friendly desktop for power users.

Below are a list of features.
- [x] represents features already present
- [ ] represents features to come

**Rendering is done on the GPU with OpenGL**
- [x] FPS control via general.xml
- [x] VSync control via general.xml

**Xcalibind, Xcalibre's keybind program**
- [x] 100% scriptable in either Lua or Bash, soon to be scriptable in Squirrel also via editing keybinds.xml settings. 
- [x] Keyboard mapping independent, Xcalikey is a program that you can use to decode the raw keycodes correlating to keystrokes used for the keybinds.
- [x] Potentially modal keybindings, you can create keybind modes allowing you to switch to different sets of keybinds via keybinds.
- [x] The ability to persist in a keybind's key-detection mode allowing the keybinds to be modal also in the vim sense of keybind modality, this also allows
keybinds to be multi-part, persisting until a keybind is detected where it is told to go back to normal mode.
- [x] Single-key global keybinds for stuff like [Print Screen].
- [x] Any key on the keyboard is bindable.
- [x] Console window to show the output of your scripts, can be used for quick notes.

**Xdialibre, Xcalibind's dialog program**
- [x] Fully integratable into your scripts and programs
- [x] Message box dialog
- [x] User input dialog 
- [ ] Color selection dialog
   - [ ] Will display colors as HTML, Hex, unsigned 32-bit integers, and unsigned bytes
   - [ ] Will contain an eyedropper tool that can be used across the screen
- [ ] Open folder dialog
- [ ] Open file dialog
- [ ] Save file dialog

**Xcalidoc, Xcalibre's user manual program**
- [ ] Will open .xcalidoc files and possibly also .man files as well
- [ ] Will contain animated images for easy illustration
- [ ] User manuals will be sufficiently detailed but tactically written for quick and easy consumption
- [ ] User manuals will be written with an easy XML-based language and pragmatic philosophy 

**Xcalishot, Xcalibre's screenshot tool**
- [ ] Will be capable of recording animations
- [ ] Simple screenshot tool
- [ ] Optionally through command line arguments also open with an interface for snipping specific rectangles
- [ ] Optionally also specific windows
- [ ] Optionally create animated images with a track recording-like interface

**Widgetization of any application with either a GUI or a TUI, including terminal emulators themselves**
- [X] Desktop or taskbar widgets are both possible by simply adding them to widgets.xml.
- [x] Every widget that comes with Xcalibre is just a normal executable GUI program that opens in a normal window
but is made into a widget via adding it to widgets.xml

**Fully designable via 32-bit bitmap files**
- [x] Window decorations
- [x] Taskbar decorations
- [ ] Popup menu decorations
- [ ] Hint window decorations
- [x] Desktop background image
- [ ] Optional desktop background executable so you can dynamically generate animations in code

**Entirely scriptable desktop context menu, literally every part of it**
- [x] Custom menu items can execute Squirrel or Lua scripts.
- [x] Custom submenus, certain types of submenus can be made to automatically display items based on the contents of a directory, scripted by a single script.

**Window management modes built-in**
- [x] Floating window management
- [x] Entirely scriptable tiling window management

**Themes**
- [ ] Themability is almost currently entirely possible but only the Default theme currently exists

**Native script interpreter** 
- [x] Interprets both Lua and Squirrel scripts

**Customizeable window titlebar buttons**
- [ ] Custom button images
- [ ] Custom buttons can execute a script based on left and/or right mouse button clicks
- [x] Default buttons for Opacity, Maximize, Minimize, and Close
- [x] Left clicking the Opacity button reduces opacity by 15% initially then 25% until 0%
- [x] Right clicking the Opacity button increases opacity by 25% until 100%
- [x] Left clicking minimize minimizes the window
- [ ] Right clicking minimize will minimize the window and also send a halt signal to completely free up processing power
- [x] Left clicking maximize maximizes the window
- [ ] Right clicking maximize will trigger an editable automatic tiling script for all unminimized windows
- [x] Left clicking the close button will close the window and kill the desired process

**Xcalitime widget**
- [x] A basic time/date widget for your taskbar
- [x] Clicking the time will pop open a window with a calander and a timer.
- [x] The timer executes a specified bash command or script when the count down is finished
- [x] Clicking on any day of the calander will allow the user to leave notes about that day for reminders.

**Xcalitask**
- [x] A taskbar widget allowing the user to view, raise, and minimize open programs
- [x] Double-click to teleport the mouse cursor to the middle of the window corresponding to the associated taskbar button
- [ ] Hold the right mouse button down on the task manager widget and move left or right to scroll the desktop
- [ ] Middle click or roll the mouse wheel downward to minimize all windows
- [ ] roll the mouse wheel upward to restore the previously minimized windows
- [x] Editable color-scheme via command line arguments

**Xcalifile**
- [ ] Xcalibre's task manager
- [ ] Entirely customizeable scriptable right-click context menu like with the desktop, editable via general.xml

**Xcalibre will come with its own C++ GUI toolkit called X++**
- [x] There are already a ton of libraries added to this, pragmatic libraries, I could go on for probably an hour about this so far.
- [x] Xcalibre is built with this library, and it continues to grow with development, I develop both projects at the same time.
- [x] Pragmatically written for ease of use and power
- [ ] xppmake will generate your makefiles automatically based on the headers you add to your source code

**Xcalifire**
- [ ] A program that runs in the background which will make all of your customizations hot-reloadable.

**Entirely compilable via g++**
- [x] Light weight
- [x] Will be tryable without installation to ensure satisfaction without sacrifice
- [ ] Fully informative installer will tell you exactly what changes are being made during install

**Hand-coded not vibe-coded**

**Plenty more innovative features to come**

-------------------------------------------------------------------------------------------------------------------------------------
-------------------------------------------------------------------------------------------------------------------------------------
-------------------------------------------------------------------------------------------------------------------------------------

**View progress updates, screenshots, and videos here**
t.me/xcalibredeskenv

**Hang out with the developer and/or request features here**
t.me/c/4473235011/1

