Physica Modular Compact Rheometer-101
MB | v20220216

### Start-up Procedure
1.	Verify that the air pressure is 5 bar or slightly above.
1.	Check water level in circulator (only add DI water).  Check water every week for cleanliness.
1.	Turn on circulator pump.
1.	If instrument is off turn instrument switch on.  After a short start time device should say “Status: OK”
1.	Remove foam bearing block or Teflon bearing guard.
1.	If the instrument was left on go to step 12.
1.	Initialize the instrument by following steps 8 - 11.
1.	Open Rheoplus v3.40 software using the desktop icon.
1.  Open the default template by clicking "File" followed by "Open."  The default template is named "Default".
1.	Open the control panel by clicking "Control Panel: Rheometer..." or by on the icon of the instrument in the top toolbar.
1.	Click the “Initialize” button.  This should be performed once per power cycle.
1.	Allow electronics to stabilize for one hour (this warmup is important because the rotors expand while warming up).  The Teflon bearing guard should be attached at this point and removed when the instrument is ready for the next step.
1.	Install the measuring system, making sure to match the lines on the measuring system shaft and the coupling.  Steps 13 - 15 detail the installation of the measurement system.  The larger diameter measurement system is better for samples that easily flow.  The smaller measurement system is better suited for samples that are more viscous.
1.  Push up on the locking sleeve.
1.  Insert the measurement system and hold in place ensuring the vertical line on the measurement system is aligned to the small vertical line on the coupling .
1.  Pull the locking sleeve down to lock the measurement system in place.  The instrument will beep and display the installed system on the front panel display.  The status will read "O.K" if installed correctly.
1.	In the Control Panel set the temperature to the desired setting.  This switches on the Peltier temperature control system.  Check the Fisher clock for the room temperature reading.  Make sure that you set the temperature in control panel when you’re doing anything besides a temperature sweep.
1.	In the Control Panel set the zero gap by pressing the “Set Zero Gap” button.
1.	Determine the inertia of the measuring system.  For this determination follow steps 19 - 22.
1.	Go to the “Service” tab of the control panel.
1.	Press the “Meas. System” button.
1.	Press “Start” button in the pop-up window.
1.	After determination click the “Save” button.
1.	Perform a motor adjustment.  For this adjustment follow steps 24 - 27.
1.	In the “Service” tab press the “Motor Adjustment” button.
1.	Select the installed measurement system and press the “Start” button followed by "Continue" in the pop-up window.
1.  Click "OK" if asked about replacing motor adjustment data.
1.	After the adjustment has completed, press the “OK” button.
1.	Press the “OK” button in the Control Panel and “Yes” when asked to save changes.

### Procedure for sample loading and analysis
1.	The sample loading is the same for all tests.  However, before loading the sample ensure the sample is properly mixed.
1.  Using the control panel within the software, move the measurement system to the lift position by clicking "Lift Position."
1.	Using either a pipet or spatula, place sample on the bottom plate.
1.	Click “Meas. Position.”  A window will appear once the trimming position has been reached.
1.	If the sample has a lower viscosity, take the flat end of the spatula and scoop out any emulsion that has squeezed out.  If no emulsion squeezed out around the measurement system more sample should be added.  If the sample has too low of a viscosity to be trimmed in this manner, DO NOT dab it with a Kimwipe.  Dabbing with a Kimwipe will take sample from under the plate.  Be careful not to tap the measurement system while trimming.
1.	Once you have trimmed and clicked “Continue,” you should place the white plastic insulators gently around the plates.  This insulation prevents any air drafts from drying out the sample as well as maintaining an even temperature.
1.  Click "OK" to close the control panel window and return to the main window of Rheoplus.
1.  Click "Edit Pre-shear Interval."  Ensure there are 5 measurement points with the time unit set to minutes.  The profile should be "Fixed meas. pt. duration" with 1 measurement point a minute for an interval of 5 minutes.  Click "OK."
1.  Click "waiting Time after Pre-shear."  Ensure there are 5 measurement points with the time unit set to minutes.  The profile should be "Fixed meas. pt. duration" with 1 measurement point a minute for an interval of 5 minutes.  Click "OK."  Also within this window, ensure "Data Recording On" is selected.
1.  click “Edit Meas profile” there should be 10 measurement points; the time unit should be in minutes; the profile should be in fixed measurement point duration; and the measurement point should be 1 per minute at an interval of 10 minutes.  Click "OK."
1.	Next click “Start test” and name the sample.  You should include the percent/amount of everything in your sample.  For remark you should add any details that seem relevant.
1.  In this same pop-up window go to the tab “Waiting before Starting Test” and select "With Waiting Time."  Set the wait time to 5 minutes.  This ensures the sample heats/cools to the same temperature as the instrument.
1.  Click “Start the Test Now” to begin the analysis.

### Cleaning the instrument
1.	Clean the plate and measuring system after each test (even if it’s the same sample).  Use a Kimwipe to wipe the majority of the sample. Next wet a Kimwipe with acetone or hexane and clean the measuring system and plate.  Make sure it has evaporated before loading next sample.

### Performing calculations
1.  Once the test has completed, click "Start Calculation (Analysis 1)" to perform the data analysis.
1.  The regression parameters of the calculations can be adjusted as needed using the menus within the "Advanced Regression Setup" options.

### Exporting data
1.  To export data, click "File" followed by "Export."  To the right will open a submenu that will allow you to export the data in various formats.  Select the appropriate format and save it with a unique datafile name for easy retrieval.  Data can only be retrieved using a flash drive.

### Troubleshooting
1.	If the sample freezes (for 10% wax emulsions, it’s below 5 ℃), a sharp increase in viscosity (table will have errors) and frost forming on the measurement system will be observed. Set the temperature (in control panel) to 23 ℃ before attempting to lift the measurement system.  The Rheometer makes weird noises at different temperatures sometimes, don’t be alarmed.
1.	If there are large air bubbles on the plate, remove them using a pipet.
1.	If there are a lot of peaks, that means there are either vibrations from the room or the emulsion is extremely unstable. Something as simple as bumping into the bench could cause a peak so it’s best to leave the room entirely during tests.
1.	If you drop the measurement system OR bump hard against the instrument, inform the Instrumentation Specialist your research advisor immediately. This could potentially ruin the instrument.
1.	If you are trying to calculate LVE range but windows keep popping up about values missing, go to the white arrow on the top left and click that. Then click the first G’ point and the second to last G’ point on graph. It should now be highlighted. Then right-click, go to “Analysis” and then “LVE range”.  Make sure you delete error points before calculating LVE range.
1.	To do calculations, select the current measurement for the graph of interest.  Located on the left there is a pencil in the corner above all the samples.  Click this pencil and the highlighted sample will be open for you to edit (unclick or click current measurement).
1.	You can calculate flow point and LVE range next if interested. This does need to be calculated if further oscillatory tests (such as a frequency sweep) are planned.  Though generally, the current LVE range on a frequency sweep is good enough for most samples.
1.	For the temperature sweep, add a wait time in the measurement window of about 10 to 15 minutes.
<div style="page-break-after: always;"></div>
### Shutdown Procedures
## Procedure One:
When the instrument is to be used the next day:
1.	Open the control panel by clicking on the icon of the instrument or through “Device” “Control Panel”.
1.	Under “Temperature,” press the “Switch off” button to switch off the Peltier temperature control system.
1.	Turn off or unplug the water circulator.
1.	Remove the measuring system.
1.	Attach the Teflon bearing guard.
1.	Remember to shut off the air.

## Procedure Two:
When the instrument will not be used for a while:
1.	Remove the measuring system.
1.	Attach the Teflon bearing guard or foam bearing block.
1.	Turn off the instrument using the power switch.
1.	Turn off the water circulator.
1.	Remember to turn off the air.
