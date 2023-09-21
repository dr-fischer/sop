# Tuning/Calibration and Optimization of Thermo Fisher TSQ Quantum Ultra MS/MS SOP
062323MB01
>**For urgent problems please report to Matt Burleson, AP 346, mburleson@wcu.edu, x2239!***

# Scope
This procedure details the tuning/calibration and optimization of the mass spectrometer via direct infusion with a syringe pump with and without LC flow.

# Definitions
1. **Auxiliary gas** - The outer-coaxial gas (nitrogen) that assists the sheath (inner-coaxial) gas in dispersing and/or evaporating sample solution as the sample solution exits the APCI, ESI, or H-ESI nozzle.  The auxiliary gas also sweeps solvents out of the API source to help keep the interior of the ion source as dry as possible. The auxiliary gas is used especially at higher solvent flow rates.  In some cases, signal intensity can be increased by using Auxiliary gas, particularly for higher LC flow rates.
1. **Ion Sweep Gas** - Extra nitrogen gas that flows along the axis of the ion transfer capillary (between the Ion Sweep cone and the capillary block) towards the source spray. The Sweep gas flow is thus countercurrent to the flow of the ions. The Sweep gas helps to desolvate many compounds and prevents the accumulation of solvent on the entrance of the capillary.  When Sweep gas is used, the nitrogen flows out from behind the sweep cone and can result in solvent declustering and adduct reduction.  When you are analyzing complex matrices such as plasma or nonvolatile salt buffers, as well as high flow rates, Sweep gas is required for ruggedness.
1. **MS/MS Scan Mode** - Scan mode in which two stages of mass analysis are performed. In the first stage, ions formed in the ion source are analyzed by a first analyzer. In the second stage, the mass-selected ions are activated by collision with a neutral gas (argon), and the resultant ionic fragments are mass analyzed by a second analyzer. MS/MS scan modes include Parent, Product, and Neutral Loss (or Gain).
1. **Sheath Gas** - The inner coaxial gas (nitrogen), which is used in the API source, that helps to nebulize the sample solution into a fine mist as the sample solution exits the ESI or APCI nozzle.
1. **SIM (Selected Ion Monitoring)** - A scan type in which the mass spectrometer acquires and records ion current at only one or a few selected mass-to-charge ratio values. Selected ion monitoring generally provides higher sensitivity than does a full scan mass spectrum since the data acquisition is done in particular mass-to-charge ratio windows, not over a broad mass range. The signal to noise ratio improves at the cost of the amount of structural information returned.
1. **SRM (Selected Reaction Monitoring)** - A scan type in which a particular reaction or set of reactions is monitored. Like selected ion monitoring (SIM), selected reaction monitoring (SRM) allows for the very rapid analysis of trace components in complex mixtures and can be employed in any of the commonly used MS/MS scan modes.  In SRM a limited number of parent-ion / product-ion pairs are monitored. A parent ion is selected as usual; however, the entire mass spectrum of its product ions is not obtained. Rather, only one or a few selected product ions are monitored.

# Gases and Startup
1. The LC-MS uses both argon and nitrogen gases.  The nitrogen should already be flowing in the lab.  The argon can be turned on using the main valve of the cylinder and the quick connect valve towards the back of the mass spec (while doing MS/MS only).
1. Ensure the Service Mode switch located on the right-side of the instrument is in the up (operation) position.
1. The **Tune Master** software is used for these procedures.  Open the software by clicking on the shortcut on the desktop.
      ![Tune Master Icon](tunemastericon.png)
<div style="page-break-after: always;"></div>
4. Navigate to the System Tune and Calibration Workspace (in yellow below) if the software isn't there by default.  You may have to click the play/pause icon to take the MS out of standby mode to change workspaces.
      ![Cropped System Tune & Calibration Workspace](Autotune&calib_cropped.png)


# Tuning and Calibration Procedure for Positive Mode
1. Load the 500 µL syringe with the 1,3,6 polytyrosine standard.
1. Press the pause button to turn on the instrument from standby.  This will turn on the voltages and gases to the source as well as begin the scanning process.
      ![Tune Master Toolbar](tunemastertoolbarhighlighted.png)
1. Select the "Autotune & Calib" tab directly below the pause button.
      ![Cropped System Tune & Calibration Workspace](Autotune&calib_cropped.png)
1. Select the 1,3,6 polytyrosine standard from the dropdown compound list.
1. Begin infusing the standard at 15 µL/min.  Allow sufficient time for the peaks of 182, 508 and 997 m/z to show in the bottom left window.
    1. If needed, the mass range in view can be adjusted by clicking the "Instrument Method Development Workspace" icon.
          ![Instrument Method Development Workspace](instrumentmethoddevelopment_cropped.png)
    1. Ensure the Scan Type is set to "Full Scan", the Scan Mode is set to "Q1MS", and Scan Range is set to "FM/LM" for first/last mass.
          ![Mass Adjustment](massadjustment.png)
    1. Change the first and last mass to 150 and 1100, respectively.  Click "Apply" to change the mass range.
    1. Repeat this procedure as necessary for Q3.
    1. Return to the System Tune and Calibration Workspace.
1. When the peaks in the previous step are present, ensure that the "Both" tab is selected to calibrate both quads.
1. Press the "Start" button to begin the process.  The process takes ~20 minutes.
1. When the procedure has finished, you will be given the option to either accept or undo the changes made during the procedure.  Click "Accept" to apply the changes.
1. A popup will ask if you want to copy the tune parameters to Negative Ion Mode as well, click "Yes."
1. Save the tune and calibration by clicking the "Save Calib" button.
1. It is best to calibrate the gain after the tuning and calibration procedure above has been performed.  Do this by clicking the "Gain" tab.
![Cropped System Tune & Calibration Workspace with Gain](gaincalibration.png)
1. Select one of the three masses shown in the mass table to calibrate the gain.  Delete the other two by clicking on them and pressing the "Delete" key on the keyboard.
1. Press the "Start" button to begin the process.  The process takes ~2 minutes.
1. When the procedure has finished, you will be given the option to either accept or undo the changes made during the procedure.  Click "Accept" to apply the changes.
1. Save the tune and calibration by clicking the "Save Calib" button.  Overwrite the file that was saved in the Autotune and Calibration procedure earlier.
<div style="page-break-after: always;"></div>
# Tuning and Calibration Procedure for Negative Mode
1. The procedure to Autotune and Calibration is the same for negative mode as above with a few exceptions:
  1. Change the polarity from positive mode to negative mode by clicking the "+" icon so that it changes to a "-".
      ![Cropped System Tune & Calibration Workspace Negative Polarity](negativepolarity.png)
  1. Use the dropdown arrow under "Compound" to select "Polytyrosine - Neg" standard from the dropdown compound list.
      ![Cropped System Tune & Calibration Workspace Negative Calibration](negativecalibration.png)
  1. Use the Optimize Compound Dependent Devices button (shown below) and clicking on each to adjust the parameters of spray voltage, sheath gas and auxiliary gas.  Recommended starting values are 2800, 20 and 10, respectively.  Press "Enter" after each adjustment.
        ![Dependent Devices](dependentdevices_cropped.png)
1. Repeat the same steps from the previous tuning section to perform the Autotune and Calibration.
>Sucrose in 1:1 MeOH : Water +0.1% formic acid is a good check standard.

<div style="page-break-after: always;"></div>
# Optimization Procedures

1. The optimization procedure is useful for tuning the instrument for a user specific compound.  You can select to optimize the standard set of devices that are associated with the chosen optimization mode (MS Only, MS + MS/MS, or SRM), or you can select to optimize a custom set of devices (more time consuming and advanced).  The procedures below is for using the MS Only optimization.

## Standard (Quick) Optimization
1. First, change the tune mass to the parent mass of your compound.
  1. Click the "Instrument Method Development Workspace" icon.
  1. Ensure the Scan Type is set to "Full Scan", the Scan Mode is set to "Q1MS", and Scan Range is set to "Center Mass" for the mass of your compound.
  1. Change the "Scan Width" to 10.  Click "Apply" to change the mass range.
1. Load the 500 µL syringe with the sample and begin the infusion at 15 µL/min.
1. Click the "Compound Optimization Workspace" icon.
      ![Compound Optimization](compoundoptimization.png)
1. Select your optimization mode to MS Only.
1. Ensure your center mass from above is listed as the Optimization Mass.  Repeat Step 2 if needed.
1. Under "Optimization Options," select "Standard."
1. Press the "Start" button to begin the process.
1. When the procedure has finished, you will be given the option to either accept or undo the changes made during the procedure.  Click "Accept" to apply the changes.
1. Resave the current calibration/tune file after each optimization.
<div style="page-break-after: always;"></div>

## Custom (Advanced) Optimization
1. First, change the tune mass to the parent mass of your compound.
  1. Click the "Instrument Method Development Workspace" icon.
  1. Ensure the Scan Type is set to "Full Scan", the Scan Mode is set to "Q1MS", and Scan Range is set to "Center Mass" for the mass of your compound.
  1. Change the "Scan Width" to 10.  Click "Apply" to change the mass range.
1. Load the 500 µL syringe with the sample and begin the infusion at 15 µL/min.
1. Click the "Full Instrument Control Workspace" icon (highlighted in yellow below) and ensure the tune mass (highlighted in red below) is the mass you changed to Step 1.
      ![Full Instrument Control Workspace with Tune Mass Highlighted](fullinstrumentcontrol.png)
1. Click the tab of the quad you want to optimize your compound for.  You have the options of Q1, Q3 or MS2.
      ![Full Instrument Control Sidebar](fullinstrumentcontrolbar.png)
1. From here you have the options to optimize the various parameters that you choose.
1. With your desired option selected, click the "Optimize" button to begin the process.
1. When the procedure has finished, you will be given the option to either accept or undo the changes made during the procedure.  Click "Accept" to apply the changes.
1. Save the tune file as a new, uniquely named file.

## Custom (Advanced) Optimization With LC Flow
1. The above advanced optimization can/should be repeated with LC flow.
2. 
1. Change the mobile phase composition to representative composition within your method, but note **there should be at least 20 % water.**
   
1. Disconnect the waste line at the tee that splits the LC eluent to the waste and mass spectrometer, and replace it with a red PEEK line that will be connected to the syringe pump.
   
1. Infuse the sample at a rate of 20 - 25 µL.
   
1. Turn the pump on with the selected mobile phase composition at a flow rate of 500 µL/min.
   
1. Once the peak(s) of your sample are observed, repeat the optimization procedure from the previous section.
   
1. When the procedure has finished, you will be given the option to either accept or undo the changes made during the procedure. Click "Accept" to apply the changes.
   
1. Save the tune file as a new, uniquely named file.

# Standby
1. When your finished with the instrument, ensure the MSD is in standby mode with the argon gas turned off until ready for analysis by clicking the green arrow at the top left of the software.
