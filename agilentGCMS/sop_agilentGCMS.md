# Agilent 7890A GC with 5975C MSD

MB 04062022

> *If you encounter problems while running the instrument, please use submit an [**Instrument Incident Report**](https://docs.google.com/forms/d/e/1FAIpQLSc96MiK73kKP06KEZpR0-O7zETCLvWgQtLp_bKEynosUKqpNg/viewform) with a description of your problem.  **For urgent problems please report to Matt Burleson, AP 346, mburleson@wcu.edu, x2239!***
# Start the Carrier Gas and Instrument
1. On the hydrogen generator located below the instrument, press "Start."  The generator will begin to initialize.
1. Once the generator has finished initializing, press "Open."  Allow the generator enough time to reach its pressure setpoint.
1. The instrument can now be turned on.
# Login
1. Login to Windows using the username **administrator** and the password **3000hanover**.
1. Open the ChemStation Software by selecting **GCMS Software & Usage Log** shortcut on the desktop.
1. When the web browser opens, use the online form to reserve the instrument and log your time (ensure no else has the instrument reserved on the calendar).
1. Login to ChemStation using the username **operator** and password **operator**.

# Load a Method

> *The "Method" file includes the parameters that tell the GC-MS how to operate.*

1. Go to **Method > Load Method**, choose your method, and click **OK**.
	1. All methods are stored on `C:/msdchem/methods/...`.
	1. If you are in a class, use the method your were instructed to use in class. For CHEM 472/572 use `C:/msdchem/methods/2018 CHEM472-572/chem472-18_method.m`.

# Prepare a Sequence

> *The "Sequence" file includes the vial locations, file names, and descriptions of the samples.*

## For a single sample
1. Click the **Green Arrow** ar the top of the screen.
1. Select the path to the data *folder* you wish to use. (All data are stored on the Data (`D:/`) drive.)
1. Enter the operator name.
1. Enter a description of your sample.
1. Enter a unique filename for your sample.
1. Enter the autosampler position for your sample under **Vial**.
1. Ensure there is enough solvent is the wash vials you are using (usually Vial A) and fill them if not.
1. Click **OK and Run Method**.

## For multiple samples

1. Select **Sequence > Edit Sequence**.
1. Select the path to your data *folder* at the top left of the sequence window. (All data are stored on the Data (`D:/`) drive.)
1. Enter the the path to the *folder* that contains your method in the top middle of the window. (All methods are stored on the `C:/` drive, see Section 2.)
1. Fill out the sequence table; an example is given in Figure 1.
1. Click **OK** to exit the sequence table.
1. Click **Sequence > Save Sequence** to save your changes.
1. Ensure there is enough solvent is the wash vials you are using (usually Vial A) and fill them if not.
1. Select **Sequence > Run Sequence**, and then click **Run Sequence** in the popup.

![Example Sequence Table](./agilentGCMS_sequenceTable.png)

# Analyze

1. Open the data analysis software by clicking the "GCMS Data" shortcut on the desktop and login using the username **operator** and password **operator**.
1. Select the file you wish to examine in the browser on the left of the screen.


> *For real-time analysis, click the **Snapshot (camera icon)** in the top shortcut bar to import the current data*

- Tips:       
    - *To zoom*: Left click and drag; double click to zoom to extents.
    - *To view a mass spectrum*: Right click, choose **Select** and the mass spectrum is displayed below.
    - *To find the retention times*: Right click on TIC and choose **Integrate**.

# Save/Export

1. You may print your spectra to the printer to paste into your lab notebook.
1. To export the spectra to Excel, MATLAB, R, Python, etc., right click on the item you wish to export (e.g. the chromatogram or the mass spectrum for a specific peak) and choose **Tabulate**.  In the window that opens up, select **Copy**.  Paste the copied text into a plain text file (for example, open Notepade and press **CTRL V**), and then save the file as `your_filename.tsv`.  The format is tab-delimited.

# Shutdown

1. Return the instrument to its resting state by selecting **Method > Load Method** and choose  `_DEFAULT.M` (in the GC software).
1. Remove your sample vials from the autosampler and solvent from the wash vials and dispose of as hazardous waste.  Ensure your work area is clean.
1. Close the software and log out of the computer.

# Keep the Instrument Safe
1. All samples analyzed via GC-MS must boil below 250 ℃ unless your method is specifically designed to accommodate high-boiling point samples.
1. The GC-MS is only for liquid (or gas) samples (unless using the headspace sampler).
1. If you have a lot of particulates in your sample (e.g. a catalyst or drying agent), you must filter it.
1. Never inject aqueous solutions (they may damage the column).
1. Never inject strong acids or bases or acetic acid (they may damage the column).
1. Aim to have you maximum abundance in the chromatogram be ~2 million.
1. Don't override the solvent delay.
