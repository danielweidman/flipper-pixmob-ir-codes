# PixMob IR Codes for Flipper Zero
Control your PixMob wristbands at home with a Flipper Zero!

This repo contains three files of IR codes:
1. pixmob_good.ir: Codes to set bracelets to any common color, and fade in or out of each color
2. pixmob_all_colors.ir: Codes to set bracelets to every possible color (with what reverse-engineering has found so far), but without the fade effects
3. pixmob_special.ir: Special codes to do things like random colors, enter motion sensitive mode on very old PixMob bracelets, and more. It is easy to mess up bracelets using these codes because some have persistent effects. I don't reccomend using this unless you are willing to mess up your bracelet and require a difficult reset.

I reccomend "pixmob_good.ir" as a starting place.

These files were generated based on the reverse engineering work detailed here: [https://github.com/danielweidman/pixmob-ir-reverse-engineering](https://github.com/danielweidman/pixmob-ir-reverse-engineering)
