# Agilent 1220 Infinity LC with UV Detector

> *If you encounter problems while running the instrument, please use submit an [**Instrument Incident Report**](https://docs.google.com/forms/d/e/1FAIpQLSc96MiK73kKP06KEZpR0-O7zETCLvWgQtLp_bKEynosUKqpNg/viewform) with a description of your problem.  **For urgent problems please report to Al Fischer, NS 209, dfischer@wcu.edu, x2695!***

# Login

1. Login to Windows using the username **./labuser** and the password **labuser**.
1. Open the HPLC software by clicking the **HPLC Software & Usage Log** shortcut on the Desktop.
1. If you have not already done so, use the form in the browser window that opens to reserve the instrument and log your time using it. (Please check the calendar first to make sure no one else has reserved it.)

# Load a Method

1. Load your method by clicking on the **Method and Run Control** pane on the left hand side of the screen, selecting the **Methods** tab, and double-clicking the method you wish to use.
1. (*Advanced*) If you need to create a new method, click **Method > Save Method As ...** and save a template as a new name.
1. (*Advanced*) To edit the new method, click **Method > Edit Entire Method**, select the portions you wish to edit, click **OK**, and edit the method as necessary.  Alternatively, right click each parameter you wish to edit on the main HPLC screen and select method to edit just that portion.

# Warm Up the Instrument

1. Ensure there is enough solvent for you run in the solvent bottles on top of the instrument.     
      > *NEVER let the solvent level get below the level of the filter in the bottle! NEVER let air get into the HPLC plumbing!*

1. Right click on the solvent bottle pictures in the main panel of the HPLC software and enter the approximate solvent levels you observed in the bottles.
1. Open the top/front cover the the HPLC and open the priming valve by turning the black knurled knob on the front of the pump a couple of turns.  This ensures no air will enter the column.
1. Click the green **On** button In the main window of the HPLC software to turn on the pump, column heater, and lamp.
1. After the pumps have been on for roughly 2 minutes *and you do not see air bubbles exiting the valve into the waste line*, you may close the priming valve by turning the black knob clockwise until it's fully tightened.
1. Allow the system to run until you observe a stable absorbance baseline in the real-time read out. (You may proceed to creating a sequence while waiting, but ensure a stable baseline before running the sequence).

# Prepare a Sequence

1. Click on the **Sequence templates** tab under *Method and Run Control* and double click the `_DEFAULT.S` to load the default template.
1. Click **Sequence > Save Sequence As** and enter a filename to save your own copy of the template.
1. Click on **Sequence > Sequence Parameters** and ensure the box next to **Post-run Command/Macro** is checked and `STANDBY` is shown as the command.  This will turn off the HPLC when your run finishes.
1. Open the sequence table by clicking **Sequence > Sequence Table...**.  Edit the resulting sequence table as necessary and press **OK** when finished.  Make sure you enter the autosampler location (Vial) and sample name and select the correct method for each sample.  The other fields can stay blank or remain the default values.

# Run Samples

1. Press the **Play Sequence** button in the main window to start your sequence if the baseline is stable.

# Analyze and Export

1. Select the **Data Analysis** pane and choose the sequence containing the data you wish to view/analyze/export.
1. Select the sample you wish to view/analyze/export from the sequence by double clicking it.
1. Click the **autointegrate** icon (green integral symbol) to find the retention time and peak area for the selected chromatogram.
1.  Export your chromatogram to a CSV (recommended).
	1. Right click on the chromatogram you wish to export.
	1. Select **Export > CSV**.
	1. Select **Signal**.
	1. Choose your file path.
	1. Select the option containing **Wavelength=XXX nm**

# Shutdown

1. Press the red **Off** button in the main HPLC control window.  (The vacuum degasser will remain on -- that's OK).
1. Close the software and logoff from the computer.
1. Remove your samples from the autosampler tray and clean up your work area.
