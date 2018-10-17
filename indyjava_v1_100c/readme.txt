Indiana Java
------------------
Multiplatform Adventure Game Engine


Author: Chir

Please send your questions and comments to chir@geocities.com

Indyjava Web site:  http://java.indy3d.net



Installing and Launching
------------------------------

      1. Download the Indyjava distribution package.
      2. Extract all files from the package into a temporary directory
         using your favorite Zip archiver.
      3. Open INDY.HTM with your browser and follow the instructions.


New Features
------------------




*** Version 1.00c ***

  Scripting language:
      - fixed game loading
      - fixed GIVE
      - added SAYI, SAYIS, WAITSAYI, WAITSAYIS

  User Interface:
      - fixed DEFAULTV
      - added "visit homepage" menu
      - added custom images for UP/DOWN buttons


*** Version 1.00a ***

  Scripting language:
      - added WALKTO, WAITWALKTO, MOVETO, WAITMOVETO
      - added "OnClick" procedure
      - fixed WALK, WAITWALK

  User Interface:
      - added INDY.INI
      - added Help window

  Sounds:
      - fixed Native MIDI support (again,again)


*** Version 0.96a ***

  Graphics:
      - Ink 10 (Brown) fixed!
      - Transitions 5 and 6 fixed
      - Added Transitions 8 and 9 (requires Java 1.2)
      - "Show Boxes" fixed.

  Sounds:
      - MOD files now allowed, if a suitable MCI driver is installed (in Win32)

  User Interface:
      - INDY_APPLET now accepts a custom HTML page for EXIT

  Scripting language:
      - added WALK, WAITWALK
      - support for custom Transition plug-ins (see GOTOTRANSITION)
      - WAIT now also waits for animation stripes to reach the end.


*** Version 0.95e ***

  Scripting language:
      - fixed SENTENCE { * }
      - renaming of *.GAG files by players is no more accepted

  Graphics:
      - Fixed lockup in SETLIGHTING and SETALPHA
      - Ink 10 (Brown) added

  User Interface:
      - double-click in Map Mode


*** Version 0.95d ***

  Scripting language:
      - fixed inheritance
      - added COMMUTATIVE sentences

  Graphics:
      - Triple-buffering for reduced flickering with animated GIFs

  Sounds:
      - fixed Native MIDI support (again)

  User Interface:
      - added support for zero-item verbs


*** Version 0.95a ***

  Scripting language:
      - fixed SAY, fixed BGSOUND problems
      - added SETVERBPREP
      - strict checking of the use of quotes ("")

  Graphics:
      - Fullscreen mode in Win32 (requires DirectX 5)

  Sounds:
      - fixed Native MIDI support (in Win32)

  User Interface:
      - added Font support for verb buttons
      - added "auto-run" feature (000.gag)


*** Version 0.94b ***

  Scripting language:
      - added DELANSWER
      - fixed BGSOUND
      - fixed SETORIENTATION
      - added customisable total number of attitudes
      - fixed LOAD lock-up (in non-Win32 platforms)

  Graphics:
      - Alpha channel for semi-transparent items (requires Java 1.2)
      - Screen motion blur (requires Java 1.2)
      - AVI/MPEG1/MOV video support (requires Java MediaFramework extensions)
      - Support for bundled images: resource.jar

  Sounds:
      - Native MIDI support (in Win32) for enhanced performance
      - added SPEAK, WAITSPEAK (requires Java MediaFramework extensions)
      - added WAITSOUND (requires Java MediaFramework extensions)

  User Interface:
      - added icon support for verb buttons


*** Version 0.93c ***

  Scripting language:
      - added SETROOMBGSOUND, STOPSOUND, SETICON, WAITMOVE
      - fixed SETBGSOUND
      - fixed GIVE
      - fixed SETANIMATION

  User Interface:
      - interface layout now customisable


*** Version 0.93b ***

  User Interface:
      - keyboard bug fix

  Scripting language:
      - Single inheritance between Items and rooms.

  Graphics:
      - Color lighting of items


*** Version 0.92g ***

  User Interface:
      - custom "hot" cursors
      - keyboard shortcuts for verbs
      - custom button colors

  Scripting language:
      - Console (to type language instructions while testing the game)
      - SIZE keyword for image-less Items

  Graphics:
      - Animation stripes for reduced flickering (animated GIFs are still supported)
      - "map" mode
      - Visual transition effects between rooms



[END OF DOCUMENT]