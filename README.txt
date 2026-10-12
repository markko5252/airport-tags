AIRPORT TAGS 1.0 for Microsoft Flight Simulator 2024
by Mark Korolevich (Link Airways)
====================================================

Floating ICAO codes above every airport near you - readable in 2D and VR, day and
night - plus an "Airport Tags" app on the EFB tablet listing each nearby airport's
name, distance, bearing (with a direction arrow) and elevation.


INSTALL
-------
1. Close Microsoft Flight Simulator 2024.
2. Unzip this download (right-click the zip > Extract All...). You can extract it
   to any folder you like - Downloads, Documents, wherever. It doesn't need to
   go on your desktop.
3. Open the unzipped folder and double-click  Install.bat
   - If Windows shows "Windows protected your PC", click "More info", then "Run anyway".
     (Airport Tags isn't signed with a paid certificate; that's all this warning means.)
4. When it says "Done!", press any key to close the window.
5. That's it. The installer copies everything it needs into place, so you can
   delete the zip file and the unzipped folder afterwards if you like.
   (Keep them only if you want Uninstall.bat handy - though re-downloading
   works too.)

The installer finds your Community folder by itself (Microsoft Store and Steam
versions both work) and adds Airport Tags to the sim's startup list. Your other
add-ons are left as they are; a copy of the original startup list is kept as
exe.xml.before-airporttags.


USING IT
--------
- Just start the sim and load a flight. Airport Tags starts and stops with the sim
  automatically - there is nothing else to run.
- Tags appear over airports within 10 nm and resize with distance.
- On the EFB tablet, open the "Airport Tags" app for the list.
  The Settings button changes:
    Range      5 / 10 / 15 / 20 / 25 nm
    Helipads   hide or show
    3D tags    on or off (the list keeps working with tags off)
  Settings are remembered between flights.


UNINSTALL
---------
Close the sim and double-click  Uninstall.bat


IF SOMETHING ISN'T WORKING
--------------------------
- Tablet says "Waiting for the Airport Tags app...": restart the sim once after
  installing. If it persists, look at the log file:
     %LOCALAPPDATA%\Programs\AirportTags\AirportTags.log
  (paste that line into the File Explorer address bar)
- No tags in the sky: check the tablet app's Settings - "3D tags" must be On.
- Send the log file to Mark along with a screenshot.


LEGAL
-----
Copyright (c) 2026 Mark Korolevich (Link Airways). All rights reserved.
Free for personal use. Please don't sell it, re-upload it elsewhere, or share
modified versions without permission. Provided as-is, with no warranty.
Full terms: LICENSE.txt. Credits for components by other authors:
THIRD-PARTY-NOTICES.txt.
