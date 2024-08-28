---
title: "Downloads"
weight: 1
---

# <center>Version changelog</center>

<br>

***v1.4.3***:

### Changes by @GBotHQ
* Lowered OpenGL version requirement to version 3.1 (Compatibility with older systems)
* SpinBox and DoubleSpinBox live update, keybind for stepping 10 at a time (hold shift while changing values)

### Changes by @p-yukusai 
* Added Autosaves
* Allow for copying, pasting and deleting keys through keybinds (Ctrl-C, Ctrl-V & Ctrl-X)
* Fixed networking
* Option to download AnimeEffects from the "Check for Updates" menu
* Option to automatically show mesh when selecting FFD
* Added FFmpeg check before exporting
* Added an FFmpeg helper to the options menu (Troubleshoot and setup)
* Bugfixes
* Minor string changes
* Updated JP translations
* Added a button to reset your keybinds to the default
* Added missing default keybinds
* Ubuntu Bionic builds have reached EOL

**Version Merge**: https://github.com/AnimeEffectsDevs/AnimeEffects/pull/24 <br>
**Full Changelog**: https://github.com/AnimeEffectsDevs/AnimeEffects/compare/v1.4.2...v1.4.3

{{< button "https://github.com/AnimeEffectsDevs/AnimeEffects/releases/v1.4.3" "Download here">}}

<br><br>

***v1.4.2***:

- Added new animation key (Hue, Saturation & Value, or HSV) for layer nodes, folder support is not ready but can be opted into. 
  -  Special thanks to Gambot for making this feature possible by writing the shader for it and helping with other OpenGL issues.
- Added a new settings tab called "Animation keys", where you can change your preferences. At the moment there are three settings to modify the new HSV keys' behaviour.
- Added new "Reset recent files list" button to the settings.
- The timeline will now automatically stop when it reaches its final frame and it's not looping.
- Reworked most of the text to (hopefully) be easier to understand.
- Adjusted the Japanese translation to match with the previous change.
- Allowed keybinds to be repeated (with a delay of 125ms)
- Association handling, this means that you can double click your .anie projects, and set AnimeEffects as the program to open them with.
- Fixed optimized palette exporting
- Added a warning when exporting with odd height or width values, as that may break the rendering pipeline.
- Added a "Check for Updates" button in the "Help" menu.
- Added an optional filewatcher in the resource window, you now may watch for changes to your image files and automatically reload them within the project when a change is detected.
- Simplified resource addition by just having an "Add resources" button instead of a menu
- Added option to change FPS playback speed within the "Project" menu, this is saved on the project itself.
- Changed "Open Recents" to read from QSettings instead of a file.
- Added support for importing .webp and .tiff images
  -  Tiff images gets imported as a single layer, no layered support is currently available.
- Fixed all known bugs with the "breeze_dark" theme
- Fixed all GitHub actions
- Added nightly artifacts to all actions.
- ##### BREAKING CHANGE: Bumped Project version from 0.5 to 0.6, this makes it so you *cannot* load projects made with this new version on older versions of AnimeEffects.

{{< button "https://github.com/AnimeEffectsDevs/AnimeEffects/releases/v1.4.2" "Download here">}}

<br><br>

***v1.4.0***:

* A new dark theme has been added (breeze_dark)
* A lot of new scripts for building and deploying have been made
* Version bump from 1.3.5 to 1.4.0
* Added keybindings for
	* Timeline movement (Ctrl + Left or Right arrow keys)
	* Jumping to the first or last frame (Ctrl + Up or Down arrow keys)
	* Toggle Looping (Ctrl + R)
	* Toggle playback (Ctrl + Spacebar)
	* Toggle docks (Ctrl + Q)
* Fix pull bones feature (thanks to aoi for reporting and Larpon for the help diagnosing)
* Fix FFMPEG exporting, so now you can export to every available format file! (Please don't have '%20' in your file name to ensure this works properly)
* Reduced minimum OpenGL version from 4.0 to 3.3
* Fix MathUtil (this fixed the pull bones feature, along with other things that I may have failed to notice)
* When opening a recent file, if it is not found it will be automatically deleted from the record (changes will apply on your next restart)
* Upgrade Linux CI to Ubuntu 20.04 Jammy, a compatibility version for older distros has been made available.
* Fixed MacOS CI, a zip containing AnimeEffects.app has been made available.

**Full Changelog**: https://github.com/AnimeEffectsDevs/AnimeEffects/compare/v1.3.4...v1.4.0

{{< button "https://github.com/AnimeEffectsDevs/AnimeEffects/releases/v1.4.0" "Download here">}}

<br><br>

***v1.3.5***:

* Added option to open recent projects
* Changed "about" section to better reflect current development
* New section in the options menu to setup the default easing and range types for new keyframes
* Debug version available

**Full Changelog**: https://github.com/AnimeEffectsDevs/AnimeEffects/compare/v1.3.4...v1.3.5

{{< button "https://github.com/AnimeEffectsDevs/AnimeEffects/releases/v1.3.5" "Download here">}}

<br><br>