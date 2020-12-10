# Agilent Cary 5000 UV-Vis-NIR Spectrophotometer Operating Instructions
AF | 2018-08-15

### Capabilities: 175--3300 nm

## Power On and Setup

1. Turn on the Cary moving the on/off toggle switch on the front of the instrument to **|/On**.  Make sure the green light illuminates.  The instrument will take several minutes to warm up and perform a self-test; some clicking and motor noises are normal.
1. Logon using `.\labuser` as the username and `labuser` as the password.
1. Open the software by clicking the **Scan** shortcut on the Desktop.
1. Click the **Setup** button in the upper left corner of the Scan software, and then select `Summary > Instrument Settings > Cary Options` from the menu at the left of the resulting window.
	- For **Absorption** measurements:
		1. Select the wavelength range and units in the *X Mode* section.
		2. Select **Abs** from the *Mode* dropdown menue in *Y Mode*; select appropriate Y-min and Y-max values (0.00 and 1.00 are good defaults).
		3. Select your desired averaging time (*Ave time (s)*), *Data interval (nm)*, and *Scan rate (nm/min)* under *Scan Controls*.
		4. Click **OK** to save your settings.
1. Select `Summary > Instrument Settings > Baseline`, then select the **Zero/Baseline Correction** radio button.

## Making an Measurement
1. Ensure the the instrument has had a chance to come online by checking to see menu bar says "*Scan - Online*" (NOT "Scan - Offline").  If the instrument is not yet online wait a few minutes for it to finish warming up.
1. Block the beam and click the **Zero** button to conduct the 0% T measurement.  Click **OK** in the load sample prompt that appears.
1. Load a blank sample into the cuvette holder and click the **Baseline** button, then click **OK** when the sample is ready.
2. Click the **Start** button (green traffic light) and choose a datafile location for your run.
1. Enter a sample name for the first sample you would like to run and click **OK**.  The instrument will begin scanning through the wavelength range selected; to stop it, press the **Stop** button (stop sign).
1. To run another sample, enter a new name and click **OK**, or click *Finish* to stop collecting data.

## Shutdown
1. Make sure any data you wish to save has been saved and/or moved to `\\neon`.
1. Click the red **X** or `File > Exit` to close the program, as with any Windows program.
1. Switch the toggle switch on the front of the instrument to the **0/Off** position.
1. Log off of the computer.
