<!-- ---
output:
  html_document:
    theme: united
--- -->
# Perkin Elmer Spectrum One FT-IR Spectrometer (NS 226)
AF v20190116

> *If you encounter problems while running the Spectrum One, please use submit an [**Instrument Incident Report**](https://docs.google.com/forms/d/e/1FAIpQLSc96MiK73kKP06KEZpR0-O7zETCLvWgQtLp_bKEynosUKqpNg/viewform) with a description of your problem.  **For urgent problems please report to Al Fischer, NS 209, dfischer@wcu.edu, x2695!***

# Setup and Acquire Background

1. Login to the computer using `.\labuser` and `labuser` as the username and password, respectively.
1. Open the FTIR software by double clicking the **Spectrum IR** icon on the desktop and select the correct username when prompted.
    - Please select the correct username based on your class or research group; there is no password.
    - If you have not been assigned a specific username, use the `labuser` account.

    > Using the appropriate username loads the correct data paths, spectral libraries, and other settings.

3. Remove the blue protective cover from the FT-IR ATR cell.
4. Acquire a background spectrum by clicking **Background** in the FT-IR software ribbon.

     > You can change how often a background is acquired by going to **Setup > Setup Instrument Data Collection [tab]** and choosing the option you desire under **Background Options**.

# Acquire a Spectrum

1. Enter a name a for the sample in the **Sample ID** field in the toolbar.
    - By default, the samples are named by date: `2018 12 4 2018 nnn`, where `n` is auto-incremented sample number.
    - You may change the ID if you wish; it determines the name of your datafiles.
1. Click **Scan** (orange play button) in the FT-IR toolbar to bring up a real-time preview.
1. Ensure the background spectrum is still good and the ATR window is clean by examining the blank spectrum.
1. Load a *small* amount of sample onto the ATR window (just enough to cover the window).
1. Rotate the **anvil arm** into place and lower the anvil by rotating the **steel knurled knob** on the top of the instrument.
    - You do not need the anvil for most liquid samples.
    - Watch the spectrum "grow in" as you lower the anvil; stop when you have applied enough pressure to obtain a good spectrum.
    - In general, you will probably want the force gauge in the software to read **50-60** for a good spectrum.
1. Press **Scan** when you are satisfied with the preview spectrum.
    - Your data will be automatically saved as a spectral file , e.g., `2018 12 4 2018 nnn.sp` and a CSV file, `2018 12 4 2018 nnn.csv`, or according any other sample ID you supplied.
    - The default file path is `C:\Users\labuser\Documents\Spectrum One Data Folder\` for spectral files and `C:\Users\labuser\Documents\Spectrum One Data Folder\labuser` for CSV files.
    - Usernames other than `labuser` may export elsewhere.

# Examine and Print a Spectrum

> The following steps assume your sample is selected in the sample tree and you are looking at the tab matching your sample name (i.e. your spectrum).

1. To print only your spectrum, select it from the data explorer tree on the left and ensure the tab matching your sample name is selected above the spectrum window; click **Print**.

<!-- 2. For *known samples* (e.g. something you've synthesized), you can *compare* it to a standard spectrum.
    - To load a spectrum for comparison, click the **Compare** selector on the right side of the software in the **Setup Pane**.
    - Choose the **Setup Compare References** tab and add any spectra you would like to compare to by clicking **Add** or clicking the **Include** checkbox if it's already listed.
    - Run the analysis by selecting your sample in the spectrum tree on the left and clicking the **Compare** button above the spectrum.
    - To print a report of the comparison, select the **Compare Tab** at the top of the spectrum and choose **Print**.
    - To return to your spectrum, select the tab matching your sample name.
1. For *unknown samples*, you can *search* the built-in libraries.
    - Click **Search** above your spectrum.  This will automatically bring up the *Search* tab.
    - You can print the two spectra overlaid on each other by **right clicking the spectrum** and choosing **print**.
    - To print a full report of the search, click **Print** in the ribbon.
    - To return to your spectrum, select the tab matching your sample name. -->

2. To label peaks, click **Labels** above your spectrum.
    - You can click and drag or delete specific labels.
    - You can change the labelling parameters by clicking on **Peak Detection** in the **Setup Pane** on the right side of the software.

# Shutdown
1.  Please leave the FTIR cleaner than you found it.
    - Wet a Kimwipe with acetone and clean the ATR window and the metal plate surrounding it.
    - Use the Kimwipe to clean the anvil (the tip slides off).
    - Use a brush to dust off any powder from the instrument.
    - Brush or shake off the protective plastic cover on the ATR cell.
    - Replace the protective cover on the ATR cell.
1. Close the software and logoff of the computer.
    - *Do not turn the FT-IR off -- it takes several hours to warm up.*
