## TA Instruments Standard Volume Isothermal Titration Calorimeter (ITC) Testing SOP
MB | v20211005
Sign in to the calendar if you have not already done so.
Prior to using the instrument, the instrument should be calibrated as detailed in the following section.
>Note: The testing procedure can take up to three hours.

### Testing the instrument prior to analysis
## Software and test setup procedure
1. Turn on the instrument using the power switch located on the back if it is off.
1. The software for analysis is "ITCRUN".  The buret will need to be homed if the software has been started for the first time.  Follow the onscreen instructions for this.  The software will open and you will need to wait until the status has changed to "Idle."
1. The cells of the instrument need to be flushed prior to analysis.
1. Using the tweezers located by the instrument, remove the reference needle plug and set it securely to the side.
1. Using the flushing needle and syringe, flush the reference cell at least 3 - 4 times with ~1.5 mL of degassed DI water.  DI water can be degassed by sonication or by drawing a vacuum for ~15 minutes.
1. To flush the cell, dispense the syringe contents in and out of the cell the desired number of times.  Discard the rinsing water.
1. Fill the reference cell with ~1.5 mL of water.  There should be no water visible once the flushing syringe has been removed.  Remove some of the volume if there is.
1. Using the flushing syringe, remove the contents of the sample cell.
1. Flush the sample cell with ~1,5 mL of the EDTA buffer at least twice.  Discard the EDTA rinse.
1. Load ~1.5 mL of EDTA into the sample cell and allow this to soak within the cell for at least 5 minutes.
1. Following the 5 minutes, discard the EDTA that was in the cell and replace with ~1.5 mL of fresh EDTA for the actual test.
1. Locate the 250 µL buret syringe.  Flush the syringe 2 times with EDTA, followed by one rinse of the calcium chloride solution.  Discard the calcium chloride solution rinse and replace with fresh calcium chloride solution.  You want to fill the syringe with 250 µL of the calcium chloride solution for the test.
1. Place the syringe in the black (aqueous) buret handle, and then insert the buret handle into the instrument.
1. Set the "Stirring Rate" to 350 and press the play icon to start the stirring.
1. Click the "Syringe Size" drop down menu and select the 250 µL syringe.
1. The "Experiment Setup" window will now be adjusted.  Click "Setup" and the "Setup Pulses" window will open.  For the Ca-EDTA titration, change the number of injections to 25, the injection volume to 10 µL, and the injection interval to 300.  Click "Ok."
1. Ensure the "Temperature Setpoint" is at 25.
1. Under "Experiment Details" change the value of the syringe concentration to match the value of the calcium chloride solution (taken from the label) and the cell concentration to match the label of the EDTA buffer.
1. Under the "Equilibration" section, select "Auto Equilibrate."  Medium should be selected for the "Expected Heats."  This selection determines the statistics of the equilibration.
1. The timeout function should be unchecked.
1. Change the "Initial Baseline" to 300.
1. The analysis can now begin.  Click the green play icon at the top of the ITCRUN screen.  Save your data and the analysis will begin.  You can monitor the baseline as the instrument equilibrates by clicking the "Monitor" tab.

### Analysis of the test data
1. Open NanoAnalyze from the desktop.
1. Add the titration file by clicking "File" followed by "Add File."  Click on the "Analysis" tab on the vertical toolbar to display the titration data.\
1. Within this tab, you can subtract the baseline so long as it is satisfactory (resolved).  Points can be added or removed as necessary, but should be done minimally and with caution to improve the baseline before subtracting it.
1. Click the "Area" tab on the "Analysis" tab toolbar to confirm the syringe and cell concentrations are correct.  Likewise, ensure the sample cell volume is 950 µL.  This value is set by TAInstruments at the factory.
1. Correct for the background heat by subtracting the average of the last 3 data points in the area tab under "Area correction."  These values are the Q values within the data columns.  It is extremely important that the sign of the value entered in to be subtracted matches that of the data that was averaged.
1. Click the "Modeling" tab.  To import a model, click the asterisk located below the "Models" box.
1. Choose the "Independent" model and then click the "Select" button.  The independent model calculates the equilibrium constant (k), enthalpy (H) and stoichiometry (n).
1. Anomalous data can be masked by clicking on the data point.  The first data point should be masked due to diffusion of titrant during equilibration.
1. Fit the data using the green play icon.
1. The image below shows what the Ca-EDTA titration data should resemble once fitted.
     ![Example of Ca-EDTA Data](CAEDTA.png)
1. Compare the values calculated from the fit to those of the table below.
     ![Acceptable values of Ca-EDTA Titration.](Acceptable.png)
1. If your test values are within the acceptable values, you may clean the cells to begin your analysis.  If they are not, contact Matt Burleson (Ap 346, mburleson@wcu.edu)


### Acquiring and analyzing data
1. Data collection and analysis for an actual sample will follow the steps outlined above.
1. It is vital that the cells be filled with the same buffer (or as similar as possible).
1. If organics are to be used, use the organic buret handle instead.

### Cleaning and Shutting down the instrument
1. Once your analysis is complete, the cells will be flushed with degassed DI water.
1. Flush the reference cell at least 5 times with degassed DI water.  Fill the cell with fresh degassed DI water after the last rinse, and replace the reference cell plug.
1. The sample cell will be flushed using the cleaning tool which shown below.
     ![Cleaning tool](cleaning.png)
1. Ensure the instrument temperature has adjusted to near ambient before starting the cleaning process.
1. Remove the buret assembly and syringe from the top opening of the Nano ITC, and withdraw the cell contents using the filling syringe.
1. Carefully lower the shaft into the cell opening.
1. Connect the shorter rubber tubing to the side port of the cleaning tool.  Place the free end of this tube in a beaker of clean, degassed DI water.
1. Connect the longer rubber tubing to the top port of the cleaning tool and the other end to the vacuum flask used for cleaning.
1. The connected tubing should resemble that shown below.
      ![Tubing connections](tubing.png)
1. Apply a vacuum to draw the water through the system and flush the cell.
1. Refill the flushed cell with ~1.5 mL of fresh DI water.
1. Contact Matt Burleson to perform a water-water titration to ensure the instrument is ready for the next user.
1. The instrument may be turned off by flipping the switch on the back.
