Title: Release 1.1.2
Published: 3/1/2015
Category: Release
Author: punker76
---

# Bugfixes / Changes

- Added alignment properties for `MetroDataGridRowHeader` style #1819
- Fixed Gripper for `MetroDataGridRowHeader` style #1822
- Fixed runtime change of `IgnoreTaskbarOnMaximize` with a maximized window (there was a bug with the frame) #1823 (39a7e05)
- Fixed upgrading the `WindowPlacementSettings` on version change #1787 #1736 (ada352b)
- Fixed a painting issue of the entire window and the maximize action (5ae97f9)
- Fixed another `Topmost` bug: Window is going behind other windows on program start #1251 (6b0a8fa)
- Fixed brief flashing window when launched (e.g. from the explorer) #1781 (4b42fe0)
