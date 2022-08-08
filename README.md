# PixMob IR Codes for Flipper Zero
Control your PixMob wristbands at home with a Flipper Zero!

These IR codes were generated based on the reverse engineering work detailed here: [https://github.com/danielweidman/pixmob-ir-reverse-engineering](https://github.com/danielweidman/pixmob-ir-reverse-engineering)

https://user-images.githubusercontent.com/44669548/182740762-0dfe8110-97fe-4c29-bb5d-7f023f072f9b.mp4

### Files
This repo contains three files of IR codes:
1. `PixMob_main.ir`: Codes to set bracelets to any common color, and fade in or out of each color
2. `PixMob_all_colors.ir`: Codes to set bracelets to every possible color (with what reverse-engineering has found so far), but without the fade effects
3. `PixMob_special.ir`: Special codes to do things like random colors, enter motion sensitive mode on very old PixMob bracelets, and more. It is easy to mess up bracelets using these codes because some have persistent effects. I don't recommend using this unless you are willing to mess up your bracelet and require a difficult reset.

I reccomend `PixMob_main.ir` as a starting place.

### How to use
Copy one of the IR code files (start with `PixMob_main.ir`) into the `infrared` folder of your Flipper Zero SD card. You can do this either with qFlipper or by taking out the SD card, mounting it on your computer, moving the files, and putting the SD card back into the Flipper. 
From there, look under your "Saved Remotes" in the "Infrared" app for the relevant new remote and try sending some signals!

