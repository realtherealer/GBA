# AgbEMU, a free online GBA emulator.

Open-Source fork of unblockedphs' GBA Emulator!

# Some helpful things:

This emulator has a built-in higher performance mode (OverChargeMode). It allows all games to run faster than they regularly would by booting framerates and doing more checks in the code than normal. It is currently not "publicly" available to access due to stability issues, but can be activated by doing the following:

1. Using the EA version (emuAEagb) automatically switches to OCM instead of the normal one. This will require you to provide your own **legally obtained** roms, which we cannot provide assistance with.
2. Changing the game link during a game can enable OCM, however has a high chance of disabling volume due to the way the sound script works. Change the link from ..launcher.html.. to ..launcherOCM.html..
3. Forking this build, deleting launcher.html and then finally renaming launcherOCM.html to launcher.html. This will automatically boot into OCM mode as the regular launcher.
4. All games that have a "++OCM" at the end of their names on the game page will launch the selected game into OCM mode.
5. Manually enabling OCM from the developer console. Go to sources and edit launcher.html. Replace its contents with launcherOCM.html.

**I only recommend using OCM if you are actually experiencing issues. It can speed up the game too much for devices already running high fps counts as it determines the run speed by the amount of fps you get. If you are experiencing visual issues or other problems, it may be due to smooth mode being enabled. Although this can be disabled, it must be done within your own fork or using the EA version.**

The audio module is somewhat bugged, mainly when the page refreshes. This is known but a fix is currently not being worked on.
