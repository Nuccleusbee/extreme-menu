# Extreme Menu

A mod menu for **GTA V story mode** (Legacy and Enhanced), drawn by the game itself. It switches itself off in GTA Online.

## Install

1. Download **ExtremeMenuInstaller.exe** from the [latest release](../../releases/latest) and run it. Windows may warn you about an unknown publisher: click *More info* > *Run anyway*.
2. It finds your GTA V folder (Steam, Epic or Rockstar). If it doesn't, click **Browse** and pick `GTA5.exe` or `GTA5_Enhanced.exe`.
3. Click **Install**. The first time, it opens the Script Hook V page: download the zip into your Downloads folder (don't unzip it), then click **Install** again.

The installer sets up Script Hook V, Script Hook V .NET and the menu. Any file it replaces is backed up to `ExtremeMenu-backup` in your game folder. Run it again any time to update to the latest version.

## Use

- Open the menu in story mode with **F9** or the **mouse back (thumb) button**. On a controller, hold RB and press D-pad Right.
- You can change the keys in `scripts\ExtremeMenu.ini`.

## If the game won't start with mods

- **BattlEye:** turn it off in Rockstar Games Launcher > Settings > Grand Theft Auto V.
- **After a GTA update:** Script Hook V stops working until it is updated. Download the new one from [dev-c.com](http://www.dev-c.com/gtav/scripthookv/) into Downloads, then run the installer again.

## Manual install

Copy `ExtremeMenu.dll` and `ExtremeMenu.ini` into `scripts\` in your GTA V folder. You need [Script Hook V](http://www.dev-c.com/gtav/scripthookv/) (the whole `bin` folder) and [Script Hook V .NET](https://github.com/Chiheb-Bacha/ScriptHookVDotNetEnhanced/releases) in the game folder.
