<div align="center"><img src="https://cartelera.elpais.com/assets/uploads/2018/11/12120553/F_09063.jpg" alt="Cartelera de Cine EL PAÍS"></div>

# DrMartyMcWho's MacOS Video Screen Saver
A screensaver for Mac that allows you to choose any video to play as your screensaver for as many monitors as you have.  It automatically detects how many monitors you have and lets you choose multiple videos for each screen.  Currently works on MacOS Sequoia (15), but hasn't been tested on other MacOS versions.

## To install
1. Download the repository
2. Unzip the file
3. Double click the DrMartyMcWhoSaver.saver to install
4. Accept any prompts

## How to Configure
1. In System Settings > Screen Saver select the DrMartyMcWhoSaver from Other
2. Select Options to the right of the Screen Saver preview
3. Select a video for each display, can be either different videos or the same
4. Select "Allons-y!" and preview to make sure it works.
5. Be sure to select the DrMartyMcWhoSaver as your screen saver for both screens

## Troubleshooting
If you are getting black screens 
- In preview try "killall legacyScreenSaver" in terminal then try the screen saver again.  Some people have some default settings in legacyScreenSavers that might interfere.  
- This could also be your storage access permissions.  Move the video to /Users/yourcomputer/Public.  Public folder bypasses storage access.

If you can't get a video to appear in the other screen
- Be sure to check that the Screen Saver is selected for both screens.  Simply selecting a video for that screen isn't enough.  The screen saver must be selected on each screen.


Report any additional bugs and I'll look into it.
