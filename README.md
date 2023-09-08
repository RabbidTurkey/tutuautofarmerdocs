# Turkey Autofarmer Documentation

# Installing Python
1. Go to https://www.python.org/downloads/ and download the latest python version (should be Python 3.11.5)
![image](https://github.com/RabbidTurkey/tutuautofarmerdocs/assets/76893259/0b28e5d3-ffcc-4e90-b754-1d6727b0e4bb)

2. Scroll down to the bottom of the page and download the installer (should be called Windows installer (64-bit))
![image](https://github.com/RabbidTurkey/tutuautofarmerdocs/assets/76893259/4eead1cc-e68a-4481-a746-f7e83252b836)
3. Proceed with installation process. Make sure to tick the `ADD TO PATH` checkbox before beginning installation - only if you're asked

# Installing ADB
1. Go to this link: https://developer.android.com/tools/releases/platform-tools
2. Download the right ADB based on your device as shown in the image below
![image](https://github.com/RabbidTurkey/tutuautofarmerdocs/assets/76893259/2e7c0337-549e-43f9-8e81-17b867547b9a)
3. A folder should download, extract the folder

# Setting up your autofarmer folder
1. Navigate to the directory where you have Python involved. You can do this by opening the Python app you have installed.
2. Open file
3. Create `new folder`. Name it whatever you want.
4. Place 2 files from the ADB folder - `adb.exe` and `AdbWinApi.dll` into the `new folder`
5. Tutu will send you 3 files - `autofarmer.py`, `coords.txt` and `settings.json`. Place these 3 files into the `new folder`

This is what the contents of your new folder should look like:
![image](https://github.com/RabbidTurkey/tutuautofarmerdocs/assets/76893259/07fa441f-52c0-4335-bdd3-72c181d26432)

# Download required modules
1. Open up command prompt on your device
2. Enter the following commands one at a time: `pip install pure-python-adb`

# Setting up emulator
1. Go to your emulator settings
2. Make sure your emulator's dimensions are 1280x720 pixels
3. Go to `other settings` in emulator settings and enable ADB debugging.
4. Click on save

# Setting up game
1. Just save your 5th army preset as what you want to farm with. For example t2 cav, or t4 cav

# Customizing your autofarmer
You will have received 3 files from me - `autofarmer.py`, `coords.txt` and `settings.json`
1. `autofarmer.py` -> ignore
2. `coords.txt` -> this is the list of all your coords. Save them in an x y format. Image attached below for reference (coord list with coordinates of 2 castles):

![image](https://github.com/RabbidTurkey/tutuautofarmerdocs/assets/76893259/06e188fa-154a-4bf0-a8d6-bcda90a4144c)

3. `settings.json` is pretty self explanatory: 
 - start_position - your castle's coordinates
 - travel_speed - your travel speed (can be found in your game settings under Expedition boosts)
 - troop_tier - the tier of troops you want to farm with, so t1/t2/t3/t4
 - troop_form - the form of troops you want to farm with, choose cavalry ofc

![image](https://github.com/RabbidTurkey/tutuautofarmerdocs/assets/76893259/ec8cbb88-515f-433f-83e9-78b9ceb581a5)

# RUN THE AUTOFARMER
You're finally good to go!! You can create a shortcut for the `autofarmer.py` file and run it whenever you want. Follow the prompts once you run it, and you should be up and running!

