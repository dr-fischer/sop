# Perkin Elmer FIMS 100 Flow Injection Mercury System

## Setup

1. Check the calendar and reserve time on the instrument if you have not already done so.
1. Turn on the fume extractor using the "light switch" under the flame AA.
1. Check that the waste tubing is free of clogs, connected to the waste container, and that there is sufficient room in the waste container.
1. Check the 1.1% SnCl<sub>2</sub> / 3% HCL and ultrapure water stock containers and refill if necessary.
1. Fill the plastic cup on the autosampler with 2% nitric acid.
1. Check the tubing on the peristaltic pump (P1) for defects and push the clamps into place.  Please consult with the Instrumentation Specialist if you suspect there are defects in the tubing or the tubing looks out of place.

## Turn On

1. Open the valve on the gas tank to turn on the nitrogen flow.
1. Activate the rocker switch on the left front of the instrument to turn it on.
1. Check that the lamp is on. (You should see a faint glow coming from the left side of the flow tube.)
1. Allow the lamp to warm up for at least 20 minutes. *You may load your samples in the autosampler and prepare your method and sample information file while you wait.*

## Prepare a Run

### Prepare a method

1. Double click the **FIMS Software** shortcut on the desktop.
1. Click the **Method** button below the toolbar and select the `_FIMSdefault` method.  Click **File > Save As > Method** and save a copy of the method under a new name for your run.
1. Enter your standard concentrations, IDs, and autosampler locations under the **Calibration tab >> Concentrations sub-tab**; enter your subtraction blank here as well.
1.  Enter your QC concentrations and limits under the **QC tab >> Concentrations and Limits subtab**.
1. Click **File > Save > Method** and close the *Method Editor* window.

### Prepare a sample information file

1. Click **File > New > Sample Info File**.
1. Enter the autosampler locations and IDs of each sample; you should include any rinse blanks and method/reagent blanks here.
1. Click **File > Save As > Sample Info File** and close the *Sample Info Editor* window. *Do NOT choose Sample Info Design!*

### Prepare an Analysis

1. Click on the **Auto** button in toolbar and make sure the **Set Up tab** is selected.
1. Ensure your sample information file is listed in the appropriate box; **Open** it if not.
1. Click **Open** next to the *Results Dataset Name* box and enter a new name for your results (or choose a dataset you wish to append to).  *Do not change the library location!*
1. Make sure the **Save Data** box is checked.  This ensures your data will be automatically saved.
1. Close the *Automated Control* window.

## Analyze

### Check the instrument for cleanliness (run a blank)

1. Click the **FIMS** icon in the toolbar.
1. Click the **Pump 1** button to turn the pump on.
1. Allow the instrument to pump until you see liquid mixed with bubbles coming out of the waste line on the mixing manifold.
1. Click the **Manual** icon in the toolbar.
1. Enter a sample ID for your first rinse blank.
1. Enter the location of your rinse blank in the box next to **Go to A/S Loc.**, and then click the **Go to A/S Loc.** button.
1. Click the **Analyze Sample** button.
1. Open the *Transient Peaks* window by clicking the **Peaks** button in the toolbar.  You should see a flat line for each blank replicate.  Keep this window open to keep track of the analysis in realtime.
1. Click **Go to Wash Loc.** when the samples is finished running.
1. In the *FIMS* window, make sure the valve is in the **Fill** position and toggle the **Valve Fill/Inject** button several to change it.
1. If the blank is clean, close the *Manual Control* window.
1. If you saw anything other than a flat line in the *Transient Peaks* window, flush the system with 2% nitric acid and rerun your blank until it comes back clean.  Enter a new sample ID for each rinse blank.

### Analyze your standards

1. Click on the **Auto** icon in the toolbar and select the **Analyze tab**.
1. Click **Analyze Standards**.
1. You should see peaks appear for each replicate in the *Transient Peaks* window.
1. You can view your calibration curve in realtime by clicking the **Calib** button in the toolbar.

### Analyze your samples

1. If your standard curve passes quality check, move on and run your samples.
1. In the *Automatic Control* window, click the **Analyze Samples** button.
1. It is now safe to leave the instrument until your run is complete.

## Shutdown

1. When done, pump the 2% nitric acid wash through the sample straw and sample loop for several minutes. Toggle the valve between **Fill** and **Inject** several times by using toggling the **Valve Fill/Inject** button in the *FIMS* window.
1. Rinse the sample straw and sample loop with ultrapure water.
1. Remove the reductant and carrier tubing from the stock containers and place them in a large beaker of *ultrapure* water.  ***Avoid contamination! Do NOT touch the filters or straws! Do NOT set them down on anything!***
1. Once the instrument has been cleaned with ultrapure water, it must be dried.  Remove the tubing from the beaker and place it in a *clean*, dry beaker. Allow the instrument to pump air for several minutes, until you see no more liquid in the waste line.  
1. Place the tubing back in the stock bottles.  Make sure you don't get the tubing mixed up!
1. When the instrument is dry, turn off the pump by clicking the **Pump 1** button in the *FIMS* window.
1. Close the software.
1. Turn off the instrument with the main rocker switch.
1. Release the clamps on the peristaltic pump.
1. Empty the 2% nitric acid wash cup, remove your samples from the autosampler, and clean up your work area.
1. Turn off the ventilation with the switch under the AA.

## Export Data

1. Click on the **Data Manager** shortcut on the desktop.
1. Choose your results dataset in the main window.
1. Click the **Export** icon in the toolbar.
1. Choose **Use Existing Design** and select `_FIMSdefault`.
1. Click **Finish**, then **Export Data**, then **Finish**.
1. You data will appear as a text file in the Reports folder (shortcut on desktop).

<center>
***Log off of Windows when you are done***
</center>


## Suggested Run List

1. Rinse Blank
1. Subtraction Blank
1. Low Standard
1. Medium-low Standard
1. Medium Standard
1. Medium-High Standard
1. High Standard
1. Rinse Blank
1. QC
1. Samples 1 - 10
1. QC
1. Samples 11-20
1. QC  
     ...
1. Samples *n* - *m*
1. QC
1. Rinse Blank [*You **must** run a final blank to ensure the instrument is left clean!*]
