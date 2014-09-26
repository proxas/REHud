REHud
=====

To install, 
go to Steam / steamapps / common / team fortress 2 / tf / custom / 
create a folder and name it, for example, hud / place resource and scripts in it. 

-----------------------------------------------------------

If you want to change the Ammo colors:

1. Go to your "resource" folder.
2. Then ClientScheme.res
3. At the top under // Garm3n Colors, there you can see what to do.
4. Save

-----------------------------------------------------------

Normal CrossHair:

Activate the crosshair by going to your scripts folder and then hudlayout. 
Change visible from 0 to 1.

If the crosshair isn’t centralized do the following:

1. Go to your scripts folder and then hudlayout.
2. Change the xpos and ypos values. (xpos is for horizontal and ypos is for vertical).
3. Start TF2 and see if it’s centralized.
4. If not, Alt+TAB and try another value. 
Go back into the game and type hud_reloadscheme in console.
5. Do this until you’re happy.

If you want to change the crosshair size go to your resource folder and then ClientScheme. 
Change the tall value to whatever you like.

If you want to change the colour go to your scripts folder and then hudlayout. 
Change the fgcolor to the colour you want. 
If you don’t know how to change to the colour that you want, i’ll help you now. 
There are four number combinations (1 2 3 4) and every combination are from 0-255. 
Combination 1 to 3 are RGB (Red Green Blue) and combination 4 are for the transparent value. 
If you for example want white it’s 255 255 255 255 and if you want green it’s 0 255 0 255. 
HERE (http://www.webdiner.com/annexe/hexcode/hexcode.htm) you’ll find most colours and RGB combinations.

(If the crosshairs isn’t centralized then you sometimes have to change “wide” and “tall” too, not just “xpos” and “ypos”)

(Some CrossHairs are combinations, you need to activate more than one)

-----------------------------------------------------------

Pulsing CrossHairs:

Activate the crosshair you want by going to your resource folder and then ui. Search for HudPlayerHealth. 
Change visible from 0 to 1.

If the crosshair isn’t centralized do the following:

1. Go to your resource folder and then ui.
2. Search for HudPlayerHealth.
3. Change the xpos and ypos values. (xpos is for horizontal and ypos is for vertical).
4. Start TF2 and see if it’s centralized.
5. If not, Alt+TAB and try another value. Go back into the game and type hud_reloadscheme in console.
6. Do this until you’re happy.

If you want to change the crosshair size go to your resource folder and then ClientScheme. 
Change the tall value to whatever you like.

If you want to change the colour go to your resource folder and then ClientScheme.res. At the top under COLORS you'll find "Garm3nHUDxHair" "125 245 0 255", 
change the numbers to your liking.
If you don’t know how to change to the colour that you want, i’ll help you now. 
There are four number combinations (1 2 3 4) and every combination are from 0-255. 
Combination 1 to 3 are RGB (Red Green Blue) and combination 4 are for the transparent value. 
If you for example want white it’s 255 255 255 255 and if you want green it’s 0 255 0 255. 
HERE (http://www.webdiner.com/annexe/hexcode/hexcode.htm) you’ll find most colours and RGB combinations.

(If the crosshairs isn’t centralized then you sometimes have to change “wide” and “tall” too, not just “xpos” and “ypos”)

(Some xHairs are combinations, you need to activate more than one)

-----------------------------------------------------------

If you want to change color on Demoman sticky ChargeMeter.

1. Go to your resource folder and then ui.
2. Search for HudDemomanCharge.
3. Under "ChargeMeter" change the numbers in "fgcolor_override" "0 255 0 255" to whatever you like.
   (White: "255 255 255 255")
   (Yellow: "255 255 0 255")
   (Green: "0 255 0 255")
   (Red: "255 0 0 255")
   (Blue: "0 175 255 255")
4. Save.

-----------------------------------------------------------
