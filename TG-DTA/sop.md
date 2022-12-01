# Perkin Elmer Diamond TG-DTA with Pyris Software
091422MB01

>**For urgent problems please report to Matt Burleson, AP 346, mburleson@wcu.edu, x2239!**

# Gases and Startup
1. The TG-DTA can use either air or nitrogen as a purge gas.  The gas of choice should be turned on prior to the following steps.  The nitrogen can be turned on using the main valve behind the Bruker IR system, and the air should be set to ~40 psi using the valve below the air purification unit.
1. The power switch to TG-DTA is on the front of the instrument in the lower left corner.  Upon startup, the instrument will initialize for 3 minutes.  The instrument will display "LINKwait" when ready.
1. The air cooling control unit's power switch is on the front of the module and should also be turned on.

# Login
1. If you have not already done so, reserve the instrument and log your time using it. (Please check the calendar first to make sure no one else has reserved it.)
1. Login to Windows using the username **./labuser** and the password **labuser**.
1. Double-click the "Pyris Manager" icon on the desktop.  A banner across the top of the screen will load.
1. Click on the "Diamond TG/DTA" button.  This will load the default window.

# Loading or Preparing A Method
### Loading the Default Method
1. A previously created method can be loaded from the default window by clicking "File" followed by "Open Method...".
1. Select the method you would like to load and use.

### Creating A New Method
1. Within the method editor window, you will fill out information contained in all of the tabs.
1. Under **Sample Info**, enter a sample ID, operator ID and any comment you choose to make regarding your sample.
1. Create a directory for your data under the "Save Data As" section by clicking "Browse" and creating a folder.
1. Click the **Initial State** tab, and set the initial temperature value to that of your method.
1. Click the **Program** tab, and at the lower left corner enter your final temperature in the "To" box, and your rate in the "Rate" box.
1. You are now ready to load your sample.

# Loading Samples
1. Below are six (6) suggestions to consider when preparing a sample:
  • The sample size should be between 2 and 50 mg.
  • If you have minimum amount of sample, run at least 1 mg.
  • If possible, cover the bottom of the pan with the sample material.
  • The sample pans, ceramic or platinum, can accommodate liquids, powders, films, solids or  crystals.
  • Once you have decided on the sample form, then for best results, use approximately the same sample weight during each experiment. This will ensure reproducibility.
  • Many small pieces of sample are better than one large chunk. It is better to have a large surface area exposed to the sample purge.

1. Acquire the sample pans.  Platinum sample pans are recommended as a general use pan.
1. Using the control on the front of the instrument, open the furnace using the "OPEN" button until it stops itself.
1. Place an empty pan in **both** the reference and sample holders.
1. With the pans in place, click "Zero Weight" in the control panel on the right-side of the software window.
1. Weigh your sample in the sample pan following the suggestions in Step 1 above.
1. With your sample in the pan, close the furnace using the "Close" button located on the front of the instrument.
1. Using the control panel in the right-side of the software, change the temperature to that of your starting temperature, and click "Go To Temperature." Allow your sample and the furnace to equilibrate at the temperature for at least five (5) minutes.
1. After your sample has equilibrated, click "Sample Weight" to input your sample's mass as the 100% weight percent starting point.

# Analyze Samples

1. Within the control panel in the right-side of the software, click "Start/Stop" to begin the analysis.

# Analyze and Export Data
The two most common calculations determined from the thermal curve are:

  **Onset Temperature** - denotes the temperature at which the weight loss of sample begins.  The onset temperature is a reproducible temperature calculation and it is specified to be used by ASTM®.

  **Inflection Point** - indicates the point of greatest rate of change on the weight loss curve.

### Onset Only
1. There are two modes to analyze data in, online (TG-DTA is on) and offline (TG-DTA is off).  Online can be done if the instrument was left on from a previous run.
1. Offline data analysis can be accomplished by clicking "Start Pyris" followed by "Data Analysis."
1. If you only want to find the onset of a change in the curve, go to “Calc” in the top menu bar and click “Onset”.  A dialog box will pop up and a small “x” will appear on the each end of your line.
1. To find the onset, it is easiest to drag each “x” closer to the side you want to measure as seen in the next image. The following spots will measure the upper portion of the curve.
Press “Calculate” in the dialog box and you will be given the option to move the tangents of each “x”. Make sure that the light blue line is as close to tangent as possible and going toward the onset point.
     ![Adjustment of X in onset calculation.](Xcloser.png)

1. Press “Calculate” in the dialog box and your result will look like this:
![Result after adjusting X.](Result.png)

### Onset, Inflection Point and Change in Weight Percent

1. To calculate the onset temperature, change in weight percent and the inflection point, click on "Calc" in the top menu bar and click "Step."
1. In the "Step Transition" dialog box, make sure "Onset" is checked and then hit "Calculate."
1. Two tangent lines will appear and you can adjust these to make them tangent with the line as shown in the next image. Click on “Calculate”.
![Adjustment of X in onset calculation.](tangentlines.png)
1. To save the calculated results, click on “File” from the top menu bar and then “Save Data”.

### Exporting Data

1. Data can be exported once processed and saved by clicking "File" followed by "Export Data" and selecting "ASCII Format..."
1. A dialog box will appear and ensure "Include Data Points" and "Include Calibration Information" are checked before clicking "OK."

<div style="page-break-after: always;"></div>

# Shutdown
1. When you're finished with the instrument, change the temperature in the control panel to 30 C, and click go to temperature.  The instrument can be left to cool overnight as long as the cooling/purging gas is flowing.
1. Allow the instrument to cool to room temperature.
1. Close the Pyris software which will also shutdown the instrument.
