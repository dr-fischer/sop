# Thermo Nicolet IS10 FT_IR SOP
05092025MB01
>**For urgent problems please report to Matt Burleson, AP 346, mburleson@wcu.edu, x2239!***
# Instrument Reservation
Be sure to reserve the instrument if you have not already done so.
# Software Startup
1. Logon to the computer with both the username <u>and</u> password **labuser.**
2. Locate the **Omnic** software icon.  This icon is shown below.
<img src="omnicicon.png" alt="Omnic Icon"/>
3. The homepage for Omnic will load and the popup below will show if the ATR is detected.
<img src="smartaccessorychange.png" width="400" alt="Smart Accessory Change"/>
4. You can click **OK** to bypass this for now and continue loading Omnic.
5. Continue the next steps if this is the first time a sample is analyzed, or if an unknown is analyzed.  Proceed to the next section if this the analysis of a repeat/routine sample.
6. Click **Expt Set** in the top-left corner.  This is shown in red below.
<img src="toptoolbarexpsetup.png"  alt="Expt Setup"/>
7. The experiment setup window will open.  This window is shown below.
<img src="exptsetup.png" width="400"  alt="Expt Setup"/>
8. Under the **Collect** tab, you can change the number of scans, the resolution, and the units for the collected data (under Final Format).  Adjust these as needed.
9. Click the **Bench** tab to load system parameters.  The Bench tab is shown below.
<img src="bench.png" width="400" alt="Bench"/>
10.  Within this tab, you can change the Gain and Aperture settings.  These are shown below in red and yellow, respectively.
<img src="gainandaperture.png" width="400" alt="Gain and Aperture"/>
11. With this being an unknown sample, or the first analysis of a sample, it is recommended to leave Gain set to **Autogain.**  Aperture can also be left as "High resolution."
12. Click **OK** to set these parameters.  This will close the experiment setup window.
13. Back in the main window of Omnic, click **Col Smp** in the top-right to begin an analysis.  This icon is shown below in red.
<img src="colsmp.png" alt="Collect Sample"/>
14. Upon clicking **Col Smp**, will bring up the "Collect Sample" window shown below.  It is recommended to name your spectrum as uniquely as possible. 
<img src="collectsample.png" alt="Spectrum Title"/>
15. Press **Enter** when finished naming your spectrum, and you will be prompted for a confirmation to collect a background.  Click **OK** to begin collecting the background.  When the background collection has finish, you will be prompted collect the sample.
16. Load your sample onto the ATR.  With the sample loaded, lower the anvil until good contact is made with your sample.  Click **OK** to collect the spectrum of your sample.
17. Once the collection has completed, a prompt will ask to add the spectrum to window 1.  Click **Yes** to keep the spectrum on the main window of Omnic.
18. To label the bands in your spectrum, click **Find Pks.**  This icon is shown below.
<img src="findpks.png" alt="Find Peaks"/>
19. When **Find Pks** is first selected, the window will change to show the current threshold for detection.  You can click to raise or lower this threshold until all your desired bands are detected.  Once satisfied, click **Replace** to place this labeled spectrum in Window 1.  The replace button is shown below.
<img src="replace.png" alt="Replace in Find Peaks"/>
20. With the spectrum labeled, click the **Collection and Processing Information** button by clicking the **I** icon shown in red below.
<img src="collectionandprocessinginfo.png" width="400" alt="Collection and Processing Information"/>
21. With the "Collection and Processing Information" dialog launched, scroll down until you see **Spectrometer Description.**  This is where you can find the gain the instrument determined best for your sample.  An example is shown below.  
<img src="gainsettings.png" height="375" alt="Gain Settings"/>
22. Also, note the collection errors, if any, to assess the quality of your spectrum.  This is shown below.
<img src="collectionerrors.png" height="375" alt="Collection Errors"/>
23. It is now recommended to save an experiment file with this gain for a routine sample.
24. Go back to **Expt Set,** click **Bench** and adjust the **Gain.**  Because this was shown earlier, only the gain adjustment is shown below.  Change this value to that observed in "Spectrometer Description" from Step 21 by clicking the drop-down arrow.
<img src="changinggain.png" width="400" alt="Changing Gain"/>
25. To save the experiment file, click **Save As** shown below.  Give your experiment file a unique name and then click save.
<img src="savingexpt.png" width="400" alt="Saving Expt"/>
26. Repeat as many analyses as desired.
<div style="page-break-after: always;"></div>
## Analysis of Repeat/Routine Sample
1. With the **Omnic** software open, click **Expt Set** in the top-left corner.  This is shown in red below.
<img src="toptoolbarexpsetup.png" alt="Expt Setup"/>
2. The experiment setup window will open.  This window is shown below.
<img src="exptsetup.png" width="400" alt="Expt Setup"/>
3. Click **Open** and locate your experiment file.
4. Click **Open** to load your parameters.
5. Follow Steps 13 - 19 in the previous section for data collection.
# Saving and Exporting Data
## Saving Data
1. With the data collection finished, click **File** followed by **Save As...** to launch the saving window.
2. The saving window should default to saving in **Spectra** as shown below in the first image.  If not, it can be found by following the path shown in the second image.  
<img src="savingwindow.png" height="400" alt="Saving Window"/>
3. It is first recommended to save your spectrum as **Spectra type** so that it can be retrieved later.  Give your spectrum as unique of a name as possible.
4. The spectrum can then be saved as a **CSV Text** file for later plotting.
## Exporting Data to Xenon
1. Once all data collection has been completed, follow the instructions below for exporting data to the Xenon share drive.
2. In the toolbar of the window, type the following: **\\\xenon.wcu.edu** as shown below and press **Enter.**  You will be prompted for a username and password.  This is your **FULL** Catamount email and its respective password.
<img src="xenon.png" alt="Xenon"/>
3. Locate the proper subfolder within either the **Classes** or **Research** folder and **Paste** your data there.
