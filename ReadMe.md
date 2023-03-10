<p align="center">
  <img alt="ImageExample" src="https://cdn.discordapp.com/attachments/737301647440740453/1077544580737662976/banner.png" width="750px">
</p>

# What the hell does this do?
This script's objective is to substitute screenshots from your Star Citizen screenshots folder for your [EAC](https://www.easy.ac/) loading screen, and to substitute a different screenshot each time the script is executed.

# History
This was originally created in 2022 by thorax on [Reddit](https://www.reddit.com/r/starcitizen/comments/rkmz93/fyi_we_can_have_custom_splash_screens_now_until/). I was kingflashroseG on Reddit when this post was originally made. I later added comments and a lot more QOL for people who weren't as tech-savvy as he was. I then created the .bat files and have been using them on my own system for the past year. If Thorax ever finds it, I will happily give him contributor credit and ownership of this project. He still deserves credit as the project's original creator.

# Requirements 🧾
- Python 3.8 or above (https://www.python.org/downloads)
  - Recommended version [3.10.2](https://www.python.org/downloads/release/python-3102/)
- Pillow .
  - Which should install with requirements.txt
- Patience
  - Take youre time if you need help just ask trust me


# How to use ✨
1. Download the [Project](https://github.com/DavidRoseLincs/SC-EAC-Screenshot-SplashScreen/archive/refs/heads/master.zip) into a zip folder.

2. Download and install [Python](https://www.python.org/downloads) if you haven't already.

   ![](https://i.alexflipnote.dev/2Ucs5Hf.png)
3. Open CMD/Terminal inside this folder.
   - On Windows, open a `command prompt` as administrator. Type `cd` with a space and drag the desired folder into it. Press enter.

 ![](https://i.alexflipnote.dev/7PvV4Eo.png)

4. Install `requirements.txt` with the command `pip install -r requirements.txt`
   - If you are on Windows, you might need to run command prompt as Administrator)
   - If you do already have it installed, you might have forgotten to put it in PATH Reinstall it and make sure to check the box that says "Add Python to PATH" And Or PIP

![](https://i.alexflipnote.dev/4QPnZiX.gif)

## ^^ all of the text above is from https://github.com/AlexFlipnote projects and is a good standard to have when giving python scripts to others.

5. Once you have installed requirements.txt, move all the stuff from inside "Move Files in This to a Preferred Space" to a folder that you can remember and find with ease. 

6. press the start_Basic.bat.

# Makes the script Automatic OPTIONAL:

- now their is two Bat files still left over depending on youre prefrence

  - "RSI Launcher.bat" Boots the launcher normally with the script ran (You will need to edit the bat to double check its openning stuff in the right locations)

  - "RSIShaderWipeLaunch.bat" Boots the launcher with a shader wipe and a script ran (you will need to edit the bat file to double check its openning stuff in the right locations) 

- After you have edited them, right click on either one or both and create shortcuts for them. You can then move them to your desktop, remove your original RSI Launcher shortcut, and then go into the properties of the shortcuts and give them icons and edit their names to look identical to a normal boot.


# Help needed?
Join [ARMCO](https://discord.gg/armco) and ask for kingflashroseG#5130 OR look in the [Thread](https://discord.com/channels/222052888531173386/1077537871382196314).

Hope you enjoy it :I

# Contributors
Big thanks to all of the people who worked on this project!

<a href="https://github.com/DavidRoseLincs/SC-EAC-Screenshot-SplashScreen/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=DavidRoseLincs/SC-EAC-Screenshot-SplashScreen" />
</a>


# To the future
- I'd like to replace the carousel (Wallpaper's) in RSI launcher with screenshots as well, but I'm not sure how to achieve it just yet.

- allowing you to select your directory only once rather than having the locations hardcoded into each system [ACHIEVED AS OF 10/03/23]

- There is a potential that this project, which may have originally been created for Star Citizen's [EAC](https://www.easy.ac/), will be renamed and modified to work for as many [EAC](https://www.easy.ac/) games as possible.
