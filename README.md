Compare Side-By-Side
================
This package adds a simple side-by-side comparison tool to Sublime Text 2 and 3.

![Screenshot](https://dougty.com/files/SBSCompareScreenshot5.png)

Features
---
  - Easily select two tabs or selections to compare
  - Comparison results open in a new window
  - Empty lines added so common code lines up
  - Count number of lines changed
  - Highlighting of changed lines
  - Intra-line diff highlighting
  - Synchronized scrolling


## Installation

### By Package Control

1. Download & Install `Sublime Text 3` (https://www.sublimetext.com/3)
1. Go to the menu `Tools -> Install Package Control`, then,
   wait few seconds until the `Package Control` installation finishes
1. Go to the menu `Preferences -> Package Control`
1. Type `Package Control Add Channel` on the opened quick panel and press <kbd>Enter</kbd>
1. Then, input the following address and press <kbd>Enter</kbd>
   ```
   https://raw.githubusercontent.com/evandrocoan/StudioChannel/master/channel.json
   ```
1. Now, go again to the menu `Preferences -> Package Control`
1. This time type `Package Control Install Package` on the opened quick panel and press <kbd>Enter</kbd>
1. Then, search for `SideBySideCompare` and press <kbd>Enter</kbd>

See also:
1. [ITE - Integrated Toolset Environment](https://github.com/evandrocoan/ITE)
1. [Package control docs](https://packagecontrol.io/docs/usage) for details.


Usage Options
---
  - Right click on a tab and select "Compare with..."
  - Right click somewhere in the active view and select "Compare with..."
  - Right click on a tab and select "Compare with active tab"
  - Highlight text, right click -> "Mark selection for comparison"
   - Mark a second selection, then right click -> "Compare selections"
  - Create two selections by holding CTRL, then "Compare selections"
  - From the command line: [see README_COMMANDS.md](README_COMMANDS.md)
  - Jump to next: `Alt+N`, Jump to previous: `Alt+P`

Configuration
---
  - Highlight colours and other options can be configured in SBSCompare.sublime-settings
  - Hotkeys can be changed in the included `Default (PLATFORM).sublime-keys` files
  - To access: *Preferences -> Package Settings -> Compare Side-By-Side*

License & Contributing
---
 - [MIT license](LICENSE)
 - Pull requests welcome!
