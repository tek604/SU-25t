# SU-25t
DCS configuration and files
Pepega Squadron Liveries
========================

Location Of Controller Configs
==============================
You can find the controller configs in the following folder:

C:\Users\<user_name>\Saved Games\DCS\Config\Input\<plane>\<controller_type>

Adding controls
===============
If anyone would like to add any controls, you will need to send me the following file(s):

<controller_name> {<controller_guid}.diff.lua

And export your controls to HTML (via the "Make HTML" button in the controller config screen in game.

Compress all the files, and contact me on discord.

GUID Update
===========
If the GUID of your device changes (for example, after updating firmwire), then you can rename the files located in the folder listed above.

The following method worked for me:

1) Start DCS, select the plane, and export to HTML without changing anything. This will give you the new device identifier (name & GUID).
2) Exit DCS.
3) Open the folder listed above, and rename the required files, using the name of the HTML file generated in step 1. Remember that the file should be named "*.diff.lua"!
4) Start DCS, and make sure the controller behaves as expected.
