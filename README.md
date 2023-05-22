# RGS_MBU-R
Customizations for RGS Motion Blue Unified Revamped edition of Batocera.

The files are for Batocera 36 (stable) only!

1. To Active the systems use a Windows PC and install winscp (https://winscp.net/eng/download.php)

2. Connect to Batocera with winscp to Batocera use hostname:batocera username:root password:linux

3. In winscp on the right side browse to /usr/share/emulationstation

4. copy (or drag and drop) es_systems.cfg from this directory to /usr/share/emulationstation on Batocera (overwirte: yes)

5. Next browse to /usr/share/batocera/configgen and copy configgen-defaults.yml (overwirte: yes)

6. Now in winscp in the toolbar select: "Commands" and select "Open Terminal" it will ask to open a Window, say "YES"

7. You can now typ in commands to execute. Type in "batocera-save-overlay" without the quotes and press execute

8. You must see this text appear:

/userdata/system$ batocera-save-overlay
Making /boot writable...
Mounting the overlay file...
Saving the real overlay to disk...

If you don't see this, start again from step 3.

9. After batocera-save-overlay return to Batocera and check if the new systems pop-up, you may have to run update gameslist from ES menu.

10. Most times its best to also reboot your Batocera machine.
