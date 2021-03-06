[![License](https://img.shields.io/badge/license-Public%20Domain-blue.svg)](https://github.com/tekezo/Karabiner-Elements/blob/master/LICENSE.md)

# Karabiner-Elements-Neo

Karabiner-Elements-Neo implements the layer 4 and 6 of the [Neo2 keyboard
layout](http://neo-layout.org/) for macOS Sierra. It is based on
[takahasix' fork](https://github.com/takahasix/Karabiner-Elements) of
[Karabiner-Elements](https://github.com/tekezo/Karabiner-Elements), a subset of
the next generation Karabiner for macOS Sierra.

## Project Status

Beta, please report any bugs or incomplete installation instructions as GitHub
issues.

## Installation

I do not have an Apple Developer license at the moment that would me allow to
distribute a ready-made installable package. Thus, it is necessary to build
Karabiner-Elements-Neo yourself.
[Follow these instructions.](https://github.com/jgosmann/Karabiner-Elements-Neo/wiki/How-to-build-Karabiner-Elements-Neo)
Once you build the installable package:

1. Open the DMG file and follow the instructions.
2. Open Karabiner-Elements and add the following “Simple Modifications”:
   * `backslash (\)` to `right_option`
   * `caps_lock` to `right_option`
   * ``grave_accent_and_tilde (`)`` to `right_command`
3. Download the keyboard layout file and move it either to
   `~/Library/Keyboard Layouts` (personal installation) or 
   `/Library/Keyboard Layouts` (system wide installation). You have the choice
   between to keyboard layout files:
   * [The one provided on neo-layout.org.](http://wiki.neo-layout.org/browser/mac_osx/neo.keylayout?format=raw)
   * [Or my modified on](https://github.com/jgosmann/neo2-layout-osx) which
     mainly improves the caps lock layout (e.g. use shift to type lowercase).
4. Select the Neo2 keyboard layout in your system settings.
