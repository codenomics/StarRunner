# StarRunner

> This application is built by AI. I made this for myself and I'm uploading it to GitHub for backup and to share in case anyone can get any use out of it. It's pretty specific to my setup and my needs, but if you can get any use out of it, then enjoy.
>
> Use at your own risk. I offer no warranty or guarantees for this software.

## Download

**Latest version: v1.7** (Oct 11, 2026)

- [StarRunner_v1.7_no-install.zip](https://github.com/codenomics/StarRunner/releases/download/v1.7/StarRunner_v1.7_no-install.zip) - 537 KB
- [StarRunner_v1.7_Setup.exe](https://github.com/codenomics/StarRunner/releases/download/v1.7/StarRunner_v1.7_Setup.exe) - 599 KB
- [StarRunner_v1.7_source.zip](https://github.com/codenomics/StarRunner/releases/download/v1.7/StarRunner_v1.7_source.zip) - 525 KB

What's new in v1.7:

- New Hauling tab: add your cargo contracts and get the best order to fly them
- Knows your ship's cargo space and splits big contracts into trips
- Routes through other systems when a gateway detour is shorter, and shows the jumps
- Choose shortest distance or fewest stops, start where you are in game, tick stops off as you fly
- Places and distances come from UEX Corp and update by themselves once a week
- Inventory: places with nothing in them are hidden, -1/+1 and icon buttons on each item, SCU box counter, more places including Nyx
- Hauling: full ship list with search, and My ships to add your own
- Hauling: optional cargo map - draw your ship's cargo grid once, type the boxes from the freight elevator, and see where every box goes at each stop (first off nearest the ramp); drag a box to move it, right-click to turn it
- Hauling: three-column layout (planning, best route, cargo map), Clear contracts button, a box-sizes button on each contract, and how full the hold is at every stop
- Tabs renamed: Citizens, Mining and Language Packs

Older versions are on the [Releases page](https://github.com/codenomics/StarRunner/releases).

## Getting started

### Installer (recommended)

1. Download the file ending in `_Setup.exe` above.
2. Double-click it and click Install. It installs just for you - no admin password needed - and adds Start menu and Desktop shortcuts.
3. To remove it later: Windows Settings > Apps, find StarRunner and click Uninstall.

### No install (portable zip)

1. Download the file ending in `_no-install.zip` above.
2. Right-click it > Extract All, and pick a folder. Don't run it from inside the zip.
3. Open the folder and double-click the app's .exe. Nothing is installed; delete the folder to remove it.

Windows says "Windows protected your PC"? Click More info > Run anyway. It shows that for apps without a paid signing certificate.

## Source code

Want to see how it works, or build it yourself? Download the file ending in `_source.zip` above, extract it and double-click `Build.bat`. It only uses the C# compiler that already comes with Windows, so there is nothing to install.

## More details

```
STARRUNNER
==========

All your Star Citizen tools in one window, with a tab for each tool.
The Citizens tab looks up a Star Citizen player by their handle and shows
their public RSI profile: avatar, citizen record number, enlisted date,
location, fluency, badge, organizations (with their rank) and bio.
The Mining tab reads the mining scan number off your screen in Star
Citizen and shows which rock it is in a small see-through overlay.
The Language Packs tab edits the game's language file (global.ini) and keeps your
edits so they can be put back on every new version. The Notes tab is a light
notepad: a list of notes on the left and the text on the right. The Inventory
tab keeps track of what you have stored where, across the universe, and knows
where you last opened your inventory in game. The Hauling tab works out the
best order to fly your cargo contracts.


GETTING STARTED
---------------
Pick one. Both give you the same app.

OPTION 1 - INSTALLER (recommended)
  Download the file ending in _Setup.exe, double-click it and click Install.
  It installs just for you (no admin password) and adds Start menu and
  Desktop shortcuts. Needs Windows 10 or 11 (64-bit).
  To remove it later: Windows Settings > Apps > StarRunner > Uninstall.

OPTION 2 - NO INSTALL (zip)
  1. Download the file ending in _no-install.zip. Right-click it -> Extract
  All... and put the StarRunner folder somewhere it can stay (for example
  Documents). Don't run it from inside the zip.
  2. Double-click StarRunner.exe. Nothing is installed; to remove it, delete
  the folder.

"Windows protected your PC"? Click "More info" -> "Run anyway".
Windows shows that for apps downloaded from the internet that aren't
signed with a paid certificate.


USING IT
--------
- Click a tab at the top to switch tools. StarRunner remembers the tab you
  had open. Drag a tab sideways to put the tabs in your own order. The window
  can be resized and maximized.
- Home tab: a quick look at each tool, plus a Look picker with five color
  looks (Synthwave, Ocean, Ember, Forest, Graphite). Pick one and click
  Restart now to use it.
- Citizens tab: type a player's handle (the name in the address of their
  RSI profile) and press Enter or click Look up.
- Mining tab:
  1. Click Pick area, switch to the game and scan a rock so the number shows.
     After 5 seconds the screen freezes - drag a box around the number.
     (Any game window mode works: Borderless, Windowed or Fullscreen.)
  2. Click Start reading. The overlay shows e.g. "3x Titanium" while the
     number is on screen. It keeps working while you use the other tabs.
  The Signatures button opens the table of scan numbers (you can fix or add
  values after game updates). Press F1 for more help.
- Language Packs tab:
  1. Click Choose language file (or drag a global.ini onto the window). "Get
     newest" downloads a community language pack from GitHub.
  2. Search the list, click an entry and type in the Current value box.
  3. Save my changes keeps just your edits in a small file (Documents\LangRunner).
     When a new version of the file comes out, open it and click Load my
     changes to put your edits back on it.
  4. Save to game puts the file into Star Citizen and backs up the old one.
     Windows may ask for permission to write there - click Yes. Backups...
     lists the backups so you can put one back. Press F1 for the guide.
- Notes tab: click New note and type. The first line is the title. Notes save
  by themselves and are plain text files in Documents\StarRunner Notes.
- Inventory tab:
  1. Open your inventory in game at a station or city, then click Add item.
     StarRunner picks that place for you (it reads the game's log file). Pick
     the type, type the name and the amount (units, SCU or cSCU) and click
     Add, or Add + next to keep going. With SCU you can also type how many
     cargo boxes and their size (for example 8 x 8 SCU) and it works out the total.
  2. Your places are listed on the left by system and planet. Click one to
     see what's there. All items adds up the same things across every place.
  3. The search box looks through every place at once. Double-click a result
     to go there.
  4. Each item has small buttons: -1 and +1 to change the amount quickly,
     then edit, move (all of it or part of a stack) and remove.
     Right-click a place to rename it, make it your home, or remove it.
  5. Tools: Set home location, Move everything home (after a patch moves your
     stuff), Back up / Load a backup, Item colors and Clear all.
- Click any name in the Recent list to look that player up again.
- Their organizations are listed with the player's rank in each. Click one
  to see its Overview, History, Manifesto, Charter and a Members list.
- "Open on RSI website" opens their page in your browser.


- Hauling tab:
  1. At the top left, pick your ship (or type its cargo SCU), where you
     start, and Shortest distance or Fewest stops.
  2. Click Add contract for each hauling job: where it's picked up, where it
     goes, how many SCU (and the reward if you like). Each contract has
     buttons to edit or remove it. Clear contracts empties the whole list
     (it asks first).
  3. The best order shows in the middle: each stop with what to load and
     unload, the distance flown and any gateway jumps. Tick stops off as you
     fly them. Big contracts are split into trips that fit your ship.
  4. Ship list: type part of a name to find it. My ships... adds your own.
  5. Cargo map (optional): tick "Show the cargo map", pick your ship and click
     Edit grid to draw its cargo hold once (squares across, long and high, and
     the ramp edge). In each contract you can type the boxes the freight
     elevator lists, or click the boxes button on a contract to set them
     later. The map shows in its own column on the right. Click a stop to see
     where every box sits: Arrive shows
     what to take off, Leave shows what was put on. Drag a box to move it,
     right-click to turn it.

GOOD TO KNOW
------------
- The Citizens tab only reads public pages on robertsspaceindustries.com.
  Nothing about you is sent anywhere.
- The Mining tab only looks at the box you picked on your screen, using
  the text reader built into Windows, and never touches the game. It needs an
  English text-reader language in Windows (Settings > Time & language >
  Language & region); most PCs already have it. Parts a player keeps private show as "-".
- The Hauling tab gets places and distances from UEX Corp (uexcorp.space), a
  public Star Citizen trade site, once a week. Nothing about you is sent.
- The Inventory tab only reads the game's log file (Game.log in the game's
  LIVE folder) to see where you last opened your inventory. It never changes
  anything in the game. If it can't find the log, use Tools > Find the game's
  log file. Your inventory is kept in %APPDATA%\StarRunner\inventory.txt.
- The Language Packs tab only writes to the game's language folder when you click
  Save to game (and it backs up the old file first). Language packs come
  from public GitHub pages; nothing about you is sent.
- RSI has no official lookup service, so if RSI changes its web page some
  details may come up blank.
- Your recent lookups, settings and the Mining signature table are kept in
  %APPDATA%\StarRunner. Language Packs changes files and downloaded packs are kept
  in Documents\LangRunner, and your notes in Documents\StarRunner Notes.
- Updates: a few seconds after it starts, StarRunner checks GitHub for a newer
  version (it only reads the public release page; nothing is sent). If there
  is one, "Update available" shows at the top right; click it to update. With
  the installer, it downloads and runs the new installer for you; with the
  no-install zip, it opens the download page. Right-click "Check for updates"
  to turn the startup check on or off.
- If something goes wrong, StarRunner-log.txt next to StarRunner.exe says what.
- To remove StarRunner: delete its folder and %APPDATA%\StarRunner.
```

