# MetaDarkStyle

## What is this?
MetaDarkStyle adds dark theme to LCL/QT apps under Windows 10 or later.

## Packages
- `metadarkstyle.lpk` is the base package and contains the basic logic to apply the dark theme.
- `metadarkstyledsgn226.lpk` is for adding dark theme to Lazarus IDE 2.2.6
- `metadarkstyledsgn.lpk` is for adding dark theme to Lazarus IDE trunk (i.e latest version)

<details>
  <summary>Screenshots/Preview</summary>
  <img src="https://github.com/zamtmn/metadarkstyle/blob/main/docs/2.png" />
  <img src="https://github.com/zamtmn/metadarkstyle/blob/main/docs/1.png" />
</details>

## System requirements
- Windows 10 1809 or later
- FPC 3.2.2 or trunk
- Lazarus 2.2.6 or trunk

## Installation/Updating from older versions
0) To use this package, you will need Lazarus 2.2.6 or trunk on Windows 10
1) If you have the old version of `metadarkstyledsgn` on Lazarus 2.2.6 - uninstall it before you update the package
2) Open `metadarkstyle.lpk` as a package, compile it, and install it
3) If you're using Lazarus 2.2.6, compile and install `metadarkstyledsgn226.lpk`. If you're using Lazarus from trunk, compile and install `metadarkstyledsgn.lpk` instead
5) Restart the IDE and you should be seeing your IDE in dark mode
6) For further configuration, go to **Tools > Options > Enviornment > Dark Style**

## License
GNU Lesser General Public License as published by the Free Software Foundation either version 2.1
of the License, or (at your option) any later version.
