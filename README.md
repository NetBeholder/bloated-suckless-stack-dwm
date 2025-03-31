# About
My bloated fork of suckless DWM
## Patches
Applied patches are:
- status2d-systray
- statuscmd-status2d
- alwayscenter
- attachbottom
- bakkeby/cyclelayots
- bakkeby/cfacts-vanitygaps:
	- cfacts
	- vanitygaps
- bakkeby/fullscreen-compilation-tagswapmon:
	- fakefullscreenclient
	- togglefullscreen
	- tagmonfixfs
	- losefullscreen
- bakkeby/tagallmon
- inplacerotate
- bakkeby/pertag-monitorrules:
	- pertag
	- monitorrules
- pwkl
## Appearance
* Color scheme: *gruvbox-material*
* Main font: *JetBrains Mono Nerd Font*
* Bar: *dwmblock-async*

![alt text](https://github.com/NetBeholder/bloated-suckless-stack-dwm/blob/main/screenshot.png)
## Layouts
Available layouts:
* tile
* monocle
* spirale
* dwindle
* deck
* bstack
* bstackhoriz
* grid
* nrowgrid
* gaplessgrid
* centeredmaster

Disabled layouts:
* horizgrid
* centeredfloatingmaster

## Keybindigs
MODKEY == win key
|Keyboard shortcut| Description|
|--|--|
|MODKEY + Shift + Return|Open terminal (alacritty)|
|MODKEY + p|Open dmenu|
|MODKEY + b|Show/hide bar|
|MODKEY + Return|Zoom function|
|MODKEY + 0|View function
|MODKEY + Shift + 0| Tag function
|MODKEY + Shift + c|Kill client|
|MODKEY + Shift + q| Quit from DWM|
|MODKEY + [1..9]| Tags 1..9
|MODKEY + [j,k]| Move focus between clients|
|MODKEY + Shift + [h,j,k,l]|Rotate clients in/between stack/master|
|MODKEY + [{,}]|Cycle through layouts backwards/forwards|
|MODKEY + [-,=]|Decrease/increase number of masters|
|MODKEY + [h,l]|Decrease/increase mfact (between master and client's stack]|
|MODKEY + Ctrl + [h,l,o]|Decrease/increase/reset cfact (between clients in a stack)|
|MODKEY + Shift + [=,-]|Decrease/increase gaps|
|MODKEY + [,Shift] + g|Show/hide/reset gaps|
|MODKEY + [,Shift] + f|Toggle fullscreen/mark client as fakefullscreen client|
|MODKEY + [comma,period]| Focus previous/next monitor|
|MODKEY + Shift + [comma,period]|Move client to previous (next) monitor|
|MODKEY + Control + [comma,period]|Swap all clients between open tags of previous (next) and current (active) monitors|
# Refs
0. https://dwm.suckless.org
1. https://github.com/bakkeby/patches/tree/master/dwm
3. https://github.com/sainnhe/gruvbox-material
4. https://fontawesome.com/v4/cheatsheet
