# Agilent 1100 (DAD) LC Operating Procedure
090723MB01

>**For urgent problems please report to Matt Burleson, AP 346, mburleson@wcu.edu, x2239!***

# Scope

This SOP details the operation of the Agilent 1100 LC with Agilent's OpenLab software and without mass spec detection.  The LC can be operated with the MS which is detailed as a separate document.

# Configuration and Login
1. If you have not already done so, reserve the instrument and log your time using it.  Please check the calendar first to make sure no one else has reserved it.
1. Login to Windows using the username **labuser** and the password **labuser**.
1. The DAD has a line connected to a tee that splits the flow between the waste and the mass spectrometer.  Remove the line leading to the mass spec by removing the fingertight fitting and replacing it with a column plug.
1. The instrument must be reconfigured for Agilent's OpenLab software each time it is to be used without the mass spectrometer.  To start this reconfiguration, click the Windows icon in the bottom-left of the desktop, or press the Windows key.
1. Locate the Thermo Scientific Foundation 3.1 folder and click it.
1. Locate Instrument Configuration and click it.
1. After a brief loading period, the Thermo Foundation Instrument Configuration window (shown below) will show.
      ![Thermo Foundation Instrument Configuration Window for Mass Spec Use. ](Instrumentconfigforlcms.png)
<div style="page-break-after: always;"></div>
8. Under "Configured Devices" click on an Agilent module followed by **<<Remove** to unconfigure it from the Thermo software.  Repeat this for each Agilent module until the Thermo Foundation Instrument Configuration window resembles the one shown below.
      ![Thermo Foundation Instrument Configuration Window Without Mass Spec Use. ](Instrumentconfigforlc.png)
1. Close the Thermo Foundation Instrument Configuration window by clicking Done.
1. Locate the LC1100 icon on the desktop and double-click it to load the Agilent OpenLab software.
1. As the software initializes, a Method Load Option will appear.  Ensure that "All modules are online" is across the bottom of this window as shown below in yellow.
      ![Method Load Option. ](allmodulesonline.png)
1. Click "Download to instrument" to complete the initialization.
<div style="page-break-after: always;"></div>
# Preparing the Instrument
1. Ensure there is enough mobile phase for your analysis in the mobile phase bottles on top of the instrument.
      > *NEVER let the mobile phase level get below the level of the filter in the bottle! NEVER let air get into the LC plumbing!*

1. The LC lines must be purged with the necessary mobile phase prior to use.  Open the purge valve of the LC pump by turning the purge valve counterclockwise.  This ensures no air will enter the column.
1. Right-click in the "Quat. Pump" window and select Method.  The pump's method window will open.
1. Change the "Flow" to 5.00 mL/min, and the composition to be an even split of the lines you are using.  For example, if using lines A & B, they would be set to 50:50.  If using all four lines, they would be 25% each.
1. Click Ok at the bottom-right to close the pump's method window.
1. Click the green **On** button In the main window of the OpenLab software to turn on the pump, column heater, and lamp.
1. After the pump has been on for roughly 3 minutes *and you do not see air bubbles exiting the proportioning valve into the pump head*, you may proceed to the next step.
1. Load your method by clicking on the **Method and Run Control** pane on the left hand side of the screen, selecting the **Methods** tab, and double-clicking the method you wish to use.
1. (*Advanced*) If you need to create a new method, click **Method > Save Method As ...** and save a template as a new name.
1. (*Advanced*) To edit the new method, click **Method > Edit Entire Method**, select the portions you wish to edit, click **OK**, and edit the method as necessary.  Alternatively, right click each parameter you wish to edit on the main HPLC screen and select method to edit just that portion.
  1. If a spectrum scan is desired by the DAD, follow these steps.
  1. In the Setup Method window of the DAD (shown below), use the dropdown arrow by Store to select either Apex or All.
  1. With Apex (spectrum is taken at the apex of the band) selected to be stored, enter the scan range, step and threshold that is desired.  A step of 2.0 nm and a threshold of 10.0 mAU are the default values.
  1. Click Ok and proceed.
1. Close the purge valve by turning the black knob clockwise until it's fully tightened to begin equilibrating the column to the initial conditions.
1. Allow the system to equilibrate until you observe a stable absorbance baseline in the Online Plot. (You may proceed to creating a sequence while waiting, but ensure a stable baseline before running the sequence).  If necessary, the baseline can be reset to zero by right-clicking the lamp and selecting "Balance."

# Prepare A Sequence
1. Click on **Sequence > Sequence Parameters.**
1. Create a subdirectory folder where your data will be saved.  Click "Yes" when asked if you want to create the specified directory.
1. Ensure the box next to **Post-run Command/Macro** is checked and `Turn Instrument STANDBY` is shown as the command.  This will turn off the HPLC when your sequence finishes.
1. Click OK to close the Sequence Parameters window.
## Editing The Sequence Table
1. Open the Sequence Table by clicking **Sequence > Sequence Table...**.  
### Sample Location
1. Click within the cell under the "Sample Location" header and then click the dropdown arrow.  An image will appear of the sample tray that was automatically detected by the autosampler during the initialization.  Click the tray in the left-hand side of the screen to load a top-down view in the right-hand side.  Click on the circle that corresponds to your sample's location in the tray.  The window will close and the table will have your location entered.  This will be repeated for each sample.
### Sample Name
1. Under the Sample Name column, name your sample for what it is.
### Method Name
1. Click the dropdown arrow to select your method.  Use the browse selection at the bottom if you do not see your method.
### Sample Information
1. Sample Information will allow you to enter comments on your sample that will appear on the resulting chromatogram.
### Data File
1. The Data File is the most important part of the sequence table as it is what the data is saved as on the computer's hard drive.  Make sure this is as unique as possible to each sample.


# Preparing A Sequence Continued
1. The other fields can stay blank or remain the default values.
1. It is recommended that **at least TWO** blanks are the start of the sequence.  The first will ensure the column is clean and equilibrated it to your method.
1. A sequence should always end with **at least ONE** blank injection to rinse the column.
1. An example of a satisfactory sequence is shown below.
      ![Example of Sequence. ](sequence.png)
1. Click OK at the bottom-right to close the Sequence Table.
1. Click on **Sequence > Save Sequence Template As** and save your sequence with a unique file name.
1. Click OK to return to the main window of the OpenLab software.

# Analyze Samples
1. Press the **Play Sequence** button in the main window to start your sequence when the baseline is stable.

# Shutdown
1. When you are finished with the instrument, make sure there is no flow from the LC and that the detector lamp(s) is off.  Both of these can be adjusted from the main window of the OpenLab software.
1. You may close all programs.
