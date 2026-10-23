MONOLITH - the RAM free alternative to rainmeter
This application has the feature to run your rainmeter skins natively through the app.
Bugs : 
     1. Battery widget Doesnt work
Features :
          Android-ish widgets with their font styles
Instructions :
NOTE : Only works when you have node.js installed , Use winget install -e --id OpenJS.NodeJS to install Node.js 
1. EXTRACT AND LAUNCH MONOLITH
------------------------------
1. Download MONOLITH-native-skins.zip.
2. Right-click the ZIP file and choose "Extract All".
3. Open the extracted project folder.
4. Double-click start.bat.
5. If the app does not launch, make sure Node.js LTS is installed.

2. OPEN SKIN STUDIO
-------------------
1. Open MONOLITH Settings from the app or its system-tray menu.
2. Navigate to Advanced > Rainmeter-style Skin Studio.

3. IMPORT A SKIN
----------------
Recommended: import the complete skin folder.
1. Download a skin from a source you trust.
2. Extract its ZIP/archive first.
3. In Skin Studio, choose the option to import a skin folder.
4. Select the folder containing the skin's .ini file and any image/resource files.
5. If importing a single .ini file, remember that the skin may need other files from its folder.

Skin sources:
- DeviantArt Rainmeter skins: https://www.deviantart.com/rainmeter
- VisualSkins: https://visualskins.com/

Important: this experimental MONOLITH version does not directly install .rmskin packages.
Look for an extracted skin folder or .ini file instead.

4. RUN A SKIN
-------------
1. Find the imported skin in the library.
2. If it is missing, use Refresh Library if that option is available.
3. Select Run Skin.
4. Start with a simple digital clock or text skin to test compatibility.

5. COMPATIBILITY NOTES
----------------------
This is an experimental native renderer, not a full Rainmeter replacement.

Feature support is limited:
- Basic text and clocks: limited support
- Images and positioning: limited support
- Bars and shapes: partial support
- Variables and simple measures: limited support
- Rainmeter plugins and Lua scripts: not supported
- Complex formulas and interactive Rainmeter actions: not fully supported

A skin may import successfully but still look incomplete or fail to render if it relies
on unsupported Rainmeter features.

6. TROUBLESHOOTING
------------------
Skin does not appear:
- Check that the imported folder contains an .ini file.
- Try refreshing the library.

Images are missing:
- Import the whole skin folder, not only the .ini file.

Skin looks wrong or opens blank:
- Try a simple clock/text skin.
- The skin may rely on unsupported Rainmeter features.

MONOLITH does not launch:
- Confirm Node.js LTS is installed.
- Run start.bat again and read any error shown in the terminal.

7. SECURITY
-----------
Only import skins from sources you trust. The native renderer does not execute imported
scripts or commands; skins that depend on them will not behave like they do in Rainmeter.

TIP
---
Start with a simple clock skin. Once that works, try a system monitor or music skin.
