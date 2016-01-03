This is a piece of software that I have written to make apt easier to use for new users to debian, ubuntu, or really any other debian-based distro.
To use the software it is recommended to either
  1. Build a bash script leading python to open the program and add it to /usr/bin/
EXAMPLE:
 "#!/bin/bash
python3 /PATHTOSCRIPT/"
  2. Or to directly add the script to /usr/bin/ and run "sudo chmod +x /usr/bin/updatesoftware". It should work just fine.

To execute the program, just run "updatesoftware" in the terminal emulator of your choice
# ubuntusoftwareupdater
