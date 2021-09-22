## Bruker 400 MHz NMR Spectrometer Shimming Procedure
MB | v20210922

This procedure should only be performed by the Instrumentation Specialist.

## Software Startup and Process
1. The username for the computer is nmrsu.  The password is "topspin."
1. Double-click the TopSpin 4.0.9. icon.  A window similar to command prompt will open before TopSpin opens.
1. Obtain the autocalibrate sample if it is not already placed in the sample changer.  The sample should live in spot 24.
1. Insert the autocalibrate sample into the magnet by clicking "Acquire" followed by "Sample."  Then click "Insert sample with sample changer."  A window will appear asking for the sample location.  Enter the location of the autocalibrate standard and click "Ok."  The instrument will load your sample.
1. With the sample in the magnet, click "Lock" also under the "Acquire" tab.
1. Select your solvent for the standard which is **H2O + D2O.**  Click "OK" to begin the locking process.
1. Once the lock is complete, ensure the sample is **not** spinning.  Click "Spin" followed by "Turn sample rotation off."  Wait for the instrument to say the sample has stopped spinning.
1. In the command line of TopSpin, type **topshim gui** and then press "Enter."  A new window will appear.
1. Within this window, select "3D" as the dimension.
1. Change "Optimse for" to "1H."
1. Now click "Start" under **"CONTROL."**  The instrument will begin the shimming process.
1. Once the shimming is complete, save the shims using "wsh" in the command line followed by "Enter."
1. Name the shims as the date they were created and then click "Write."

## Setting The New Shims for Automation
1. Type "iconnmr" in the command line and press "Enter."
1. With the Automation window open, click "Configure."  A window will appear asking for a password.  This password is "bruker."
1. In the Configuration window, locate the "Lock/Shim Options" in the left pane.  Click this so that the "Solvent/Probe Dependencies" option is available.  Double-click this to open the window.
1. Ensure that the "Enable Shim File Loading" is enabled.  Do not change the "Probe Type to associate shim files with" option.
1. Beside the line "Copy this shimfile to all entries for this Probe" option, click the folder icon.
1. Find the shimfile you created earlier with the **wsh** command and click "Open."
1. Clcik the "Copy" button next to the folder icon used in the previous step to copy the shimfile to all solvents used with the probe.
1. In the top-left of the IconNMR: Configuration window, click "File" followed by "Save."
1. The configuration window can now be closed and instrument use resume as normal.
