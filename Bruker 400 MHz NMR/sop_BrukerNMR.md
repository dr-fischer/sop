## Bruker 400 MHz NMR Spectrometer Operating Instructions
MB | v20210922

### Single sample analysis
## Software Startup and Acquisition
1. The username for the computer is nmrsu.  The password is "topspin."
1. Sign in to the calendar if you have not already done so.
1. Double-click the TopSpin 4.0.9. icon.  A window similar to command prompt will open before TopSpin opens.
1. Obtain a spinner and place your NMR sample tube inside.  Use the depth gauge (with no force) to set your tube depth to the appropriate level.
1. Place your prepared sample in an autosampler location.  Take note of the number within the autosampler.  Location 24 is reserved for the autocalibration sample and should never be removed.
1. Under the "Acquire" tab select "Create Dataset."  A new window will open.
1. Within this window, give your experiment a name and number in "NAME" and "EXPNO", respectively.
1. Select your nuclei under from "Read parameterset" and then select your solvent beside "Set solvent".  Click "OK".
1. Insert your sample by clicking "Sample" followed by "Insert sample with sample changer."  A new window will appear for you to enter the location of your sample.  Once you click "OK", the sampler will insert your sample.
1. With your sample inserted, click "Lock."  A new window will appear where you will select your solvent and click "OK."  The instrument will then initiate the locking process.
1. With the instrument locked, select "Tune" followed by "Tune/match ATM probe automatically."
1. Once the tuning is complete, select "Spin" followed by "Turn sample rotation on."
1. Once the sample is spinning, select "Shim" followed by "Autoshim sample using TopShim."
1. Once the sample has been shimmed, select "Prosol" followed by "Update 'prosol' parameters."
1. With the parameters updated, select "Gain" followed by "Receiver gain adjustment."
1. After the gain has been adjusted, the sample can be analyzed by clicking "Run" followed by "Start Aquisition."


### Automation use for multiple samples
## Software Startup and Acquisition Setup
1. The username for the computer is nmrsu.  The password is "topspin."
1. Sign in to the calendar if you have not already done so.
1. Double-click the TopSpin 4.0.9. icon.  A window similar to command prompt will open before TopSpin opens.  TopSpin will primarily be used once the acquisition is complete.
1. Click in the command line within TopSpin and type "iconnmr" followed by pressing enter.
1. Click the "Automation" icon.
1. Select the nmrsu username and click "OK."  The password for the username is "topspin."
1. The subsequent window is where acquisitions are created and submitted for analysis.

## Acquire Spectra Using Automation
1. Obtain a spinner and place your NMR sample tube inside.  Use the depth gauge (with no force) to set your tube depth to the appropriate level.
1. Place your prepared sample in an autosampler location.  Take note of the number within the autosampler.  Location 24 is reserved for the autocalibration sample and should never be removed.
1. Within the Experiment Table window, click the number under the "Holder" column followed by "Add."
1. Take note of the location listed under "Disk" as this is where your spectrum will be saved.  Leave the value under the "NO." column as is.
1. Select your solvent from the drop-down menu under the "Solvent" column.
1. Select your experiment from the drop-down menu under the "Experiment" column.
1. Parameters of the selected experiment, such as the number of scans, can be edited by clicking the equal sign under the "Par" column.
1. Your spectrum can be given a title by  clicking in the "Title/Orig"* window.
1. You can add multiple experiments to the same holder as necessary.  For example, a carbon experiment could be added for the same sample by clicking "Add" again.  You will then observe a new row has been added and the value under the "No." column has increased by one.  Repeat the above instructions for setting up the subsequent experiment.
1. Click "Submit" to add your sample to the queue.  Note that any sample to be analyzed must be submitted.
1. Click the "Start" icon located near the top toolbar to load the submission subwindow, and click "Start" again to begin the acquisition.
<div style="page-break-after: always;"></div>
### Processing Spectra
1. Find your spectrum within TopSpin.
1. To integrate spectra, click "Analyse" followed by "Integrate."  Select "Manual-Integrate" to bring up the integration toolbar.
1. It may be necessary to delete an automatically integrated peak.  This can be done by clicking the red integration value so that a yellow-green color is under the integration value and then clicking "Delete selected regions."  Holding the left mouse button, click and drag from left to right of the peak you want to integrate.  Let go of the left mouse button when you reach the end of the peak.
1. To change the integral value, right-click on the current integral value and select "Calibrate Current Integral."  Within the popup window, change the value of your integral to the desired value.
1. Peak locations may be identified by clicking "Pick Peaks."  After the peaks have been picked, press "Return, save changes."
1. Adjusting the x-axis of your plot can be accomplished by clicking "PROCPARS" followed by "Peak" in the left-hand toolbar.  Change the values for the labels of "F1P" and "F2P" to be your upper and lower limit for the x-axis, respectively.

### Printing Spectra
1. To print your spectra, select the "Plot" tab.  Under layout, use "Proton Default" if it is not already selected.
1. In the top-right corner of TopSpin you will have the option to send the file to a printer or print as a PDF.

### Retrieving Samples
1. With your analysis complete, you can retrieve your sample by returning to the TopSpin window.
1. From here, navigate to the "Acquire" tab.
1. Click "Sample" followed by "Insert sample with sample changer."
1. A new window will appear asking for the holder position.  Use the value of 24 for the autocalibrate sample.
1. With the autocalibrate sample inserted, the software can be closed.
