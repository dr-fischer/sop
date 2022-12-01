## Bruker 400 MHz NMR Spectrometer Variable Temperature Operating Instructions
MB | v20221129
**Note: All users must be trained by the Instrumentation Specialist before changing the probe temperature!**

**Before you begin:**
1. Ensure that your sample tube has no chips or cracks.
2.  Know the boiling point of your solvent!  **Stay at least 25 degrees away from the solvent's boiling point!**


### Software Startup and Initial Acquisition
1. The username for the computer is nmrsu.  The password is "topspin."
1. Sign in to the calendar if you have not already done so.
1. Double-click the TopSpin 4.0.9. icon.  A window similar to command prompt will open before TopSpin opens.
1. Obtain a spinner and place your NMR sample tube inside.  **Note: The blue spinners can only be used to 80 C.**  
1. Use the depth gauge (with no force) to set your tube depth to the appropriate level.
1. Place your prepared sample in an autosampler location.  Take note of the number within the autosampler.  Location 24 is reserved for the autocalibration sample and should never be removed.
1. Under the "Acquire" tab select "Create Dataset."  A new window will open.
1. Within this window, find or create a folder for your data, give your experiment a name and number in "NAME" and "EXPNO", respectively.
1. Select your nuclei under from "Read parameterset" and then select your solvent beside "Set solvent".  Click "OK".
1. Insert your sample by clicking "Sample" followed by "Insert sample with sample changer."  A new window will appear for you to enter the location of your sample.  Once you click "OK", the sampler will insert your sample.
1. With your sample inserted, click "Lock."  A new window will appear where you will select your solvent and click "OK."  The instrument will then initiate the locking process.
1. With the instrument locked, select "Tune" followed by "Tune/match ATM probe automatically."
1. Once the tuning is complete, select "Spin" followed by "Turn sample rotation on."
1. Once the sample is spinning, select "Shim" followed by "Autoshim sample using TopShim."
1. Once the sample has been shimmed, select "Prosol" followed by "Update 'prosol' parameters."
1. With the parameters updated, select "Gain" followed by "Receiver gain adjustment."
1. After the gain has been adjusted, the sample can be analyzed by clicking "Run" followed by "Start Aquisition."  This initial spectrum will serve as a reference point.
<div style="page-break-after: always;"></div>

### Raising The Temperature
1. Lock, tune and shim your sample again following the steps above.
1. In the command line, type "edte" to open the Temperature Control Suite (shown below).  Take note of the locations for Heater Power, Sample Temperature and Shim Coil Temperature.  **Note: The Shim Coil Temperature should remain < 100 C!**

![Temperature Control Suite](edte.png)</div>

1. To begin, click "Set" under the Target Power of the BCU Chiller.
1. In the dialog box that opens, titled "Set Power Mode," select "Off" followed by "Ok."
1. You may observe color changes in the temperature readbacks.  <span style="color:blue">Blue</span> means the probe is below the set target temperature, <span style="color:green">green</span> means the probe is at the set target temperature, and<span style="color:red"> red</span>  means the probe is above the target temperature.
1. Click the "Monitoring" tab within the Temperature Control Suite.  Check the Current Temperature, Target Temperature, Target Gas Flow, and Current Gas Flow boxes.  This will allow a graphical representation of how steady the temperature and gas flow are as you heat your sample.
1. Click back on the "Temperature" tab in the Temperature Control Suite.  To set a new Target Temperature, click the "set" button, enter your new temperature and click "OK."  **NOTE: YOU SHOULD ONLY HEAT IN 10 DEGREE INCREMENTS!**
Ramping the temperature too fast can harm the probe.  The same is true when ramping the probe back to room temperature.


1. As your temperature ramps you may need to adjust the Target Gas Flow.  The default value is 400 L/hour, but you may need to try other values to reach/maintain your target temperature as shown below.

  ![Temperature Control Suite](Vtgasflow.png)

1. In the "Monitoring" tab, watch for any signs of trouble.  If you see the Current Temperature or Current Power changing erratically, let the Instrumentation Specialist know IMMEDIATELY.

**Note: Never leave the NMR unattended while conducting a variable temperature experiment.**

1. Once the Target Temperature has been reached and the Sample Temperature in the bottom status bar has been green for about three minutes, the temperature is stabilized.
1. Lock, tune and shim your sample at the new temperature as all of these will change with a change in temperature.
1. Acquire your data after locking, tuning, and shimming.

### Ramping Down The Temperature
1. The ramping of the temperature back to room temperature is reverse of ramping up the temperature.
1. Ramp down your temperature in 10 degree increments allowing the probe to equilibrate for three minutes at each temperature.
1. Once the temperature is back at room temperature, select the "Temperature" tab within the Temperature Control Suite.
1. Check that the Target Gas Flow is back to 400 L/hour.
1. Click the "Set" button under Target Power for the chiller.
1. Change the power to medium for the chiller.  Allow the chiller to stabilize for at least two minutes.
1. After two minutes, change the chiller's power to maximum.
1. You have now completed your variable-temperature NMR experiment.

### Processing Spectra
1. Find your spectrum within TopSpin.
1. To integrate spectra, click "Analyse" followed by "Integrate."  Select "Manual-Integrate" to bring up the integration toolbar.
1. It may be necessary to delete an automatically integrated peak.  This can be done by clicking the red integration value so that a yellow-green color is under the integration value and then clicking "Delete selected regions."  Holding the left mouse button, click and drag from left to right of the peak you want to integrate.  Let go of the left mouse button when you reach the end of the peak.
1. To change the integral value, right-click on the current integral value and select "Calibrate Current Integral."  Within the popup window, change the value of your integral to the desired value.
1. Peak locations may be identified by clicking "Pick Peaks."  After the peaks have been picked, press "Return, save changes."
1. Adjusting the x-axis of your plot can be accomplished by clicking "PROCPARS" followed by "Peak" in the left-hand toolbar.  Change the values for the labels of "F1P" and "F2P" to be your upper and lower limit for the x-axis, respectively.

<div style="page-break-after: always;"></div>

### Advanced Processing for Spectra


## Peak picking
1. Peak picking can be performed by clicking "Analyse" followed by the "Pick Peaks" dropdown menu.  This menu allows peaks to be selected automatically or manually.
1. In the event that Auto-pick is not satisfactory, select "Manual Peak Picking" to open the peak picking toolbar.1. Left-click and hold to drag the mouse from left to right over the range of peaks you need to pick.
1. Under the peak picking toolbar, select "Define peak manually."  Left-click in the center of the peak you need to pick and the peak's ppm will appear in green.
1. Zoom out and repeat this procedure as necessary for all of the necessary peaks.

## Adjusting Peak ppm
1. In the event that a peak's ppm needs to be edited such as setting TMS to zero, for example, the Axis Calibration will be used.
1. Under the "Process" tab, select the "Calib. Axis" dropdown menu.
1. Click "Manual Axis Calibration." A red cursor should now be displayed on the screen.  Left-click this cursor in the center of the peaking needing to be adjusted.  A new window will open asking for the cursor frequency in ppm.  Set this value accordingly and press "OK."  The spectrum will then be adjusted.


### Printing Spectra
1. To print your spectra, select the "Plot" tab.  Under layout, use "Proton Default" if it is not already selected.
1. In the top-right corner of TopSpin you will have the option to send the file to a printer or print as a PDF.

### Retrieving Samples
1. With your analysis complete, you can retrieve your sample by returning to the TopSpin window.
1. From here, navigate to the "Acquire" tab.
1. Click "Sample" followed by "Insert sample with sample changer."
1. A new window will appear asking for the holder position.  Use the value of 24 for the autocalibrate sample.

 > Please do not close IconNMR so that the instrument performs the autocalibration at night.

### Retrieving Spectra
 1. You can retrieve a previously analyzed spectrum within TopSpin by pressing **ctrl+f** to open the "Find data" window.
 1. Enter the name of your data/spectrum you'd like to retrieve and click "OK" to start the search.
 1. After locating the spectrum within the search results window, click "Display" to display the spectrum in TopSpin.
 1. You may close the search results window.
