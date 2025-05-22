# EX-CSB1
Open source EX-CSB1 CommandStation / Booster

Using the Bouni JLCPCB plugin to create the production files (gerbers) and handle all the parts subtitutions and rotations. Get the plugin from here:
https://github.com/Bouni/kicad-jlcpcb-tools

If your parts show up in the Kicad gerber viewer or in the JLC visual tool, import the corrections from our dcc-ex-rotation-corrections.csv file in the "support_files"folder.

 C:\Users\<user_name>\Documents\Kicad\<version>\3rdparty\plugins\com_github_bouni_kicad-jlcpcb-tools\jlcpcb
 
 Modified to include Booster Com connection that ties the DC power supply gnd between a command station and booster. I did this to eliminate any potiential problems.
 
 Removed the dual I2C headers from the board to make room for the new booster connection.
 
 Fixed the serial interface to be Arduino compliant.
 
 Added an option to provide vin power out by jumper (enabled by default).
 
 Added an option to provide ioref out by jumper (disabled by default).
 
