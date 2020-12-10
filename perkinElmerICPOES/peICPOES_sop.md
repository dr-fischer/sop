# Perkin Elmer Optima 4100 DV ICP-OES

## Warm Up (~90 minutes)
1. If you have not already done so, open the [web broswer, check the instrument calendar, and reserve/log your time](https://www.wcu.edu/learn/departments-schools-colleges/cas/science-and-math/chemphys/instrumentation/instrumentation-schedules/icp-oes-schedule/) on the instrument (use the `neon` computer).
     ***Do not open the ICP-OES software without completing the steps below first!***
1. Turn on the exhaust snorkels with the "light switch" on the cabinet under the instrument.
1. Turn on the chiller (Polyscience brand, under table).
1. Open the valves on *all five* argon tanks; if any tank has <500 psi please contact the Instrumentation Specialist to have it replaced prior to proceeding.
1. Make sure the pressure gauge on the wall reads ~100 psi.
1. Check the drain tubing and waste bottle to ensure everything is connected, there are no kinks, and the waste bottle is below the maximum fill level.
1. Check the level of the DI water reservoir. If there isn't enough water for your run, remove the filter and transfer line and place it immediately in the spare bottle.  You may alternatively use a solution of 1% nitric acid in water as your rinse.
     ***Make sure the filter does not become contaminated -- never touch it or the transfer line and never set it down on anything!***
1. Tension the tubing on both peristaltic pump and secure the clamps.
1. Click the **ICP-OES Software and Usage Log** icon on the desktop to start the ICP-OES software.
1. Make sure the software has automatically connected to the spectrometer, plasma generator, and autosampler; let the system **warm up for ~80 minutes**.
1. While the instrument is warming up, click on the **Manual Control** (erlenmeyer flask icon); find the **Go to A/S Loc** button, enter the position of an empty location into the box next to it (e.g. 1), and click the button.  *If the menu item is not available yet (greyed out) you may skip this step.*
1. You may now proceed to *Create a Method* and *Enter Sample Information*, below, using the **Offline ICP-OES** software while you wait.  Or, you may leave until the ICP has finished warming up.

## Prepare a Run

### Create a Method

1. Click **File > New > Method**.
1. Enter the elements for analysis.  
     1. Navigate to the **Spectrometer Tab / *Define Elements***.
     1. Click the **Periodic Table** button.
     1. Select the analytes you wish to probe on the table.
     1. Click on **Wavelength Table**.
     1. Hold *CTRL* on the keyboard and select up to 3 wavelengths for each element; choose the wavelengths with the highest intensity.
     1. Click **Enter Selected Wavelengths**.
1. Navigate to the ***Settings Tab*** and set the *Delay Time* to 60 seconds and the *Replicates* to 3.
1. Navigate to the **Process Tab** and set *Points per Peak* to 5.
1. Navigate to the **Calibration Tab / *Define Standards*** and enter your standard and calibration blank information.  *See back for suggested run list.*
1. Navigate to ***Calib Units and Concentrations*** and enter the *actual* concentration of each standard.
1. Close the *Method Editor* window.

### Prepare a Sample Information File

1. Click **File > New > Sample Info File**.
1. Enter autosampler (A/S) location and ID for each sample; you should include any rinse and method/reagent blanks here. *See back for suggested run list.*
1. Click **File > Save As > Sample Info File** and close the *Sample Info Editor* window.

## Start the Plasma (~5 minutes)

1. Move the autosampler probe to an empty location (**Manual > Go to A/S Loc.**)
1. Open the *Plasma Control* window by clicking the **Plasma** icon.
1. Click the **On** switch in the *Plasma Control* window to turn the plasma on.
1. Once the plasma is lit, move the autosampler probe to the wash location and let the plasma stabilize for at least 5 minutes.  *Plasma ignition takes about a minute -- you can check the status in the* Plasma *indicator in the toolbar.*
1. You may move on to *Prepare an Analysis*, below, while the plasma stabilizes.

## Run Samples

### Prepare an Analysis

1. Click on the **Auto** button in the toolbar and make sure the **Set Up** tab is selected.
1. Ensure your sample information file is listed in the appropriate box; **Open** it if not.
1. Click **Open** next to the *Results Dataset Name* box and enter a new name for your results (or choose a dataset you wish to append to). *Do not change the library location!*
1. Make sure the *Save Data* box is checked.  This ensures you data will be saved automatically.
1. Close the *Automated Control* window.

### Check the instrument for cleanliness (run a blank)

1. Click the **Manual** icon in the toolbar.
1. Enter a sample ID for your first rinse blank.
1. Enter your rinse blank location next to the **Go to A/S Loc.** button, and then click the button.
1. Click the **Analyze Sample** button.
<!-- 1. Open the *Transient Peaks* window by clicking the **Peaks** button in the toolbar.  You should see a flat line for each blank replicate; any peak indicates contamination. -->
1. Click **Go to Wash Loc.** when the instrument finished running the blank.
1. If the blank is clean, close the *Manual Control* window and move on to *Analyze your standards*, below; if it is dirty, flush the system with ultrapure water and/or 5% nitric acid for 5-10 minutes and try again.  Enter a new sample ID for each rinse blank.  Keep in mind the contamination could also be from your blank itself!

### Analyze your standards

1. Click on the **Auto** icon in the toolbar and select the **Analyze** Tab.
1. Make the **Use Method in Memory** radio button option is selected.
1. Navigate to the **Analyze Tab** and click **Rebuild List**.
1. Click **Analyze Standards**.
1. You should see peaks appear for each replicate in the *Transient Peaks* window.
1. You can view your calibration curve in realtime by clicking the **Calib** button in the toolbar.
1. If your standard curve passes quality check, move on to *Analyze your samples*, below.

### Analyze your samples

1. In the *Automatic Control* window, click the **Analyze Samples** button.
1. It is now safe to leave the instrument until your run is complete.

## Export

1. Click the **Data Manager** icon on the desktop.
1. Choose your results dataset in the main window.
1. Click the **Export** icon in the toolbar.
1. Choose **Use Existing Design** and select `_ICPdefault`.
1. Click **Finish**, then **Export Data**, then **Finish**.
1. Your data will appear as a text file in the *Reports* folder (shortcut on Desktop).

## Shutdown (~20 minutes)

1. Open the *Manual Control* window.
    1. Move to a 5% nitric acid blank and rinse the system for 5 minutes.
    1. Move to the wash location and rinse with ultrapure water for 5 minutes.
    1. Move to an empty location and pull air through the system for 5 minutes.
1. Click **Plasma**.
    1. Turn off the peristaltic pump by operating the **Pump** button.
    1. Turn off the plasma by operating the **Plasma Switch**.
1. Close the software and logoff of windows.
1. Release the clamps on the peristaltic pump and then remove tension from the tubing.
1. Turn off the chiller.
1. Turn off the argon tanks (all 5).
1. Turn off the snorkels with the "**light switch**" on the cabinet under the instrument.

## Suggested Run List

1. Rinse Blank
2. Subtraction Blank
3. Low Standard
4. Medium-low Standard
5. Medium Standard
6. Medium-High Standard
7. High Standard
8. Rinse Blank
9. QC
10. Samples 1-10
11. QC
12. Samples 11-20
13. QC
...
14. Samples *n-m*
15. QC
16. Rinse Blank [*You must run a final blank to ensure the instrument is left clean!*]
