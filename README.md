# Mega Man X Randomizer
---

## Disclaimer: 
This is will only work on windows computers and if you are having any problem running the program, make sure your
.NetFramework is up-to-date here: https://www.microsoft.com/en-us/download/details.aspx?id=48130
Also, this only works with Mega Man X NTSC v1.1 US :  Also known as Mega Man X Rev A

Make sure to check out the "Releases" option above for the most current build of the randomizer

## About
---

This will be a lengthy journey I'm sure.  With each update I'll list what has been fixed and also known issues going forward with patches.  Any checkboxes or radio buttons that have blacked out text will not be useable in any form and can't be clicked on.  These represent ideas we have but are not yet implemented in the actual program at this time.  They also don't represent everything we want to do for the randomizer just all ideas we have at the moment.  More will be added / implemented when we come up with them.

## Patch Notes of Current Build
---


### List of changes in new build: Version 0.83 6/19/2018

New Things (There are a lot of things to go over so let's get started! :D ):

* MSU audio patch now is fully compatible with every mode and setting in the randomizer!  This goes for applying the SD2SNES patch as well as the emulator patch!  You can now enjoy random boss health and i-frames with different audio now!!! 
* 4 New Game Play Modes!!!
   * Low Battery - In this mode, you start each life with a partially filled health bar of a random size.  For example, you could start each life with 6 health but your health bar can hold up to 20 health.
   * Frame Perfect - In this mode, every boss is only weak to the 1st level charge shot from your buster and nothing else.  This shot has a frame window of between 1-4 frames depending on the difficulty you choose for this mode.  A frame window is just how many frames X will have this charge before he hits his 2nd level charge.  While this sounds difficult, the catch is that every boss only needs to be hit 3 times before they die.
   * Vampiric (Experimental) - In this mode, whenever a boss damages you during a fight, they will gain that much health back (In Lite difficulty mode, they will gain half that amount back).  This mode is fully funtional but isn't quite done.  The boss health bars only update whenever you deal damage to them.  So that's something that will be fixed in the future.
   * Double Vision Rework(WIP) - Double Vision has been completely reworked to be more fun and enjoyable. In the default Double Vision mode, each boss (up to spider) will have a 50% chance to be a double fight. I have included additional options for this mode including fighting all bosses as double fights, the option of double Rangda (still causes crashes.....sometimes), and an actual working fast explosions box.  Fast explosions still renders the game unbeatable as Jedi Sigma, but it's there.
* Color Mode Rework
    * Bit Crush - In this mode, the color depth of the game can be reduced anywhere from 64 to 8 colors. (8 color mode is still in progress)
    * Apple II mode has been enhanced with a color picker.  If you click the green box next to this option, you can change the game from green and black to whatever color you want......and black! :D 
    * ZX Spectrum - This is more a faux ZX Spectrum color scheme, but it is so close that that is what I'm gonna call it.  I may make the colors more authentic in the future!
    * Palette Shift Rework - I've now changed Palette Shift from a radio button option to a checkbox option meaning that you can now palette shift ANY other graphics mode in addition to the vanilla game colors.  Feel free to experiment with all kinds of combinations for weird results.  Each palette shift is random, so results will always vary even with the same mode.
* Difficulty Bar - This bar at the bottom of the randomizer window allows you to set the overall max difficulty for any seed.  This will prevent more challenging (unfun) things from happening on seeds across multiple settings.  This way, any one regardless of experience with Mega Man X can make a seed and have some fun! :D
* Zero Knockback has been removed as an option as it was found out to be terribly buggy and causing the game to crash if you took damage near a wall.
* The UI is cleaned up and laid out even better than before! Every option grouping that has radio buttons now has a normal button to revert any choice back to the default.  Not sure why these weren't in to begin with.
  
Known Bugs:

* There is still a slight problem with random stages where you get credit for beating the stage you ended up playing instead of the stage you had selected from the stage select.
* There is a problem using both Random Mavs and Random Health / I-Frames.  
* There is a new found issue with Zero Knockback.  If you get hit while being on a wall or very close to touching one, the game will most likely crash.
* MSU audio patching overwrites boss health / i-frame code.  Should fix that


### List of changes in new build: Version 0.75 3/20/2018

Big update and a lot of things reworked!

Notes:
* UI completely reworked and sorted to make room for new features as well as future features to be added
* New Mode:  Colors -  This tab has all kinds of settings that will let you alter the colors of the entire game to various themes and patters.  All the colors altered in these modes are random and not hand picked sets of colors.  The randomizer does this on its own. This mode is still in development but will work close to 100%.  Some things aren't modified yet like effects that affect the entire screen such as explosions.  I will be adding more to this in the future.
* New Mode:  Music - There isn't much in here to start but that will hopefully change.  This will currently allow 2 things.  The first being the randomization of the stage music to anything in the game (not counting music that doesn't loop or boss fight music as both are annoying in their own way).  The second is a Punk Rock mode that alters the playback of all music in the game.  More will be coming to this mode including MSU-1 support.

Known Bugs:
* There is still a slight problem with random stages where you get credit for beating the stage you ended up playing instead of the stage you had selected from the stage select.
* There is a problem using both Random Mavs and Random Health / I-Frames.  
* There is a new found issue with Zero Knockback.  If you get hit while being on a wall or very close to touching one, the game will most likely crash.


If you find any glitches or something wrong, please leave a comment or get in contact with me on Twitter. :D
