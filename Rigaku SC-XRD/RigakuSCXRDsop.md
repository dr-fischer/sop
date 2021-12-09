Rigaku XtaLAB Mini II SC-XRD Standard Operating Procedure
============================

# Safety

- **All users** must obtain X-ray safety training prior to using the instrument.
- All users must sign the log sheet prior to logging into the computer or turning the instrument on.
- Never attempt to turn on the X-ray source when the instrument is open.
- Never attempt to open the instrument when the X-ray is on (i.e. when the red light on top of the instrument and/or orange X-ray light on the front panel of the instrument will be **on**).
- Never attempt to defeat the safety interlocks on the instrument.
- Never adjust or change out any parts of the instrument.
- In an emergency, push the **red, round STOP button** on the front of the instrument.  Notify safety personnel (contact info in SC-XRD binder) immediately.
- Never touch the source; it contains beryllium, which is toxic.
- Users should be trained on liquid nitrogen handling prior to using the instrument.  See the Instrumentation Specialist or Research Operations Manager for this.
- Do not operate the SC-XRD in a manner other than specified in this SOP.

# Login

1. If you have not already done so, reserve time on the instrument calendar.

     > The instrument is available on a walk-up basis ONLY if no other users have scheduled time on the instrument.  Walk-in users still need to reserve time on the calendar and sign the paper log sheet.

1. Write your name on the log sheet and list your start time.
1. Log in to the computer.  Contact the Instrumentation Specialist for a username and password.  *Do not give out the username/password to other users!*

# Turning on the SC-XRD

1. Complete the steps under *Login*, above.
     > Note: anytime the instrument is not measuring, the window protector should be placed over the detector window.

1. Turn on the SC-XRD chiller (white and blue box under the table holding the instrument labeled "Rigaku") by holding the power button on the controller until it kicks on. The chiller should be set to 100 &deg;C.
1. The liquid nitrogen dewar will need to be filled prior to performing an analysis.  You can begin your analysis when the dewar is >50% full (this amount should last a day or two).  Contact the Instrumentation Specialist for assistance with this step.
1. Turn on the air dryer using the power switch on the back of the apparatus.  Ensure the condensate collecting container (also on backside) is empty.  This can go down the sink.
1. Turn on the CryoStream Cooler (left of the instrument) using the button on the back first, and then the button next to the touchscreen.  This button illuminates to show the status of the controller.
     ![Illumination key of CryStram Controller](cryostreamcontroller.png)
<div style="page-break-after: always;"></div>
1. Flip the **breaker switch** on the back of the instrument to **On** (up).  Look for the label on the left side of the instrument, reach around the back and flip the breaker switch up.
     ![Rear view of the XtaLab Mini II power panel](scxrdrearpanel.png)
1. Press the **Power On button** on the front of the instrument.
1. Ensure the "HV Enable" key is turned clockwise.
1. Check that the *Operate Light* is illuminated on the front panel of the instrument.  If it is not lit, notify the Instrumentation Specialist of the problem.  Do not proceed until the operate light is illuminated.
1. Press the "Door Lock" button to ensure the door is locked.  This light blinks when the door is unlocked and stops blinking when the door is locked.
1. Turn on the power of the controlling PC and launch the CrysAlis software.  The software will take a moment to fully initialize.
# Conduct an Experiment

### Setup your sample
1. The detector window protector should still be in place for now.
1. The best position for loading your sample can be achieved by pressing "cmd" in the left-hand pane to bring up the command prompt.
1. Type "GT O -60" and press enter.  This command has the goniometer adjust to -60 degrees in the omega position.
1. There is a beam stop (see diagram below) located as part of the optics components within the sample compartment.  The purpose of this beam stop is to filter out any unreacted X-rays to preserve the lifespan of the detector.  The beam stop should be pressed until flush again the cryo tube emerging from the top of the instrument.  
     ![Beam stop diagram](Beamstop.png)
1. Using the microscope within AP 314, and the parrafin oil, place as few crystals of your sample as possible on the microscope slide.
1. Using the needle next to the microscope, break your crystals into a single crystal as much as possible.
1. Dip the magnetic crystal sample holder in the oil, and then load your crystal sample onto the magnetic holder.
1. Place the magnetic sample holder back onto its post within the door to begin the sample alignment process.

### Aligning your crystal and accounting for the beam stop
1. With the software window open, press the **F12** key to see the crystal alignment view for analysis.  Note that the circle indicates an area of 300 µm.
1. The goal of aligning your crystal is to have it as uniformly in the center of the crystal circle at all angles.
1. This can be accomplished using a combination of the knurled nut and adjustment screw on the goniometer (see diagram below).
     ![Inside view of instrument](goniometer.png)
1. The knurled nut will adjust the vertical axis whereas the adjustment screw will adjust the horizontal.
1. To change the angle of the crystal view, use the **angle arrow keys** in the bottom left corner of the crystal video screen under **Goniometer control.**
1. Continue the alignment process until your crystal is as uniformly centered in the crosshairs across all angles as possible.
1. Once fully aligned, carefully remove the detector window protector and close the door.  Press the door locking button.
1. The shadow of the beam stop onto the detector must be accommodated for when the beam stop is in the correct position.
1. Press the **F12** key to exit the crystal alignment view and return to the main window within the software.
1. To accommodate for the beam stop shadow, once again bring up the command prompt by clicking its icon in the left-hand pane.
1. Within the command prompt, type "card raw on 30" and then press return.  This will open the shutter for 30 seconds to allow assessment of the shadow produced by the beam stop.
1. The software defaults to a blue background which makes seeing the shadow difficult.  Adjust the background of the image by clicking the dropdown arrow next to the paintbrush located in the bottom toolbar within the software and select "Saturn." The background should now change color.
1. Now locate the "CCD" button in the lower right-hand side of the software and click its dropdown arrow.
1. Select "Beamstop/Jet Shadow Overlay." This will load the mask the software uses to accommodate for the beam stop.  It will most likely need to be adjusted.  **This option should always be on.**
1. Click the dropdown arrow by "CCD" once again and select "Adjust Beamstop."  Within the new window that opens, select "Edit beamstop."
1. Adjust the angle until the displayed beamstop overlaps the one observed on the screen.
1. Adjust the Y-offset of the beamstop until it completely masks the observed shadow.
1. Adjust the diameter as necessary so that the shadow overlay is slightly larger than that observed from the sample.

### Turning on the X-rays
1. With your crystal aligned, close the crystal video window.
1. Under the **Start/Stop** window to the right, left click on **X-ray.**
1. Locate the **Set kV, mA, X-ray** button and click it.  A new window will open.
1. Under the **X-ray ramp options** column, select **Default** followed by **OK.**  The X-rays will begin ramping to the default settings.  Allow the beam to be at full power for at least 20 minutes. Close this window.
1. Select **CRYO** under the **Start/Stop** window to the right.
1. Select the **Set** button.  Ensure the target temperature is 100 K at a rate of 360 K/hour.
1. Wait for the temperature to be reached before proceeding.

### Performing the Experiment
1. Press the **Start/Stop** button in the window to the right of the main screen.
1. Select **Start new.**
1. Under **SM Screening**, select the arrow next to **Screen** to see the screening settings.
1. Once these are satisfactory, click **OK & Screen** to assess the diffracting quality of your crystal.
1. We will now create a folder and user for your data.
1. Click the **Edit** button near the bottom of the **SM Screening** window.  A new window labeled **Pre-experiment** will open.
1. Here you can name your sample, create a folder and user as well.  Complete all of these so that your data can be retrieved at a later time.
1. You can enter the expected chemical formula, but note, the formula needs a space after each element.
1. With the formula entered, you may click **Exit & start screening** at the bottom of the window to begin the pre-experiment process.
1. The instrument will begin taking some initial measurements to devise a strategy it deems best for your sample.  It is recommended to always use this strategy.
<div style="page-break-after: always;"></div>
# Shutdown the XRD

1. When your analysis is complete, turn the X-rays off by pressing the **X-ray** button under the **Start/Stop** window.
1. Select **Set kV, mA X-ray.**
1. Under the **X-ray ramp options** column, select **Off** followed by **Ok.**
1. Select **Cryo** under the **Start/Stop** window followed by **Stop.**
1. Be sure to leave the air dryer on overnight after your analysis to prevent any condensation within the instrument.
1. Open the door and replace the window protector over the detector.
1. Remove your sample.  

    > Do not touch the X-ray source as it contains toxic beryllium metal!  Wash your hands immediately with soap and warm water if you do!

1. Enter your stop time on the SC-XRD log sheet.
1. Turn the instrument off by first pressing the **Power Off** button and then by flipping the breaker on the back of the instrument.
1. Allow the chiller to run for 30 minutes; come back and turn it off after 30 minutes have elapsed.
1. Be sure to log out of the computer.

*Take all samples and extraneous supplies with you when leaving.*

### Data analysis
1. Analyze your data per your research group's needs.  The data can be saved to Xenon or printed to Printer 653 located in AP 318.

     > There is a video recorded by Rigaku detailing data analysis saved to the desktop of the instrument's computer.
