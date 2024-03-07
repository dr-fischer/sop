# Leica ACE600 Dual Coater System SOP
022624MB01
>**For urgent problems please report to Matt Burleson, AP 346, mburleson@wcu.edu, x2239!***

# Scope
This procedure details the general use of the coater system as part of SEM sample preparation.  The operation of the SEM is detailed in a separate SOP.

# Responsibility
1. Because this is a shared system, it is the responsibility of each individual desiring to use the system comply with the procedure of this document as written.  
1. It is the responsibility of the Instrumentation Specialist to train users first on an in-person basis.
1. No sharps are permitted near the touchscreen.
1. Each user **MUST clean the system appropriately before leaving.**  Failure to do so will result in suspended privileges of the system.

**The system should always be left in a pumped or standby state.  The standby state is used for longer periods (> 1 week) between anticipated use.**

# Materials
1. Carbon Thread
1. Coater Ruler
1. Scissors
1. SEM Sample on Stub
1. KimWipe
1. Ethanol
1. Nitrogen and Argon gases (set to 7.5 - 12 psi).

# Description of Processes
1. The carbon coating process is carried out by evaporating a carbon thread.  The default method is **Pulse Mode** where the process can be terminated according to the desired thickness or a set user-defined pulses.
1. Magnetron sputter coating is performed using ionized argon to create a plasma.  The argon ions are accelerated by a high voltage and directed towards the source via a magnet where they collide with the target and displace surface atoms.  Due to this collision, the surface atoms are directed towards the area below the target and coat the sample.  Historically, the most frequently used sputter coating material has been gold because of its high conductivity and relatively small grain size, which makes it ideal for high-resolution imaging. If energy-dispersive X-ray (EDS) analysis is required, SEM users typically coat their samples with carbon due to carbon’s X-ray peak does not conflict with the peak of any other element.
<div style="page-break-after: always;"></div>

# Assessing Carbon Thread and Au/Pd Targets
1. Ensure the regulators of both the argon and nitrogen gases shows flow going to the coater.
1. **Vent** the system by pressing the **Vent** button on the coater touchscreen.  Allow the vent cycle to complete before proceeding.
1. Wearing gloves, ppen the top cover to observe the heads.  The **left** is for **carbon thread** and the **right** is for the sputter target.  The image below shows the two labeled heads.
<img src="Heads.png" alt="System Heads" width="450"/>
1. Disconnect the power cable to the head you anticipate to use.  Each connection has two clips that need to be pressed to release the cable(s).  The clips are shown below.
<img src="Clips.png" alt="Head Clips" width="450"/>
1. Remove the head by loosening the thumbscrews holding them in place.
<img src="Thumbscrews.png" alt="Head Clips" width="450"/>
1. Place the head (electrical connections down) on a surface covered with either a KimWipe or a piece of aluminum foil.  The image below shows both heads removed in the described manner.
<img src="Headsurfaces.png" alt="Head Surfaces" width="450"/>
1. Assess the Au/Pd target.  If it appears too spent notify Matt Burleson. **The carbon thread should be replaced before each use.**  This will be detailed in the next section.
1. Place the heads back on the system (orientation matters).  Tighten the thumbscrews and connect the power cables.
1. On the touchscreen, tap **Pump** to begin the pump down of the chamber.
<div style="page-break-after: always;"></div>

# Replacing the Carbon thread
1. The carbon thread should be replaced before each use.
1. With the head removed and on a sturdy surface as described above, use the TORX screwdriver (kept in the Coater Supplies drawer) to loosen each carbon thread head.
1. Dispose of the spent carbon thread in the trash.
1. Locate the spool of carbon thread in the same drawer as the TORX screwdriver.  A good way to measure the necessary length for all of the carbon thread heads is to cut a piece the length of sample chamber door.  A single thread is good for ~ 15 nm and double threading will give ~ 30 nm.  To double thread, cut two identical in length pieces of thread and entwine them with your fingers.
<img src="lengthofthread.png" alt="Length of thread measurement suggestion." width="350"/>
1. Using the cleaning brush, clean the surface shown below.
<img src="carboncleaning.png" alt="Threading Order." width="350"/>
1. Begin by wrapping the thread around the thread head labeled as **<i>A</i>** below.
<img src="threadingorder.png" alt="Threading Order." width="350"/>
1. There is a step that is part of the clamping mechanism.  **DO NOT** let the thread be clamped in here.  This area is shown below.
<img src="threadheadstep.png" alt="Thread Head Step." width="350"/>
1. With the thread around head **<i>A</i>** tighten the screw with the TORX screwdriver.
1. Continue the threading going alphabetically, but don't tighten the heads until fully threaded.  Once fully threaded, tighten the **Last** head (<i>E</i> in the image above) to hold the thread at tension.
1. Remove any excess thread with scissors.
1. The head should now resemble the start of the process with the new thread.
1. Replace the head on the system and its power cable connections.

# Loading Samples
1. The lower toolbar of the software has a button for the option of turning the chamber light on or off.
1. Open the chamber door.
1. The planetary stage can hold up to 24 samples total and utilizes six mini stages that spin to ensure uniform coating on all surfaces.
1. Place sample on the planetary stage of your choice.
<img src="stage.png" alt="Main and Planetary Stages." height="350"/>
1. Using the ruler, measure the height of the sample from the surface of the planetary stage to the top of the sample stub as shown below by **<i>S</i>.**
<img src="sampleheight.png" alt="Sample Height." height="350"/>
1. Close the chamber door.
1. Press the **Pump** button to begin the pump down process.  Allow good vacuum to be reached (indicated as green by the vacuum bar).

# Quartz Thickness Monitor Testing
1. Before each analysis it may be necessary to test the quartz thickness monitor.  
1. Press the **Menu** button on the main screen of the software.
1. Select the **Quartz** tab.
1. Ensure that **Quartz type** is set to **stage.**
1. Press the start button to begin the test.
>A quartz crystal swings in a certain frequency.  Coated with a material, this frequency reduces according to the material and the applied thickness.  With this information, the accurate film thickness coated during a process can be monitored.  A new quartz has a frequency of ~ 6 MHz.


6. If the test is successful, proceed to the next section.  Alert Matt Burleson if the test fails.
1. The **Main** button will return the software to the starting screen.

# Selecting A Protocol
1. On the main menu of the coater are two options labeled as **Carbon Thread** or **Sputtering.**  Select the desired protocol by pressing its respective button.
1. Once opened, the screen will show the list of available coating procedures which are detailed in the next sections depending on the desired coating.

# Carbon Thread Protocol
1. Select **Open** under **Carbon Thread** on the main screen to enter the process screen.  The process screen is shown below.
<img src="carbonthreadprocess.png" alt="Carbon Thread Process Screen." width="350"/>
1. The library of protocols available can be selected by tapping the Library button labeled as **<i>1</i>** above.
1. Tapping the Characteristics of the protocol (labeled as **<i>2</i>** in the above image) opens the list of recipes.  There, the parameters for the process can be changed and saved (shown below).
<img src="carbonthreadprotocol.png" alt="Carbon Thread Protocol Screen." width="350"/>
1. Once a protocol is marked (as Pulse Single is above), by tapping on a specific category, the parameters can be changed.
1. If method is selected, the screen below will display.  The method should be left as **<u>Pulse</u>.**  Ensure the **Quartz usage** box is ticked for thickness monitoring.  **<u>Only tick Double Thread if two threads were entwined earlier.</u>**
<img src="editingcarbonprotocol.png" alt="Carbon Thread Method Edit Screen." width="350"/>
1. Adjust the thickness to the desired measurement.
1. Tap **Save** to save the updated method.
1. Back in the Characteristics screen, tap the **Stage** properties.
<img src="carbonstageprotocol.png" alt="Carbon Stage Method Edit Screen." width="350"/>
1. Defining the sample height ensures that the working distance is kept constant during the coating.
1. A user-defined tilt can be entered.  Tilting the stage influences the coating angle.
> **Note:** The carbon thread head is already at 25 ºC.


12. Rotation can be set to continuous (recommended) or a 120º rotation after each pulse.
1. Settings on this page can be checked using the **Test** button.  The **Init** button stops the testing and moves the stage to the initial position of the method.
1. Tap **Save** to save the updated method.
1. Use the **Back** button to get back to the main Carbon Thread Protocol window.
1. Once all the relevant parameters for the coating process has been defined, the process can be started using the **Start** button.

# Sputter Coating Protocol
The process for performing sputter coating is similar to that of carbon thread above.
1. Select **Open** under **Sputtering** on the main screen to enter the process screen.  The process screen is shown below.
<img src="sputteringprocess.png" alt="Sputtering Process Screen." width="350"/>
1. The library of protocols available can be selected by tapping the Library button labeled as **<i>1</i>** above.
1. Tapping the Characteristics of the protocol (labeled as **<i>2</i>** in the above image) opens the list of recipes.  There, the parameters for the process can be changed and saved (shown below).
<img src="sputteringprocessesscreen.png" alt="Sputtering Protocol Edit Screen." width="350"/>
1. Once a protocol is marked (as Iridium is above), by tapping on a specific category, the parameters can be changed.
1. If method is selected, the screen below will display.  Change the **Time,** **Thickness** and **Current** to the desired values.  Ensure the **Quartz usage** box is ticked for thickness monitoring.  Presputtering depends on the material (see reference material).
<img src="sputteringparameters.png" alt="Sputtering Edit Screen." width="350"/>
1. Tap **Save** to save the updated method.
1. Tap **Back** to return to the Characteristics screen.
1. Back in the Characteristics screen, tap the **Stage** properties (same as carbon thread).
<img src="carbonstageprotocol.png" alt="Sputtering Stage Method Edit Screen." width="350"/>
1. Defining the sample height ensures that the working distance is kept constant during the coating.
1. A user-defined tilt can be entered.  Tilting the stage influences the coating angle.
> **Note:** The sputter head is already at 25 ºC.


10. Rotation can be set from 1 to 5 (20 rpm).
1. Settings on this page can be checked using the **Test** button.  The **Init** button stops the testing and moves the stage to the initial position of the method.
1. Tap **Save** to save the updated method.
1. Tap **Back** to return to the Characteristics screen.
1. Two kinds of vacuum cycles have to be defined.  The vacuum needs which needs to be reached before the sputter process starts (base vacuum) and the sputter vacuum which will be adjusted by letting argon gas in the chamber.  One purge cycle flushes argon in for 10 seconds and then pumped for 30 seconds.  Always use **at least one purge cycle.**
<img src="sputteringvacuum.png" alt="Carbon Stage Method Edit Screen." width="350"/>
1. Tap **Save** to save the updated method.
1. Tap **Back** to return to the Sputtering homepage.
1. Once all the relevant parameters for the coating process has been defined, the process can be started using the **Start** button.

<div style="page-break-after: always;"></div>
# Removing Coated Samples
1. When the coating process is completed, the samples will remain in the chamber under vacuum.  On the main page of the software, tapping **Vent** will vent the system and allow sample retrieval.
1. With the samples removed, tap **Pump** to keep the system under vacuum.

# Cleanup
1. Upon completion and removal of coated samples, wipe the chamber and door gently with a Kimwipe doused in ethanol.

# Deep Cleaning
Leica states the coater should be deep cleaned every 5 -15 coatings.  However, deep cleaning should also be performed when:
1. There is peeling observed on the metal shielding, shutter and cover glass of the LED light.
1. When a short circuit is detected.
1. When going to base-vacuum takes too long (more than 1 hour for 5x10<sup>-5</sup>)

Inform **Matt Burleson** if the system requires deep cleaning.

# Reference Material
<center>
<img src="sputteringparametersuggestions.png" alt="Carbon Stage Method Edit Screen." width="475"/>
</center>
<center>
<img src="Target Selection Guide.png" alt="Target Selection Guide." width="475"/>
</center>
