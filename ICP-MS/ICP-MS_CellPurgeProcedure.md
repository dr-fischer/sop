# Conditioning Procedure for Perkin Elmer NexION 2000 ICP-MS
022324MB01
# Scope
This procedure details the conditioning/preparation of the dynamic reaction cell (DRC).
# Responsibility
This procedure should be performed either by the Instrumentation Specialist, or under direct supervision of the Instrumentation Specialist.  Due to the inherent sensitivity of a mass spectrometer and the use of caustic solutions, gloves should be worn at all times when working at the front of the instrument.

# Definitions
1. **Dynamic Reaction Cell (DRC)** - A cell placed after the ion optics but before the mass analyzer quadrupole.  The DRC is capable of <i> both </i> ion-molecule collisions/reactions to cleanse the ion beam of interferents.  When used in collision mode,<i> Kinetic Energy Discrimination </i> is used to reject any undesired products.  When used in reaction mode, a reaction gas (ammonia, oxygen, etc.) is introduced into the cell to stimulate ion-molecule reactions.  The choice of gas is determined by thermodynamics to favor exothermic (spontaneous) reactions, due to the ionization potential of the interferent ion being much larger than the reaction gas.
1. **Kinetic Energy Discrimination (KED)** - One way to remove interferent ions.  A low reactive gas (typically He) is used to induce collisions with the polyatomic interferent.  Because the interferent has a larger collision cross-section (due to its larger size than that of the analyte ion), it will collide more frequently with the gas, and thus lose more kinetic energy.  By placing an energy barrier at the exit of the cell, the lower energy the lower energy interferent can be eliminated.

# Required Reagents
1. 5% Nitric Acid Solution (Made from Trace Metals Grade Nitric Acid).
1. 10% NH<sub>3</sub> in He gas.
1. UHP (or better) O<sub>2</sub> gas.
1. UHP (or better) He gas.

# Gases and Startup
1. Turn the chiller on by pressing its power button.  Allow the chiller sufficient time to reach 15 C.
1. The ICP-MS uses argon gas for the plasma.  The argon can be turned on using the main valves of the four cylinders.

  >**85 - 95 PSI of argon is required!**

3. Wearing gloves, visually inspect the tubing of both peristaltic pumps for the autosampler and instrument.  Replace the tubing if there is any obvious holes or flat spots.
4. Wearing gloves, affix the tubing to the peristaltic pumps making sure not to cross over each line with another.  The pump on the ICP-MS rotates counterclockwise to introduce the sample into the spray chamber.
5. Clamp the tubing to the pumps.  The ICP-MS pump has a "Tube saver" feature, so you may observe it rotating clockwise and then counterclockwise
6. Open the Syngistix software by clicking the icon on the desktop.  The launch window of the software is shown below.
      ![Syngistix Launch Window](Syngistixmainscreen.png)
      > A red icon indicates a system fault.  The image shows an argon gas fault due to the cylinders being off as an example.

1. The instrument's cones, including the sample cone, skimmer cone and hyper skimmer cone, should all be inspected prior to use.  Replace any worn cone to ensure optimum beam transmission.
1. With the cones inspected and satisfactory, the plasma can be ignited.
1. Click the toggle switch located under **Plasma** in the main Syngistix window.  The plasma ignition process will initiate.
1. Allow the plasma to stabilize for 20 mins prior to any analysis, including the next steps.
1. The picture below shows the status screen after the plasma has been successfully ignited.
      ![Plasma On Status](plasmaonstatus.png)
1. Initialize the autosampler by clicking the **Autosampler** icon in the left-hand toolbar shown below in yellow.
      ![Autosampler icon](syngistixlefttoolbarautosamplerhighlighted.png)
1. Click the **Initialize** button to establish connection to the autosampler.  The screen should look like the image below if the communication is successful.
      ![Autosampler Initialized](syngistixautosamplerinitialized.png)
>Ensure that the probe is **NOT** sent to standby after batch completion.

14. Proceed to the Workspace procedure below after the plasma has had 20 minutes to stabilize.
<div style="page-break-after: always;"></div>

# Workspace Procedure
1. Click **File** and navigate to **Workspace** and select **Open Workspace.**
1. Select the **Conditioning the cell for KED Mode manual.wrk** workspace file and click **Open.**

# Loading Conditioning Conditions
1. Navigate to the **Conditions** tab.
1. Click **File** followed by **Open.**
1. Select the **Cell Conditioning.dac** Conditions file and click **Open.**
>The difference between the Default and Cell Conditioning files is that the Cell Conditioning file loads a lower argon flow rate due to the procedure requiring extended times with the plasma on.

# Loading the Conditioning Method
>The steps below detail the files for KED mode.  If other gases (O<sub>2</sub> or NH<sub>3</sub>) are to be used, select the files labeled for those gases.


1. Click on the **Method** icon.
1. Click the **Syngistix ball** followed by open.  Locate the method **Conditioning the cell for KED mode manual** and load it.
>The flow rate for the helium should be quite high, ~ 6.

3. Place the autosampler probe into the 2-L bottle filled with the nitric acid wash solution.

# Batch Sample analysis
1. Click on the **Sample** icon.
1. Because the Conditioning Workspace was loaded previously, the sample table should be filled out already and resemble that as shown below.
      ![Conditioning Sample Batch](conditioningsamplebatch.png)
1. Click the **Batch Index** tab to select all the samples.
1. Click the **Analyze Batch** button.
1. When the **Run List** window opens, ensure that **Autostop** is checked and that **Stop Criteria is set to Batch Completed.**  This will tell the instrument to kill the plasma when the conditioning has been completed as the conditioning can take ≥ 12 hours.
