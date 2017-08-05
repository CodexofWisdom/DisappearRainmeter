# DisappearRainmeter
Dissappearing Rainmeter menu.

Please report any major bugs.

I am aware that the menu will not appear in monitors left of the primary. I believe it to be a limitation of MouseXY. If you find a fix (asside from making the far-left monitor primary), let me know!

Keep me updated on any cool changes or additions you make, as well.

Defaults Guide:

The top icon is an internet browser link. It defaults to Firefox.

The right icon opens a menu dedicated to chat programs. From top to bottom in the menu: Skype, Teamspeak, Mumble, Discord.

The bottom hover opens a game menu. From left to right: GogGalaxy, BattleNet, Steam, Origin, Misc. Left clicking these will open their programs. Right clicking any of these will open their folders. The misc opens a subfolder on hover that currently only contains Minecraft.

The left submenu is for everything else. From top to bottom: LibreOffice, My Computer, GIMP, Settings.

    My Computer submenu defaults are: Downloads, D drive, C drive, Dropbox.
    Settings defaults are Power off and CCleaner.
   
Adding icons is just a matter of finding the menu you want in the code and adding a new Meter. You will probably have to play with the positioning. Then just put a new picture in the Images folder and point the Meter to it. Then change the link to whatever you want to go to.

Editing existing icons is even easier. Just change the link and picture.

Adding a new submenu is a bit harder. I would recommend just copy-pasting existing submenu code and fiddling with the positioning.


Feel free to use this code however you like, as long as you give credit to myself and Fawxy (creater or MouseXY) where applicable.

Enjoy!

Installation guide:
[Video guide for the lazy](https://youtu.be/Q6MjpPuARsk).

0.) To use this menu, you are required to have Rainmeter installed (https://www.rainmeter.net/).

1.) Download the repository at https://github.com/CodexofWisdom/DisappearRainmeter.

2.) Extract the downloaded archive.

3.) Copy the extracted 'Menu' folder to the Rainmeter 'Skins' folder (DEFAULT: 'C:\Users\\%USERNAME%\Documents\Rainmeter\Skins').

4.) Copy the DLL files in the downloaded 'Plugins' folder to your Rainmeter 'Plugins' folder (DEFAULT: 'C:\Program Files\Rainmeter\Plugins').

5.) If you changed the default installation location of Rainmeter (DEFAULT: 'C:\Program Files\Rainmeter'), you will need to edit the EXE file, which is done by editing and compiling the AHK file included. Compiling AHK files requires Autohotkey (https://autohotkey.com/).

6.) To enable the skin, open the 'Manage skin' window in Rainmeter and load the 'Menu' skin by selecting 'menu.ini' inside the skin's folder and pressing LOAD. To set the paths of programs, press the EDIT button to open the INI file and insert paths where instructed.

7.) Make sure the skin's settings are set as on the following pictures: http://prntscr.com/g4fa8g, http://prntscr.com/g4fagl.

8.) Now launch the extracted EXE file to disable the Windows key's default action and set it as the hotkey for opening the menu. If you want to choose a different hotkey, you will once again need to edit the AHK file and compile it.

9.) If you wish to load the menu on Windows startup, place the EXE file inside the Windows Startup folder ('C:\Users\\%USERNAME%\AppData\Roaming\Microsoft\Windows\Start Menu\Programs\Startup') and make sure that it is enabled, alongside Rainmeter, to launch on startup in the Task Manager or 'msconfig' in older versions of Windows.
